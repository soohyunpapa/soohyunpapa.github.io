---
title: "[Error] Gitbush - LF will be replaced by CRLF in ..."
categories:
  - Error
tags:
  - gitbash
  - error
---

π<br>
**OS** : Windows 10<br>
**Tool** : Git Bash
{: .notice--primary}

<br>

![waring](https://user-images.githubusercontent.com/45550607/102007684-81e69000-3d6e-11eb-9135-e4928aa4ff3f.PNG)

<br>
warning: LF will be replaced by CRLF in {file name}.<br>
The file will have its original line endings in your working directory.<br>
<br>
Github μλ‘λλ₯Ό μν΄μ, addλ₯Ό νλ μ€ λ°κ²¬ν μ€λ₯μλλ€.<br>
μμ£Ό λ±μ₯νλ κ±΄ μλλ° λ³Έ μ΄νμ νμΌ λ±λ‘λ μλμ ν΄κ²°νκ³ μ ν©λλ€.<br>
<br>

| LF (Line Feed) | CR (Carriage Return) | CRLF(CR + LF) |
| :------------: | :------------------: | :-----------: |
|       \n       |          \r          |     \r\n      |
| Mac λ²μ  9κΉμ§ |         Unix         |    windows    |

<br>

[μμ€λ¬Έμ WIKI](https://ko.wikipedia.org/wiki/%EC%83%88%EC%A4%84_%EB%AC%B8%EC%9E%90)λ₯Ό μ°Έκ³ ν΄μ ν΅μ¬κ΅¬μ λ§ μ λ¦¬ν΄λ³΄μμ΅λλ€.<br>
μ¦ μ€μ λμ κ΅¬λ³νλ κ²μ΄ OSλ§λ€ λ¬λΌμ githubμ μ¬λ¦¬λ νμμ μ‘°μ ν΄μ£Όμ΄μΌ νλ κ²μλλ€.<br>
<br>
```
git config --global core.autocrlf true
```
<br>
λ₯Ό ν΅ν΄μ μ½κ² ν΄κ²°νμμ΅λλ€.<br>
λ§€λ² λ°μνλκ±΄ μλμ§λ§, κ°κ°ν νμΈλλ μ΄λ κ² ν΄κ²°νμλ©΄ λκ² μ΅λλ€!<br>
