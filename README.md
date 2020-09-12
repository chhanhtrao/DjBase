#### Installation

  ```sh
    - Clone the source code.
    $ cd FP_ONE
    - Copy .env.example and paste as .env
    - Update environment variable in .env
    $ pip install -r requirements/base.txt
    $ python manage.py migrate
    $ python manage.py createsuperuser
    $ python manage.py runserver 0.0.0.0:8000
  ```

#### APIs

- Oauth API [doc/oauth_api.md](https://github.com/chhanhtrao/DjBase/blob/master/doc/oauth_api.md) 
- User APIs
    + [Signup](https://github.com/chhanhtrao/DjBase/blob/master/doc/user_api.md#signup)
    + [Current Profile](https://github.com/chhanhtrao/DjBase/blob/master/doc/user_api.md#current-profile)
    + [Profile](https://github.com/chhanhtrao/DjBase/blob/master/doc/user_api.md#profile)
    + [Profile List](https://github.com/chhanhtrao/DjBase/blob/master/doc/user_api.md#profile-list)

