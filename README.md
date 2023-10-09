# onlineshop
The Onlineshop is a virtual store on the Internet where customers can browse the catalog and
select products of interest. The selected items may be collected in a shopping cart. At checkout
time, the items in the shopping cart will be presented as an order. 
At that time, more information will be needed to complete the transaction.

## Running the Project Locally
First, clone the repository to your local machine:
```
git clone https://github.com/eddoganga/onlineshop.git
```
Install the requirements:
```
pip install -r requirements.txt --user
```
Create the database:
```
python manage.py migrate
```
Finally, run the development server:
```
python manage.py runserver
```
The project will be available at 127.0.0.1:8000.
