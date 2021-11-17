# How-to

1. Create a github secret called FIREBASE_TOKEN with your [firebase token](https://firebase.google.com/docs/cli#cli-ci-system)
2. Replace `your-project-id` with your firebase project id in following files:
  - [.firebaserc](/.firebaserc)
  - [deploy.yml](/.github/workflows/deploy.ym)
2. Put site in `./public` and commit to github