# MiniMarshal

A versatile tagging and categorization system, in a single PHP file.

For a live example, see http://keyboardfire.com/pages/. An example you can use on your own website is provided in the test.php file.

Usage instructions:

1. Upload minimarshal.php and test.php to a location of your choice.
2. Create a minimarshaldefs.php file in accordance to the example file provided, and upload that to the same directory. (You will also need to create a mySQL database in order to provide the correct definitions.)
3. Run the setup() PHP function somehow (if you go to test.php?admin, there's a "setup" tool at the bottom that will do this for you).
4. Access MiniMarshal at `path/to/directory/test.php` (you can rename it to a name of your choice), and append `?admin` to the URL to access the admin page (you will need to update the password hash; TODO: make this easier than going into the test.php code itself).
