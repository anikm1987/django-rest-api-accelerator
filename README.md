 Django Rest Api Accelerator
 ----------------

Rest framework accelerator repository using django framework

#### Pre-requisites
| Software                         |
| ---------                        |
| Python 3.6+                      |
| virtualenv                       |
| git ( and access to github)      |
| Terraform >=0.12 - Refer - [Terraform Install](https://learn.hashicorp.com/tutorials/terraform/install-cli)                  |


Quick Start
----------
You can create your own repository by selecting this repository as template repository. Made neccessary changes according to your project name for below comand


1. Clone the repo
  ```
  $ git clone https://github.com/anikm1987/django-rest-api-accelerator.git
  $ cd django-rest-api-accelerator
  ```

2. Initialize and activate a virtualenv:
  ```
  python -m venv env
  # For windows
  env\scripts\activate
  # For linux
  source env/bin/activate
  ```

3. Install the dependencies:
  ```
  $ pip install -r requirements.txt
  ```

4. Run the development server:
```
python manage.py runserver 0.0.0.0:8000
```
Navigate to [http://localhost:8000](http://localhost:8000)