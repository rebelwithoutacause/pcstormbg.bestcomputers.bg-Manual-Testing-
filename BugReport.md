# pcstormbg.bestcomputers.bg-Manual-Testing-

[BugReport.docx](https://github.com/user-attachments/files/20210088/BugReport.docx)

Bug Title: Incorrect Currency Conversion – Price in EUR Doesn’t Match BGN Value
Environment:
•	Website: [https://pcstormbg.bestcomputers.bg/]
•	Device: [PC]
•	Browser: [Brave]
•	OS: [Windows 10]
Steps to Reproduce:
1.	Navigate to the product/service page.
2.	Click on the option to change the currency from BGN to EUR.
3.	Observe the displayed price.
Expected Result:
Price in EUR should reflect the correct conversion rate from 1400 BGN (e.g., ~715 EUR at current rates).
Actual Result:
Price in EUR is shown as nearly 3,000 EUR, which is over 4x higher than the correct value.
Impact:
•	Severity: High
•	Misleads customers and distorts actual product value
•	Potential loss of trust or business
•	Possible revenue loss or legal implications
•	May indicate a backend logic flaw or intentional misconfiguration
  Screenshots:
 
![PriceInBGN](https://github.com/user-attachments/assets/50b1caf8-6812-4616-8564-7b600800e336)

![PriceInEUR](https://github.com/user-attachments/assets/f050e5aa-79be-4e61-85b0-b4fe93e73707)


