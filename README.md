/*
Object oriented programming Midterm question 6


Complete the 
char[] decomposeString(String word)
method that returns the array of characters that compose the input string word
Hint: The expression s.charAt(i) returns the character at position i of the string s.
For example:
Test	Result
String word = "Auckland";
System.out.println("Auckland 1st char is: "+(decomposeString(word)[0]));	Auckland 1st char is: A

String word = "JAVA";
System.out.println("JAVA 2nd char is: "+(decomposeString(word)[1]));	JAVA 2nd char is: A

String word = "COMP503";
System.out.println("COMP503 5th char is: "+(decomposeString(word)[4]));	COMP503 5th char is: 5

String word = "my_array";
char[] array = decomposeString(word);
for(int i = 0;i < array.length;i++)
{
System.out.println("Char "+i+" is: "+(array[i]));
}	Char 0 is: m
Char 1 is: y
Char 2 is: _
Char 3 is: a
Char 4 is: r
Char 5 is: r
Char 6 is: a
Char 7 is: y


Starter code
char[] decomposeString(String word)
{
    
   return null;
  
}
*/
char[] decomposeString(String word)
{
    char[] result = new char[word.length()];
    for (int i = 0; i < word.length(); i++) {
        result[i] = word.charAt(i);
    }
    return result;
}
