# Room_temp

Flask app for REST API with SQL it will measure the temprature of each room and filters like data and room id.


## Run Locally

Clone the project

```bash
  git clone https://github.com/MSShoeb16/Room_temp.git
```

Go to the project directory

```bash
  cd my-project
```
Create a `.env` file with a `DATABASE_URL` variable that points to a PostgreSQL database. Look at 
`.env.example` for information on how this should be written.

Create a Python virtual environment:

```bash
  python3.11.5 -m venv .venv
```

Activate the virtual environment and install the dependencies using `pip`:

```bash
  .venv/Script/activate
pip install -r requirements.txt
```
Run the app:

```bash
  flask run
```
