# URL_Shortener

URL Shortener using Python With GUI

The provided code is a basic implementation of a URL shortener GUI using the tkinter library in Python. It allows users to enter a URL, shorten it using pyshorteners library, display the shortened URL, and provides options to open the shortened URL in a web browser or copy it to the clipboard.

Here's a breakdown of the code:

1. The necessary libraries are imported: tkinter for GUI, pyshorteners for URL shortening, webbrowser for opening URLs, tkinter.messagebox for displaying messages, and pyperclip for copying to the clipboard.

2. The `shorten_url` function is defined, which retrieves the URL from the entry field, shortens it using pyshorteners, displays the shortened URL in the GUI, and shows a success message using `mbox.showinfo` if the shortening process is successful.

3. The `open_shortened_url` function is defined, which retrieves the shortened URL from the label and opens it in the default web browser using `webbrowser.open`.

4. The `copy_shortened_url` function is defined, which retrieves the shortened URL from the label, copies it to the clipboard using `pyperclip.copy`, and shows a success message if the copying process is successful.

5. The main GUI window is created using `tk.Tk()`, and its title, dimensions, and background color are set.

6. The URL input label and entry field are created using `tk.Label` and `tk.Entry` respectively.

7. The "Shorten URL" button is created using `tk.Button`, which triggers the `shorten_url` function when clicked.

8. An image label is created using `tk.PhotoImage` and `tk.Label` to display an image.

9. The label to display the shortened URL is created using `tk.Label`.

10. The "Open Shortened URL" button is created, which triggers the `open_shortened_url` function when clicked.

11. The "Copy Shortened URL" button is created, which triggers the `copy_shortened_url` function when clicked.

12. Finally, the GUI main loop is started using `window.mainloop()`.

To run this code, you need to have the necessary libraries installed (tkinter, pyshorteners, pyperclip) and provide a suitable image file (named "1.png" in the same directory as the Python script).
