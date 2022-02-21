# shopping-2022-inclass


## Usage


```sh
python shopping_cart.py
```

## Setup

Create a virtual environment:

```sh
conda create -n rps-env python=3.8
```

Activate the virtual environment:

```sh
conda activate rps-env
```

Install package dependencies (mainly for testing):

```sh
pip install -r requirements.txt
```

## Usage

Run the shopping cart script:

```sh
python shopping_cart.py
```

## Testing

Run tests:

```sh
pytest
```
## Instructions
Enter as many desired products using their product id's. Should a user entry not conform to the the accepted product id's, the program will make the user aware and gracefully terminate. Finish product entry using the keyword "DONE". At this point, a receipt showing a summary of product details, subtotal, tax and total cost will be displayed.