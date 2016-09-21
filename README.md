# droidCrypter
droidCrypter is a Java API crypter by which you can crypt and decrypt text without any key.

How to Use:
>->Add droidCrypt.jar to your project Build Path

>->Create a Reference of IdroidCrypt interface with Crypter.getInstance() which provide Object for IdroidCrypt

        EX- IdroidCrypt idc = Crypter.getInstance();
        
>->Two methods idc reference is provide us i.e public String cipher(String text) which encrypt the text and public String decipher(String encText) which decrypt the encrypted text.

        EX- String encText = idc.cipher("Hello this text is going to be encrypter");
             encText storing encType text 
             String normalText = idc.decipher(encText);
             normalText storing decrypted text
             
             
USES:


-> Transfer important information between two medium

-> Storing Confidential data in Database in encrypted form

-> Encryption of text in file

Implementation:
I am not disclosing implementation at this point ;) just enjoy and say Thanks 
       
