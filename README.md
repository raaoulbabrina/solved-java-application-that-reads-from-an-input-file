Download Link: https://assignmentchef.com/product/solved-java-application-that-reads-from-an-input-file
<br>
5/5 - (2 votes)

I.Java application that reads from an input file, which contains your data from Assignment #2 in CSV (Comma Separated Values) format, stores the data in an array of objects, and outputs the array to the screen. We are still re-doing sample #2, but using an input file, classes, and arrays of objects instead!



A.  The 1st step is to make your CSV file. Open up jGRASP. Cick: File, New, Plain Text, to create a new text file. Then, save the file as a CSV file by adding the .csv file extension when you save it: filename.csv Otherwise, open up a CSV excel file and type in your data. The 1st row should be the column names, separated by commas. The 2nd row, 3rd row, etc. should be the data from Assignment #2. Add a little more data, so you have at least 10 rows of data. Here is an example CSV file from the grocery list program: groceries.csv. And here is an exaple CSV file from my “Marine Mammals of Hawai’i” example: mammals.csv

B.   The 2nd step is to write your program! Here is starter code: LastnameFirstname09.java You will have two classes – your public class LastnameFirstname09 and class HawaiianTheme.

** The class HawaiianTheme does NOT have the public modifier. **

** The class HawaiianTheme is NOT nested inside public class LastnameFirstname09. **

** The class HawaiianTheme is a class definition, which contains the variables (data fields) and methods to define objects, which store data. **

C.  class HawaiianTheme is the type of data that you stored in your input file. For example, I am using “Marine Mammals of Hawai’i”, so my class is: class MarineMammalsOfHawaii

D. The 1st commandline argument (args[0]) is the name of your input file that you just created. Have some error checking to make sure there is only one command argument.

E. In your main() method, make an array of objects of class class HawaiianTheme. Display the array on the screen – it should be all nulls at this point.

F.  The next step is to initialize the array with the data from the file. Earlier this semester, we read a file and stored it in an array with this program: ArrayBasedGroceryList.java

G. Before we store data in our array of objects, we have to create data fields, a constructor, and toString() method for class HawaiianTheme.

H. Below your public class LastnameFirstname09 class, create data fields, a constructor, and toString() method for class HawaiianTheme.

I. Create three data fields – one data field for each of the attributes, which is the same as the three column names, in your class HawaiianTheme. For example, for my class MarineMammalsOfHawaii, I have these data fields: name, population, and length.

J.  Write the constructor for your class HawaiianTheme. You should have a three parameters, which initialize your three data fields. For example, I have three parameters of type String, Integer, and Double in my constructor.

K.  Write the toString() method for your class HawaiianTheme. The return value should return a String with the three data fields, so they can be displayed.

L. See SimpleClass.java for an example of a class, constructor, toString() method, and an array of objects.

M.The next step is to make get() and set() methods, so you can change each data field as you wish. You should have three (3) get() methods – one get() method for each data field. And you should have three (3) set() methods – one set() method for each data field.

Or, you can make a single method that also updates each data field. You should have three (3) methods – one method for each data field you are updating.

N.After you make the changes to your data fields for each element, print the array of HawaiianTheme objects to the screen again.

O. See SimpleClassWithMethods.java for an example of a class, constructor, toString() method, an array of objects, get() methods, set() methods, and other update methods.

II.Make sure your code follows the ICS 211 Java Coding Standard, in particular the Java documentation (Javadoc) comments that go above each method.