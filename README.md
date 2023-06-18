# Email-Slicer
Email Slicer is a Python project that involves breaking down an email address into its username and domain name components. It takes a user's email address as input and returns the username and domain name separately.

Here's a step-by-step description of how the Email Slicer project works:

The user is prompted to enter their email address.
The input email address is stored in a variable.
The program searches for the "@" symbol in the email address using the find() method.
If the "@" symbol is found, it means the email address is valid. The program proceeds to the next step. If the "@" symbol is not found, an error message is displayed.
The program uses string slicing to split the email address into two parts: the username and the domain name. The username is everything before the "@" symbol, and the domain name is everything after the "@" symbol.
The username and domain name are stored in separate variables.
The program outputs the username and domain name separately.

Here's an example to illustrate the functionality of the Email Slicer project:

Output:
Enter your email address: john.doe@example.com

Username: john.doe
Domain: example.com
In this example, the input email address is "john.doe@example.com". The program extracts the username "john.doe" and the domain name "example.com" using string slicing, and then displays them as separate outputs.

The Email Slicer project can be useful in various scenarios, such as when you need to extract specific parts of an email address for further processing or validation.
