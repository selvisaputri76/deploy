## Install Truffle
- [Step 2](https://trufflesuite.zendesk.com/hc/en-us/articles/8150057408923-install-Truffle-on-Windows-10-11)


1) ❗️❗️❗️ Run PowerShell as Administrator
![image](https://user-images.githubusercontent.com/30211801/223653639-c4d3cfa7-cde7-4d61-8de5-2c8c72f6abb6.png)
2) Check
```
node -v
npm -v
```
3) Install Truffle
```
npm install -g truffle
```
4) Check truffle
```
truffle
```
5) If you have an Error
![image](https://user-images.githubusercontent.com/30211801/223654850-54579d23-73e6-4922-bd73-6ba041bd030c.png)
Type commands one by one:
```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
Set-ExecutionPolicy -Scope LocalMachine -ExecutionPolicy Bypass
```
Now our directory is 
```
C:\Program Files (x86)\Microsoft Visual Studio\2019\BuildTools
```
![image](https://user-images.githubusercontent.com/30211801/223704351-ce7818f9-1c62-45cb-9a7b-b7c1d07f121d.png)
6) Again reopen PowerShell as Administrator. And check:
```
truffle
```
![image](https://user-images.githubusercontent.com/30211801/223655750-4c8ba93c-b392-4a12-8c23-a34ae49fc931.png)

🎉🎉🎉 Great job!
