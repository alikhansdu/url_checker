#  Concurrent URL Status Checker & Report Generator

A simple Go tool for checking a list of URLs using concurrent requests. The program sends GET requests to each URL, measures the response time, and saves the report in CSV format.

---

#  How to run it

1. Clone the repository:
```bash 
git clone (https://github.com/alikhansdu/url_checker.git)
cd url-checker
```
2. Create a file with a list of URLs (`urls.txt`):
 Each line in the file will contain one URL
3. Run the program:
```bash
go run main.go checker.go -f urls.txt -c 5
```

5. Expected output:
![image](https://github.com/user-attachments/assets/d1a84f85-469a-4e38-9353-836346827654)
![image](https://github.com/user-attachments/assets/8929286f-dff2-42b6-888d-3d523bc024fc)



# Requirements
Go installed
