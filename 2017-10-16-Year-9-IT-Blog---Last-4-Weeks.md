---
title: Year 9 IT Blog - Last 4 Weeks
layout: post
author: aidan.collins
permalink: /year-9-it-blog---last-4-weeks/
source-id: 1zU-DR09ILUhF8-Q17SXBioVTjTWYXcXp5CNLB0J0Ggk
published: true
---
**The Start Of Year 9 IT****                                                                **   9/10/17

In the last four weeks we have used Google Sheets to learn some basic encryption skills.

I started by writing all the alphabet out, letter by letter, in the next column along I wrote every letters' equivalent in the encryption. The alphabet was changed by one letter being +4 letters in the alphabet and the next letter being -4 e.g: A = E and B = X.

We then learnt how to reference this encrypted alphabet in order to encrypt a certain word. The word I wanted to encrypt was apple. I used the function "=vlookup" which finds the list of letters and encrypts the letter in the new word. The =vlookup” function is a really cool and useful function which would come in really handy if you needed to encrypt a long message. The exact code to encrypt the first letter of apple (“a”) is: 

=VLOOKUP(D1,A1:B26,2)

This encryption technique is useful if you need to send a top-secret message to somebody and don't want anybody to intercept the message and know the secret information.

After encrypting, we learnt how to decrypt the encrypted code back to the original. 

We had to write the two alphabets out again, but reversed, so the encrypted letters were in the first column, with their equivalents in the original alphabet in the second column. The encrypted code = "ejjhi" and I needed to find a way to decrypt that word back to “apple” the “=vlookup” function came in useful again: =VLOOKUP(D4,$A$28:$B$53,2, FALSE)

The "vlookup" function did the same thing but just with the second lot of alphabets in order to find the encrypted letter and give out the normal alphabet letter. You would need to use this decryption technique if somebody gave you a long encrypted message and you needed to find the original.

We then used a table to break up the message given, in a longer mesage this would be necessary to break up the words and make 

<table>
  <tr>
    <td>Program</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Left</td>
    <td></td>
    <td>e</td>
    <td>ej</td>
    <td>ejj</td>
    <td>ejjh</td>
    <td>ejjhi</td>
  </tr>
  <tr>
    <td>Factor</td>
    <td></td>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
  </tr>
  <tr>
    <td>Switch I/0</td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
</table>


