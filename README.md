This program was created with the purpose of taking an inputted list of single word items and counting them by number ot listing them in the form of a histogram.

I think I implimented the file reading well because I find it particularly difficult to create output files that read the right information correctly.

I think I could have improved this code by having all the histograms start at the same point so their lengths are actually reliable to determine what word appears most. I think I also could have made the list alphabetic to make sorting through the numbered words easier.

I found it most difficult to figure out how to read from teh file via a class, speciifcally counting the words occurences.

I think being able to read from files and use that data is going to be very useful for corporate purposes of having to take informationa and process it.

I think the use of the class kept this code clean, because typically I would have copy an dpasted the code over and over which could ahve caused problems. However, with classes repeated steps are much more compacted in the main program.

This code implements the class and main in the same source code under the main.cpp. The class, named WordFrequencyAnalyzer, utilizes a public and private section to display the menu and allow the options to run as desired. The private section of the class uses the input file, ‘CS210_Project_Three_Input_File.txt,’ to count each word listed on it. It uses a function called countWords() to identify each word and count its occurrences via incrementing. The public section of this class is the main meat of the code, prompting the user for options 1 2 3 or end. Option 1 utilizes wordCount(), declared in the private section, to recall the value already counted and stored using the chunk of code above. Option 2 outputs frequency.dat to the screen, which stored the values of countWords() in the data file. Option 3 utilizes wordCount to get the number of occurrences in each word, taking that information and incrementing using i as a counting value to output a star for every word occurrence. The end option just breaks the program to force it to end. Finally, there is feedback if there is an input that doesn’t follow one of the options to prompt the user to input their selection differently.
