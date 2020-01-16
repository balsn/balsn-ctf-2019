# Balsn CTF 2019

The champions will pre-qualify directly for HITCON CTF Finals in December (Onsite in Taipei, Taiwan).

- Date: 10/5 10:00 a.m. (UTC+8) ~ 10/7 10:00 a.m. (UTC+8)
- Format: Online Jeopardy
- [CTFtime link](https://ctftime.org/event/811)
- Prize (the prize will be proceeded in BTC or ETH)
  - 1st place: $25,000 TWD + pre-qualify for HITCON CTF Finals
  - 2nd place: $15,000 TWD
  - 3rd place: $10,000 TWD
  - Balsn CTF Taiwan Star (1st domestic team): $ 10,000 TWD

Results:
- 1st: [hxp](https://twitter.com/hxpctf)
- 2nd: [LC↯BC](https://ctftime.org/team/15726)
- 3rd: [PPP](https://twitter.com/PlaidCTF)
- Taiwan 1st: 新竹沒放假QAQ


# Challenges

 - [Balsn CTF 2019](#balsn-ctf-2019)
   - [Misc](#misc)
     - [SecureCheck](#securecheck)
     - [pyshv1](#pyshv1)
     - [pyshv2](#pyshv2)
     - [pyshv3](#pyshv3)
     - [JPcode](#jpcode)
     - [john](#john)
     - [Need_some_flags](#need_some_flags)
     - [Need_some_flags_2](#need_some_flags_2)
   - [Pwn](#pwn)
     - [KrazyNote](#krazynote)
     - [SimpleLanguage](#simplelanguage)
     - [SecPwn](#secpwn)
     - [PlainNote](#plainnote)
     - [securenote](#securenote)
     - [Machbook](#machbook)
   - [Web](#web)
     - [卍乂Oo韓國魚oO乂卍](#卍乂oo韓國魚oo乂卍)
     - [Warmup](#warmup)
     - [Donation](#donation)
     - [RCE Auditor](#rce-auditor)
     - [Silhouettes](#silhouettes)
     - [Images and Words](#images-and-words)
   - [Rev](#rev)
     - [Hack Compiler](#hack-compiler)
     - [vim](#vim)
     - [plam](#plam)
   - [Smart Contract](#smart-contract)
     - [simple sol aeg](#simple-sol-aeg)
     - [Bank](#bank)
     - [Creativity](#creativity)
   - [Crypto](#crypto)
     - [collision](#collision)
     - [unpredictable](#unpredictable)
     - [harc4](#harc4)
     - [shellcode writer](#shellcode-writer)
   - [Web and Golang](#web-and-golang)
     - [Gopher Party](#gopher-party)
   - [PPM](#ppm)
     - [listcomp ppm](#listcomp-ppm)


## Misc
### SecureCheck
- Points: 330
- Solved: 31
- Description:
    ```
    No system call no pain
    `nc securecheck.balsnctf.com 54321`
    ```
- Author: Billy
- Link: 

### pyshv1
- Points: 572
- Solved: 13
- Description:
    ```
    Continuous delivery is awesome.
    We deploy our code to production whenever we can.
    No code, no vulnerability.
    Everything works great.

    `nc pysh1.balsnctf.com 5421`

    Decrypt v2/v3 with flag from previous level using following command:
    `openssl enc -d -aes-256-cbc -salt -pbkdf2 -in task.tar.gz.enc -out task.tar.gz`

    Python version: python 3.6
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/misc/pyshv1/
    
### pyshv2
- Points: 857
- Solved: 5
- Description:
    ```
    Continuous delivery is awesome.
    We deploy our code to production whenever we can.
    No code, no vulnerability.
    Everything works great.

    `nc pysh2.balsnctf.com 5422`

    Decrypt v2/v3 with flag from previous level using following command:

    `openssl enc -d -aes-256-cbc -salt -pbkdf2 -in task.tar.gz.enc -out task.tar.gz`

    Python version: python 3.6
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/misc/pyshv2/

### pyshv3
- Points: 906
- Solved: 4
- Description:
    ```
    Continuous delivery is awesome.
    We deploy our code to production whenever we can.
    No code, no vulnerability.
    Everything works great.

    `nc pysh3.balsnctf.com 5423`

    Decrypt v2/v3 with flag from previous level using following command:

    `openssl enc -d -aes-256-cbc -salt -pbkdf2 -in task.tar.gz.enc -out task.tar.gz`

    Python version: python 3.6
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/misc/pyshv3/

### JPcode
- Points: 957
- Solved: 3
- Description:
    ```
    シェルコード だいすき
    I love shellcode <3
    `nc jpcode.balsnctf.com 19091`
    ```
- Author: how2hack
- Link: https://github.com/how2hack/my-ctf-challenges/tree/master/balsnctf-2019/jpcode

### john
- Points: 1000
- Solved: 1
- Description:
    ```
    
    text is unacceptable in our confidential flag checker.
    All traffics are encrypted.

    Note: Make sure you have a standard network setup. If you're not sure, try to use GCP.
    Our solution is tested on AWS (us-east) and GCP (us-central & asia-east).
    `nc john.balsnctf.com 5452`
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/misc/john/

### Need_some_flags
- Points: 1000
- Solved: 1
- Description:
    ```
    To host a CTF, we need tons of flags.
    Would you like to help us? We will take your flags after the end of CTF
    Please make sure your flags work great under Ubuntu 18.04 and python 2.7.15
    `nc flagsss.balsnctf.com 10121`
    ```
- Author: sces60107
- Link: https://github.com/sces60107/My-CTF-Challenges/tree/master/Balsn_CTF_2019/Need_some_flags/solution#need_some_flags

### Need_some_flags_2
- Points: 1000
- Solved: 1
- Description:
    ```
    Need more flags !!!!
    `nc flagsss2.balsnctf.com 10122`
    ```
- Author: sces60107
- Link: https://github.com/sces60107/My-CTF-Challenges/tree/master/Balsn_CTF_2019/Need_some_flags/solution#need_some_flags_2

## Pwn
### KrazyNote
- Points: 572
- Solved: 13
- Description:
    ```
    Hide your secret in kernal space

    user: knote, passwd:knote

    ssh knote@krazynote.balsnctf.com -p 54321
    ssh knote@krazynote-2.balsnctf.com -p 54321
    ssh knote@krazynote-3.balsnctf.com -p 54321

    Finish your exploit before you connect to Remote. And try minimize your binary. 300 seconds should be enough for you to upload your exploit to the server.
    ```
- Author: Billy
- Link:

### SimpleLanguage
- Points: 957
- Solved: 3
- Description: 
    ```
    Billy love ROP !?

    nc simplelanguage.balsnctf.com 54321
    ```
- Author: tens
- Link:

### SecPwn
- Points: 957
- Solved: 3
- Description:
    ```
    Playing classic pwn in 2019.

    nc secpwn.balsnctf.com 4597

    Linux 4.14.143-91.122.amzn1.x86_64 #1 SMP Wed Sep 11 00:43:34 UTC 2019 x86_64 x86_64 x86_64 GNU/Linux
    ```
- Author: yuawn
- Link: https://github.com/yuawn/CTF/blob/master/2019/balsn-ctf-2019/SecPwn/secpwn.py

### PlainNote
- Points: 1000
- Solved: 1
- Description:
    ```
    Write some notes in 2019

    nc plainnote.balsnctf.com 54321

    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com
    ```
- Author: Billy
- Link: https://gist.github.com/st424204/6b5c007cfa2b62ed3fd2ef30f6533e94?fbclid=IwAR3n0h1WeL21MY6cQ_C51wbXimdts53G3FklVIHw2iQSgtgGo0kR3Lt-1Ek

### securenote
- Points: 1000
- Tag: crypto-ish
- Solved: 0
- Description:
    ```
    Notes family is known to be pwned, we secure it with SOTA encryption.
    There's nothing you can control.
    nc securenote.balsnctf.com 5454
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/pwn/securenote/

### Machbook
- Points: 1000
- Solved: 1
- Description:
    ```
    Mach Apple Great Again!!!
    https://drive.google.com/open?id=1-8IauoBTbeuoCS_HN8ngxNtaXhxjsuLO
    nc machbook.balsnctf.com 19091
    ```
- Author: how2hack
- Link: https://github.com/how2hack/my-ctf-challenges/tree/master/balsnctf-2019/machbook

## Web 
### 卍乂Oo韓國魚oO乂卍
- Points: 527
- Solved: 15
- Description:
    ```
    Taiwanese people love korean fish.
    ```
- Author: Kaibro
- Link: https://github.com/w181496/My-CTF-Challenges/tree/master/Balsn-CTF-2019#%E5%8D%8D%E4%B9%82oo%E9%9F%93%E5%9C%8B%E9%AD%9Aoo%E4%B9%82%E5%8D%8D-koreanfish

### Warmup
- Points: 857
- Tag: reverse-ish
- Solved: 5
- Description:
    ```
    Baby PHP challenge again.
    ```
- Author: Kaibro
- Link: https://github.com/w181496/My-CTF-Challenges/tree/master/Balsn-CTF-2019#warmup

### Donation
- Points: 1000
- Solved: 0
- Description:
    ```
    Do you wanna support us?
    ```
- Author: Cyku
- Link: https://github.com/CykuTW/My-CTF-Challenges/tree/master/BalsnCTF-2019/Donation

### RCE Auditor
- Points: 1000
- Solved: 1
- Description:
    ```
    http://rce-auditor.balsnctf.com/
    
    Download the source code here

    Chrome has retired the XSS Auditor, but how about the RCE Auditor? The evil eval_server is listening on 127.0.0.1:6666, but RCE Auditor protects us.


    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com . 
    ```
- Author: bookgin
- Link: https://github.com/BookGin/my-ctf-challenges/tree/master/balsn-ctf-2019/rce-auditor

### Silhouettes
- Points: 1000
- Solved: 2
- Description:
    ```
    http://silhouettes.balsnctf.com/

    BGM: American Football - Silhouettes
    ```
- Author: bookgin
- Link: https://github.com/BookGin/my-ctf-challenges/tree/master/balsn-ctf-2019/silhouettes

### Images and Words
- Points: 1000
- Tag: misc, web
- Solved: 0
- Description:
    ```
    http://images-and-words.balsnctf.com/

    Download the source code here

    BGM: Dream Theater - Images and Words


    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com . 
    ```
- Author: bookgin
- Link: https://github.com/BookGin/my-ctf-challenges/tree/master/balsn-ctf-2019/images-and-words

## Rev
### Hack Compiler
- Points: 690
- Solved: 9
- Description:
    ```
    There is a password checker on a Hack machine.
    Can you solve it?

    Compiler: https://github.com/qazwsxedcrfvtg14/Hack-Assembly-Language-Compiler
    ```
- Author: qazwsxedcrfvtg14
- Link: https://github.com/qazwsxedcrfvtg14/CTF_Hack_Copiler_Write_Up

### vim
- Points: 726
- Solved: 8
- Description:
    ```
    A vim challenge written with kakoune.
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/rev/vim/

### plam
- Points: 1000
- Solved: 1
- Description:
    ```
    I tried my best, but it's still a little bit slow.
    It will tell you the result after several years.
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/rev/plam/

## Smart Contract
### simple sol aeg
- Points: 957
- Solved: 3
- Description:
    ```
    Solidity Automatic Exploit Generation?
    try it:
    nc aab2596ac4a422a9f803ed317089c399b818bb72.balsnctf.com 30731
    Be a King

        Give you a contract bytecode, give me transaction data to be a king.
        Timeout = 10 seconds per challenge.
        You can call isKing() to verify it.
        pragma solidity 0.4.25


    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com . 
    ```
- Author: ysc
- Link: https://gist.github.com/YSc21/101c4b79195f202f78a098ffd951ae59

### Bank
- Points: 1000
- Solved: 1
- Description:
    ```
    Again, as those ctfs did in the past, we also implemented our 100% secure bank system, but on blockchain this time.

    Game environment: Ropsten Testnet

    nc bank.balsnctf.com 12345

    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com
    ```
- Author: shw
- Link: https://github.com/x9453/balsn-ctf-2019

### Creativity
- Points: 1000
- Solved: 1
- Description:
    ```
    Be concise, or be creative.

    Game environment: Ropsten Testnet

    nc creativity.balsnctf.com 12345

    This challenge requires Proof-of-Work (PoW). We have already finished the code for you. Please see pow.balsnctf.com
    ```
- Author: shw
- Link: https://github.com/x9453/balsn-ctf-2019

## Crypto
### collision
- Points: 726
- Solved: 8
- Description:
    ```
    md5 is broken, sha1 is broken, but our authenticator survives.
    Note: It may takes several seconds to check the password. Please be patient.
    nc collision.balsnctf.com 5451
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/crypto/collision/

### unpredictable
- Points: 810
- Solved: 6
- Description:
    ```
    Our team, Balsn, is full of prophets. We know the future, we know the flag. How about you?
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/crypto/unpredictable/

### harc4
- Points: 857
- Solved: 5
- Description:
    ```
    Four is the only number whose name in English has the same number of letters as its value, and the name of our favorite cipher, RC4, ends with 4.
    Coincidence? I don’t think so!
    nc harc4.balsnctf.com 5450
    ```
- Author: sasdf
- Link: https://sasdf.cf/ctf/tasks/2019/BalsnCTF/crypto/harc4/

### shellcode writer
- Points: 906
- Tag: shellcode
- Solved: 4
- Description:
    ```
    Tired of AES pwn? Try some RSA pwn!!!
    Give me your encrypted message then I will write it out for you!
    nc shellcode.balsnctf.com 4001
    ```
- Author: fweasd
- Link: https://github.com/b04902036/balsnctf-2019

## Web and Golang
### Gopher Party
- Points: 857
- Tag: web
- Solved: 5
- Description:
    ```
    Welcome to gopher party! Sign up to register the event!
    (O口o)!!!(O口o)!!!(O口o)!!!(O口o)!!!(O口o)!!!(O口o)!!!(O口o)!!!

    https://gopherparty.balsnctf.com

    https://github.com/balsnctf/gopher-party

    What is the smallest scheduling unit of golang, and how it works? Maybe there's some features/tricks in it.
    ```
- Author: Xun
- Link: https://github.com/LeeXun/my-ctf-challenges#gopher-party-o%E5%8F%A3oo%E5%8F%A3oo%E5%8F%A3o


## PPM
### listcomp ppm
- Points: 371
- Solved: 26
- Description:
    ```
    Solve 3 super easy list-comp challenges!!!
    Short! Shorter!! Shortest!!!

    nc easiest.balsnctf.com 9487

    UPDATE: the challenge runs by python3.6 UPDATE: the original code should already be list comprehension

    Question1: The first line would contain a positive integer N. Then there would be N lines below. Each line contains two integer A and B. Please output the corresponding A+B.
    Example Input:
    3
    1 2
    3 4
    5 6

    Example Output:
    3
    7
    11

    Input Length Limit: 75

    Question2: This is the knapsack problem that you know. Sasdffan is going to buy some junk foods. However, he has only limited budgets M. Each junk food would have two attributes, the cost of buying the junk food and the value of eating the junk food. The first line contains two positive integers N and M. Then, there would be N lines below. Each line contains two positive integers v and c. (v: value, c: cost). Please output the maximum value that Sasdffan could get after consuming all the junk foods he bought. Caution: Each junk food could only be bought once.
    1000 <= N <= 2000, 1 <= M <= 3000, 1 <= c <= 3000, v > 0
    Example Input:
    3 5
    1 2
    1 3
    2 2

    Example Output:
    3

    Input Length Limit: 200

    Question3: Depth of the tree. There is a size N tree with node index from 0 to N-1. The first line is an integer N (tree size). Then, there would be N numbers in the next line each represents the father of the node. (0 is always the root). 10 <= N <=10000. Please notice that for any i, father[i] < i.
    Example Input:
    3
    0 0 1

    Example Output:
    2

    Input Length Limit: 300

    ```
- Author: hortune
- Link: https://github.com/hortune/listcomp-ppm 
