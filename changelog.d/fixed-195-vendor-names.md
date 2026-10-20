- **Keys with USB vendor ID 0x311F are no longer labeled Feitian.** That ID
  was filed under Feitian by mistake, so other makers' keys showed the wrong
  brand; they now show the generic "Security key" until their maker is
  known. On Windows without administrator rights, a FIDO-only key's card
  showed its raw vendor ID instead of a name; it now uses the same names as
  everywhere else. Reported by @Ephemera42. ([#195])
