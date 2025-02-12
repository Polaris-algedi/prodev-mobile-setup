# ProDev Mobile Setup

## Project Setup

### Navigate to Your Project Directory

Open your terminal and move to your parent project directory:

```sh
cd prodev-mobile-setup
```

### Set Up Your Project

Initialize a new Expo project using the latest Expo Router template:

```sh
npx create-expo-app@latest prodev-mobile-app-0x00
```

### Modify the Home Screen

1. Open `app/(tabs)/index.tsx`.
2. Locate the default text `Welcome!`.
3. Change it to `**First App Created**`.

### Run and Test Your Application

Start the Expo development server with:

```sh
npx expo start
```

- **For iOS Devices:** Scan the QR code in the terminal using your phone’s Camera app.
- **For Android Devices:** Scan the QR code using the Expo Go app.

### Reset the Application

Run the following command to reset the project:

```sh
npm run reset-project
```

### Observations After Resetting

After running the `npm run reset-project` command, the following observations were made:

- All installed dependencies were removed and reinstalled.
- The `node_modules` and `.expo` folders were cleared.
- Any cached data related to the project was deleted.
- The app needed to be restarted and reconfigured as per initial setup steps.

---
