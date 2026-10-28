- **Forced PIN changes no longer block unlocking.** When a FIDO key
  requires a PIN change, the app opens the change-PIN form instead of failing
  with a PIN policy error. After the change, the key can be unlocked with the
  new PIN. ([#220])
