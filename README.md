# fast_app_base

A new Flutter project.

## Getting Started

In the ports view (the PORTS tab), port 3000 should be listed there already. Right click on it, and, under "Port Visibility", select "Public". This is important so the app can access services on your client from other server ports without getting blocked due to CORS.

```bush
flutter run -d web-server --web-hostname 0.0.0.0 --web-port 3000
```
### Go to http://<hi1>0.0.0.0:3000<hi2>
Please wait a few minutes.
### When you return to the terminal, you will see the following message in the terminal:
```bush
🔥  To hot restart changes while running, press "r" or "R".
For a more detailed help message, press "h". To quit, press "q".
```