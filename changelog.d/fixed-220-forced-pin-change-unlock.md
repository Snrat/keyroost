- **Forced PIN changes no longer block unlocking.** When a FIDO key
  requires a PIN change, the app opens the change-PIN form instead of failing
  with a PIN policy error. After the change, the key can be unlocked with the
  new PIN. CLI commands that need a PIN token now ask for a PIN change first
  instead of reporting a misleading new-PIN complexity error. ([#220])
