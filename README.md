# Challenge_2
Repo for Challenge 2

GENERAL INFO -
This is an update to a loan qualification application that matches users to appropriate loans based off four (4) main criteria; maximum loan size available, user credit score, user debit to income ratio, and user loan to value ratio. Within this update there is an added user save functionality that allows users, when prompted, to save a list of loans they have qualified for as a CSV for ease of user consuption



The codebase for the app is located in the master branch of this repo & is labeled app.py, it is located within a folder labeled 'loan_qualifier_app'. You will find accompanying modules of data & calculations that I will define below that are key to utilizing the apps functionality. These folders are labeled 'data' & 'qualifier'; within these folders you will find filter functions, calcualtions, & a bank data CSV. These all will be imported & documentation is available below. 



TECH REQUIREMENTS -
For this application you will require an understanding of python & a working understanding of using Fire & Questionary. This code was writen using MacOS in Jupyterlabs using a Python 3 kernel & will not function on py 2.7.. 






INSTALATION -
- To start, a CSV of lender criteria for loans is imported as well as Fire & Questionary.


<img width="577" alt="Screen Shot 2022-04-03 at 7 31 29 PM" src="https://user-images.githubusercontent.com/98225311/161453625-a608ae82-bf93-47de-9b0d-4ab26cef7d4e.png">


USAGE -
- Then users are prompted to supply their maximum loan application amount, credit score, debt, income, & home value. 

<img width="699" alt="Screen Shot 2022-04-03 at 5 26 33 PM" src="https://user-images.githubusercontent.com/98225311/161449353-5f5536bd-04ad-4af5-abad-08e266beccd9.png">


- The app requires two (2) mathmatical calculations: finding the users debt to income ratio & user loan to value ratio. The calculations can be found within the 'calculator' module in the codebase & is writen as such:

<img width="669" alt="Screen Shot 2022-04-03 at 5 28 06 PM" src="https://user-images.githubusercontent.com/98225311/161449383-5c554c51-459a-4c1e-81c1-16c2ab9d667b.png">

(https://github.com/tsear/Challenge_2/files/8405788/terminal_history.txt)

- These calculations are then paired with user credit score & their maximum loan availability & are passed through filters (I will only provide one example for brevity sake & since they are derivative of one another) & are writen as such:
  
 <img width="575" alt="Screen Shot 2022-04-03 at 5 29 10 PM" src="https://user-images.githubusercontent.com/98225311/161449415-6d2d10b9-fdf8-4a64-b547-fbc07d14fa81.png">

    
- Once user data has been filtered the app matches the parameters of the lender & returns a list of available loans.

Previously, this is where the app had conlcuded. With recent updates there is no an updated user CLI & a new function that allows users to save their availale loans as a custom CSV.

- The new save_CSV function is writen as such:

<img width="509" alt="Screen Shot 2022-04-03 at 5 30 06 PM" src="https://user-images.githubusercontent.com/98225311/161449440-cfb52dce-eb6c-4126-be56-cc5808049973.png">

& the new save_qualifying_loans function as such:

'

CONTRIBUTORS -
Tyler Sear = WAGMI

TERMINAL HISTORY -
[terminal_history.txt](https://github.com/tsear/Challenge_2/files/8405789/terminal_history.txt) (Starts at 800)


LICENSE - 


