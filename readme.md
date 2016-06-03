# Installation

Clone the repository, add your [Pusher.com](https://pusher.com) credentials in `.env` and `resources/views/home.blade.php`, check the Settings (Cluster/Server etc.) in `config/broadcasting.php` and start the Server from the command Line with `php artisan serve`.

Visit [http://localhost:8000](http://localhost:8000) in one tab, open another one and hit the url [http://localhost:8000/pusher](http://localhost:8000/pusher).
You should see a message being added to the list on your first tab via Websockets! 

## Misc

For questions, just tweet me via [@remoblaser](https://twitter.com/remoblaser) and i will get back to you.