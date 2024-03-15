# Word Count from File

This Java program reads a text file, counts the occurrences of each word, and displays the word count for each unique word in alphabetical order.



## Instructions for Running and Testing the Java Program:

1. Clone the repository to your local machine using the command:
- git clone repository_link
2. Navigate to the directory containing the Java program.
3. Open the WordCountFromFile.java file and update the filePath variable with the path to your input text file.
4. Compile the Java file using the Java compiler:
- javac WordCountFromFile.java
5. Run the compiled Java program:
  - java WordCountFromFile
6. Verify that the word counts are displayed correctly according to the input text file.

7. Optionally, modify the input text file or test with different input files to verify the program's robustness.
    
  
## Functionality
- Reads the content of the specified text file.
- Counts the occurrences of each word.
- Removes punctuation marks and converts words to lowercase for accurate counting.
- Utilizes a TreeMap to store word counts in alphabetical order.
- Displays the word count for each unique word in alphabetical order.
## Dependencies

- This program only relies on standard Java libraries and does not require any external dependencies.
## Error Handling

- Handles IOExceptions that may occur during file reading, printing error messages to the standard error stream if an error occurs.
## Contributing

Contributions are welcome! If you have any suggestions for improvement or find any issues, feel free to submit a pull request or open an issue.
