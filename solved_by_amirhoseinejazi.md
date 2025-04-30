### Solved by AmirhoseinEjazi 4002164031🔓

## Decrypted Message

TABRIK MIGAM, EY CODEBREAKER BOZORG! TO MOAMAYE MA RA HAL KARDI VA PAYAM-E MAKHFI RA RAMZGOSHAEE KARDI! HALA BE PISH BORO VA CODE-E KHODET RA DAR REPOSITORY-E MAKHFI ERSAL KON! SAFAR-E TO TAZE SHORU SHODE! LOTFAN CODE-E KHOD RA BE SORAT-E PULL REQUEST DAR **HTTPS://GITHUB.COM/CE-SHAHED/SARENAKH-MATRIS** ERSAL KONID VA BE COMMUNITY-E CODEBREAKERHA BEPEYVANDID.VA FARAMOSH NAKONID KE NAM-E KHOD VA CODE-I DANESHJOOEI RA DAR CODE-I KE ERSAL MIKONID GHARAR DAHID.

##  My Decryption Script

```python
def decrypt_ascii_shift_cipher(ciphertext):
    
    printable_chars = [chr(i) for i in range(32, 127)]
    
    for shift in range(1, 127):
        decrypted_text=""
        for ch in ciphertext:
            if ch in printable_chars:
                new = chr((ord(ch) - shift - 32) % 95 + 32)
                decrypted_text+= new
            else:
                decrypted_text+= ch
        print(f"Shift {shift}: {decrypted_text}")
        print('#'*50)

text = "]JK[RT)VRPJV5)Nb)LXMNK[NJTN[)KXcX[P*)]X)VXJVJbN)VJ)[J)QJU)TJ[MR)_J)YJbJV6N)VJTQOR)[J)[JVcPX\\QJNN)TJ[MR*)QJUJ)KN)YR\\Q)KX[X)_J)LXMN6N)TQXMN])[J)MJ[)[NYX\\R]X[b6N)VJTQOR)N[\\JU)TXW*)\\JOJ[6N)]X)]JcN)\\QX[^)\\QXMN*)UX]OJW)LXMN6N)TQXM)[J)KN)\\X[J]6N)Y^UU)[NZ^N\\])MJ[)33Q]]Y\\C88PR]Q^K7LXV8LN6\\QJQNM8\\J[NWJTQ6VJ][R\\33)N[\\JU)TXWRM)_J)KN)LXVV^WR]b6N)LXMNK[NJTN[QJ)KNYNb_JWMRM7_J)OJ[JVX\\Q)WJTXWRM)TN)WJV6N)TQXM)_J)LXMN6R)MJWN\\QSXXNR)[J)MJ[)LXMN6R)TN)N[\\JU)VRTXWRM)PQJ[J[)MJQRM7"

decrypt_ascii_shift_cipher(text)

## dar shift 104 be payam miresim 😎