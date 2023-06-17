# jsonproject

This Java program reads a list of JSON objects from a JSON file, processes each object based on the type of question, and writes the output to another JSON file.

![image](https://github.com/MOHDSAMIULLAH/JSON-project/assets/91786605/858fc276-a09a-4492-a07e-b1d00760d150)


## Requirements

- Java Development Kit (JDK) 8 or above
- json-simple library (included in the project)

## Usage

1. Clone the repository or download the source code.

2. Ensure you have Java installed on your machine.

3. Place your input JSON file in the project directory. The file should have the following format:

   ```json
   [
     {
       "type": "first non repeating",
       "input": "aaabcd"
     },
     {
       "type": "first repeating",
       "input": "skrrt"
     },
     ...
   ]
4. Open a terminal or command prompt and navigate to the project directory.

5. Compile the Java source code by running the following command:</br>

      <b>javac -cp lib\\* src\test\java\jsonproject\jsonproject\ReadDataFromJSON.java</b>

6. Run the program using the following command:
    
   <b> java -cp lib\\* src\test\java\jsonproject\jsonproject\ReadDataFromJSON.java jsonfiles\input.json</b></br>
   
This will process the input JSON file and generate an output JSON file named output.json in the project directory.

7. Once the program finishes execution, you can find the output JSON file (output.json) in the project directory. The file will contain a list of strings in the same order as the input JSON file, representing the processed results.

The program uses the json-simple library (https://mvnrepository.com/artifact/com.googlecode.json-simple/json-simple/1.1.1) for parsing and manipulating JSON data. You can include the library by downloading the JAR file and adding it to your project's dependencies.
