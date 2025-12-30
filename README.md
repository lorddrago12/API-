# 🔐 API
This is a simple API for GET and POST requests using python and flask.

---
# 🧰 Technologies Used

🐍 `Python`

🌶️ `Flask` — lightweight web framework for building APIs

---
# 📌 What This API Does

* Accepts a user ID from the URL.

* Optionally accepts extra data through query parameters.

* Returns a JSON object containing user information.

* It’s designed for learning purposes and focuses on API basics, not database integration.

---
# ▶️ HOW TO RUN THIS PROJECT

Install Flask 

```pip install flask```

Run the project

```python main.py```

*** This is only for running the GET requests *** 

For the Post requests you have to

* Download Postman from https://www.postman.com/.
* Run the project and copy the address.
* create a new request on postman and paste the address there and add create-user behind the address or it wont work(it depends on what you have named your post request).
* change the method to POST
* Click Body, set it to raw and JSON.

Put this in the Body

```
{
      "username": "Tim"
}
```

---
