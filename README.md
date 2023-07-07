## Social Networking Website 
## Frontend
#### To install dependency

```
npm install
```

#### To start the server

```
npm start
```

#### For Production Build

```
npm run build
```

- I have used proxy `http://127.0.0.1` for axios in package.json
- You can set axios.defaults.baseURL = `https://api.example.com` Globally

## Backend

#### Installing

open terminal and type

```
git clone https://github.com/Aklilu-Mandefro/social-network-for-developers-in-django-and-react.git
```

or you can download using the url below

```
https://github.com/Aklilu-Mandefro/social-network-for-developers-in-django-and-react.git
```

#### Requirements

To install requirements type

```
pip install -r requirements.txt
```

`To use Github api put your credentials in settings.py`

```
GIT_CLIENT_ID = 'your github client id'
GIT_CLIENT_SECRET = 'your github client secret'
```

To migrate the database open terminal in project directory and type

```
python manage.py makemigrations
python manage.py migrate
```

To run the program in local server use the following command

```
python manage.py runserver
```

## Preview of The Project

<img src="https://i.imgur.com/wlFYtXD.png" alt="Developers' social network"/>

<img src="https://i.imgur.com/1IWXvry.png" alt="Developers' social network"/>

<img src="https://i.imgur.com/qqOSKpQ.png" alt="Developers' social network"/>
