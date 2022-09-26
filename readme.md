# Script for route creation and uploading (OMS)

## Installation:

### Clone the repo
> git clone git@github.com:agustin-caro/create-route.git
> cd create-route
> 
### Install dependencies
> pip3 install openpyxl

## Usage
Run in terminal:
>python3 create_route.py {pack_id1} {pack_id2} ...
>
e.g python3 create_route.py 7821 5813

It will create (or overwrite) routes.xlsx . You can now upload this file to OMS
