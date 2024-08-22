# Cracking-a-password-with-a-lookup-table

## Objective

 Utilizing an NTLM Hash and a look up table to crack a password. Look up tables store pre-defined passwords and hashes and are much more faster and efficient than using a brute force attack. 


### Skills Learned

- Understanding in how simple dictionary passwords can be cracked easily using a lookup table. 
- Ability to generate hashes and crack them by using a lookup table. 

### Tools Used

- NTLM Hash Generator from Code Beautify
- Crackstation.net


## Steps
1. Google and serach for **NTLM Hash Generator**. Select the NTLM Hash Generator from **Code Beautify**.
2. Enter the text **P@ssw0rd** and click <b>Generate</b>. 
3. Output text will be the resulting hash. Copy the hash.
4. Google **Crackstation** and select **Crackstation.net**. This is massive pre-computed lookup table to crack password hashes. Only works for unsalted hashes.
5. Paste the hash. Verify you are not a robot and click on the <b>Crack Hashes</b> button.
6. The program found the password right away and also knows the type of hash.
7. Let's try another hash. Navigate back to Cody Beautify NTLM Hash Generator and input **P@ssw0rd1234**.
8. Repeat steps 3, 4, and 5.
9. The program has easily cracked this hash as well. 
