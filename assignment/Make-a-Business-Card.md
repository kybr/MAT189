## Make a Business Card

- Create a GitHub account
  - <https://github.com>
  - Pick a good handle. I am [kybr](https://kybr.github.io) on GitHub
  - Email me your GitHub handle <yerkes@ucsb.edu>
- Create⁰ a GitHub pages site
  - <https://pages.github.com>
  - Follow those directions
- Publish¹ a 150 word bio on your GitHub pages site
  - Write in the third person about yourself as if you are awesome and mysterious
  - Use the word "praxis", "dialectic", or "phenomenological"
  - Append your socials
  - Confirm that your GitHub pages site loads in your browser
- Create a QR code that leads to your github pages site
  - Find an online QR code generator
  - Enter your GitHub pages site URL (e.g., <https://kybr.github.io>)
  - Test the QR code with your phone; How does it look?
- Take a good picture of this QR code on your phone
  - Fill the screen with the code
  - Make sure it is not blurry
  - You will show this photo to people in class
- Add² an image to your GitHub pages site
  - Any image; Not huge. Less than 1000 pixels square
  - Refresh the page on your phone
  - How does it look?
- Bring your phone to class
  - Show people in class the QR code
  - Receive feedback on your bio



⁰ Once you have created a repository using the the GitHub website, use the GitHub Desktop app to get the repository onto your computer. 

¹ Use GitHub Desktop to view the files of your repository. Navigate to`index.html` and open the file in your text editor. (On Windows, use `notepad.exe`. On macOS, use `TextEdit.app` _but do "Command-Shift-T" to put it in plaintext mode_.) Use your text editor to modify `index.html`, adding your bio text inside the P-tag: `<p>This is my bio.</p>`. Delete the H-tag (`<h1></h1>`). Once your text is complete, use GitHub Desktop to commit and push the modified file.

² Use GitHub Desktop to view the files of your repository. Put your image file into the folder next to `index.html`. Name the image file something short; Do not use spaces ( ) in the name of the file. Next, modify your `index.html` using your text editor. Add an IMG-tag within the BODY-tag: `<body>...<img src="my-image.png" style="zoom:50%;" />...</body>`. Do not add the dots (`...`).



In the end, you might have something like this:

```html
<!DOCTYPE html>
<html>
  <body>
    <p>
      This is my bio.
    </p>
    <img src="my-image.png" style="zoom:50%;" />
  </body>
</html>
```


#### Example:

**kybr.github.io**

<img src="../image/kybr.github.io.png" alt="kybr.github.io" width="400" />

