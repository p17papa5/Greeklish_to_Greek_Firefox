# Greeklish_to_Greek_Firefox
Extension for Mozila Firefox conversion Greeklish text to Greek

# Πως μπορούμε να αλλάξουμε την γλώσσα του extension.

Για να αντικαθιστούμε όλα τα γράμματα των ελληνικών σε μια άλλη γλώσσα πρέπει να ανοίξουμε το αρχείο script.js και να αντικαταστήσουμε όπου γράφει 
new_text = new_text.replace(/:I/g, "Ϊ"); τα γράμματα που θέλουμε (το γράμμα που αντικαθιστούμε είναι μέσα στα "x" , το γράμμα ανάμεσα στα /x/ προσδιορίζει το 
αγγλικό πληκτρολόγιο). 

# How can we change the language of the extension.

To replace all the Greek letters in another language we have to open the script.js file and replace where it says new_text = new_text.replace (/: I / g, "Ϊ"); the
letters we want (the letter we replace is inside the "x", the letter between / x / identifies the English keyboard).
