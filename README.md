#DungeonCrawl

##Setup

1. Create app using Expo
   `npx create-expo-app --(Name of your app)`
2. initialize git repository, and upload to origin
   `git init`
   `git remote git remote add origin git@github.com:CardinalNavigation/DungeonWalk.git`
3. run `npx expo` to initialze the development server (`npx expo --help` for help)
   4. select i for ios development
4. Added Splash screen with JSON. (remember the comma at the end)
   "expo": {
   "splash": {
   "image": "./assets/splash.png"
   }
   },
5. Added safe area provider to limit screen size appropriately
`

2/27/23 -Stopped here to open up react project to explore that again.