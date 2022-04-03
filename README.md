# Challenge_2
Repo for Challenge 2


This is an update to a loan qualification application that matches users to appropriate loans based off four (4) main criteria; maximum loan size available, user credit score, user debit to income ratio, and user loan to value ratio. Within this update there is an added user save functionality that allows users, when prompted, to save a list of loans they have qualified for as a CSV for ease of user consuption

For this application you will require an understanding of python & a working understanding of using Fire & Questionary. This code was writen using MacOS in Jupyterlabs using a Python 3 kernel & will not function on py 2.7.. 

- To start, a CSV of lender criteria for loans is imported as well as Fire & Questionary.

- Then users are prompted to supply their maximum loan application amount, credit score, debt, income, & home value. 

<img width="699" alt="Screen Shot 2022-04-03 at 5 26 33 PM" src="https://user-images.githubusercontent.com/98225311/161449353-5f5536bd-04ad-4af5-abad-08e266beccd9.png">


- The app requires two (2) mathmatical calculations: finding the users debt to income ratio & user loan to value ratio. The calculations can be found within the 'calculator' module in the codebase & is writen as such:

<img width="669" alt="Screen Shot 2022-04-03 at 5 28 06 PM" src="https://user-images.githubusercontent.com/98225311/161449383-5c554c51-459a-4c1e-81c1-16c2ab9d667b.png">

  
- These calculations are then paired with user credit score & their maximum loan availability & are passed through filters (I will only provide one example for brevity sake & since they are derivative of one another) & are writen as such:
  
 <img width="575" alt="Screen Shot 2022-04-03 at 5 29 10 PM" src="https://user-images.githubusercontent.com/98225311/161449415-6d2d10b9-fdf8-4a64-b547-fbc07d14fa81.png">

    
- Once user data has been filtered the app matches the parameters of the lender & returns a list of available loans.

Previously, this is where the app had conlcuded. With recent updates there is no an updated user CLI & a new function that allows users to save their availale loans as a custom CSV.

- The new save_CSV function is writen as such:

<img width="509" alt="Screen Shot 2022-04-03 at 5 30 06 PM" src="https://user-images.githubusercontent.com/98225311/161449440-cfb52dce-eb6c-4126-be56-cc5808049973.png">

& the new save_qualifying_loans function as such:

'
