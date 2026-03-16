# Maui Android Show Photo

This repository contains a .NET MAUI Android app that immediately opens to a full-screen image.

## What it does

- Launches directly into a page that displays a membership card image.
- Uses a bundled app image (`membership_card.svg`) so the card appears as soon as the app opens.
- You can replace the placeholder image with your own photo.

## Replace with your real membership card

1. Open `MauiMembershipCardViewer/Resources/Images/`.
2. Replace `membership_card.svg` with your card photo (you can keep the same filename, or update `MainPage.xaml` to match).
3. Build and deploy the Android app.

## Build (on a machine with .NET SDK + MAUI workload installed)

```bash
dotnet workload install maui
cd MauiMembershipCardViewer
dotnet build -f net8.0-android
```
