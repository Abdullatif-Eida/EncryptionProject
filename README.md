# EncryptionProject
An Encryption using Steganography

Encryption flowchart:
![image](https://user-images.githubusercontent.com/35701617/153746446-79c1a106-2cc3-4174-841b-546641e5e02d.png)

Decryption flowchart:
![image](https://user-images.githubusercontent.com/35701617/153746452-0b222842-6c79-42d9-8101-fe5ee6fcf59e.png)

Program execution (Encryption process):

  ![image](https://user-images.githubusercontent.com/35701617/153746464-9ed16c21-50e2-4df2-b6df-7d735a307b3a.png)

  The first stage is the implementation of the program which is the coding process. As shown above, this is the main program interface that contains two buttons, the first button       responsible for the encryption process and hiding the text in the image, the second button responsible for the decoding process and showing the encrypted text. 

  ![image](https://user-images.githubusercontent.com/35701617/153746468-0e31c152-7875-4697-a5d4-d1a12b84171e.png)

  Now after pressing the encoder button, the first square appears, and through it we can choose the appropriate image to hide the text inside, and it must be in BMP extension as       shown above

  ![image](https://user-images.githubusercontent.com/35701617/153746471-f8a8798f-6a1a-4961-94d4-ee19c224a6ae.png)

  The third step is to choose where to save the selected image after the process of hiding the text inside it. We choose a file to save the image and called it the output file as shown above.

  ![image](https://user-images.githubusercontent.com/35701617/153746495-8eea52b6-418d-4a79-8026-0d82ada03f6f.png)

  The final step is to choose the text to be encoded and hide it in the image as shown above.

  ![image](https://user-images.githubusercontent.com/35701617/153746502-bd4a90b1-79aa-434d-b929-4361cfc0642e.png)

  As shown above, the encryption process was successful and the encrypted text is 51 characters long.

Program execution (Decryption process)

![image](https://user-images.githubusercontent.com/35701617/153746523-b31f09f6-c2d8-4673-adc8-b9b3dc173c40.png)

The decryption process also depends on several steps. The first step is to choose the image containing the encoded text that was placed in the output file during the encryption process as shown above.

![image](https://user-images.githubusercontent.com/35701617/153746565-ed439a34-62cb-4e9f-9295-a2cddc166220.png)

The last step is to choose where to save the text document after decoding it from the image as shown above.

![image](https://user-images.githubusercontent.com/35701617/153746574-27375fcb-2250-49aa-9370-ec5de5353821.png)

As shown above, the decryption process was successful done and the 51-character text has been decoded.

Also if we want to see the image in which we placed the decoded text, it is possible to notice that the image is still the same and has not changed even though it contains the encrypted message and the image has not changed because we put the encoded text in the first pixel field of the image from the RGB layers and Alpha, as shown below

![image](https://user-images.githubusercontent.com/35701617/153746592-41f1d078-cc3c-4e0c-8599-12b1632dbce7.png)

Figure: Encrypted image

My algorithm 
![image](https://user-images.githubusercontent.com/35701617/153746623-a5650aa7-3655-43db-a99f-a8e90ee11075.png)

If it is possible to say that the while condition will be repeated 8 times, but it will be called according to the size of the message, which is n, then this means that the complexity of the algorithm is O(n). So, the worst-case scenario for this algorithm is O (8 * n) = O(n) which is somewhat good
Now by looking at that result in the statistical chart above, we find that this algorithm is somewhat bad.


