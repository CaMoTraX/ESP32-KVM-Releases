# ESP32 KVM – Downloads

Fertige Firmware für den ESP32 KVM: Fernsteuerung für Windows über einen **ESP32-S3 N16R8** (16 MB Flash, 8 MB PSRAM).

1. Unter **[Releases](../../releases/latest)** `ESP32-KVM-vX.Y.Z.zip` laden und **entpacken**.
2. ESP32 über die Buchse **COM/UART** anschließen und **`install.cmd`** starten. Das Skript prüft das Board, flasht es und zeigt die Startpasswörter.
3. Handy mit dem WLAN `ESP32-KVM-XXXX` verbinden: WLAN wählen, neues Passwort setzen.
4. ESP32 über die Buchse **USB** an den Server stecken, `https://esp32-kvm.local/` öffnen und **Bild aktivieren** klicken.

Spätere Versionen meldet die KVM-Seite selbst (**Update**). Sie werden nur mit gültiger Signatur installiert; startet eine
Version nicht sauber, kehrt das Gerät zur vorherigen zurück. `latest.txt` und `firmware-*.bin` sind dafür da.

`ESP32-KVM-Helfer-…zip` braucht nur, wer Windows über den KVM installieren will. Fremdsoftware: `THIRD-PARTY.md` im ZIP.
