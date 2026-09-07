# davem0rg Umbrel apps

Personal [Umbrel](https://umbrel.com) Community App Store.

## Add this store

On your Umbrel:

1. Open **App Store**
2. Tap the **⋯** menu → **Community App Stores**
3. Paste:

```
https://github.com/davem0rg/umbrel-apps
```

4. Install **Seat Beacon**

The app image is `ghcr.io/davem0rg/seat-beacon`. After the first GitHub Actions build, set that package to **Public** under GitHub → Packages so Umbrel can pull it.

## After install

1. Open Seat Beacon
2. Connect Pushover (User Key + API Token, send a test)
3. Watch a flight (try AS 292)

The box checks the seat map every two minutes and pushes to your iPhone. Keep the Umbrel running.
