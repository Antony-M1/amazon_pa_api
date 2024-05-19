# [Amazon PA API](https://webservices.amazon.com/paapi5/documentation/)

![image](https://github.com/Antony-M1/amazon_pa_api/assets/96291963/6ab99cfb-71b4-42f9-af89-374d538c19d1)

Amazon has developed a world-class web service that millions of customers use every day. As a developer, you can build Product Advertising API applications that leverage this robust, scalable, and reliable technology. You get access to a lot of the data used by Amazon including the items for sale, customer reviews, seller reviews, as well as most of the functionality you see on Amazon.com, such as finding items, displaying customer reviews, and product promotions. Product Advertising API operations open the doors to Amazon's databases so that you can take advantage of Amazon's sophisticated e-commerce data and functionality. Build your own web store to sell Amazon items or your own items.

Best of all, Product Advertising API is free. By signing up to become a Product Advertising API developer, you join the tens of thousands of developers who are already realizing financial gains by creating Product Advertising API-driven applications and web stores.

For [PA API](https://affiliate-program.amazon.in/assoc_credentials/home)

[**Using SDK**](https://webservices.amazon.com/paapi5/documentation/quick-start/using-sdk.html#using-sdk)

[**Python**](https://webservices.amazon.com/paapi5/documentation/quick-start/using-sdk.html#python)
  
1. Download [`paapi5-python-sdk-and-samples`](https://webservices.amazon.com/paapi5/documentation/assets/archives/paapi5-python-sdk-example.zip) archive and `unzip` it.
2. Install all the dependencies locally using sudo python `setup.py` install
3. Open the project in any editor of your preference.
4. Add your `Access Key`, `Secret Key` in sample code snippet files.
5. Add valid Partner Tag for the requested marketplace in sample code snippet files.
6. Run code sample like `sample_get_items_api.py` using the command `python sample_get_items_api.py`.

# Prerequisites
* [Python3.10](https://www.python.org/downloads/)

# .env
The `.env` file is contains the all the `Secret Credential` create the `.env` file in the root folder and past this code inside the file.

*Note: These are all `dummy` data only you have to apply your orginal data*
```.env
AMAZON_PA_ACCESS_KEY=<MY_ACCESS_KEY>
AMAZON_PA_SECRET_KEY=<MY_SECRET_KEY>
```


# Local Setup
### Step 1:
Clone the project using this command

```
git clone https://github.com/Antony-M1/amazon_pa_api.git
```

### Step 2:
Create the `virtual environment`

```
python3.10 -m venv .venv
```
Activate the env for `windows` use `bash` or `git bash` terminal
```
source .venv/Scripts/activate
```
for `linux`
```
source .venv/bin/activate
```

### Step 3:
Install the Requirements
```
pip install -r requirements.txt
```
