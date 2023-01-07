{
  "mojang_configuration": "https://launcher.sonoyuncu.network/minecraft/launcher.json",
  "java_preferred_type": "so",
  "version": "0.1.32",
  "updater": {
    "checksum": "8169544641548a494db203833d76f807f0a99f4c",
    "url": "https://assets.sonoyuncu.com.tr/bootstrap/updater.jar"
  },
  "nativeUpdater": {
    "windows": {
	  "checksum": "53cc7566cd42a210836bca9f79e06ccc2bd3465a",
	  "name": "soup.exe",
	  "url": "https://assets.sonoyuncu.com.tr/bootstrap/native-updaters/soup_win.exe",
	  "cmd": ["cmd.exe", "/c", "start", "%updaterPath%"]
    }
  },
  "versionControl": {
    "windows": {
      "checksum": "99f1735c05769c355193519a82a2160faea270b2",
      "url": "https://assets.sonoyuncu.com.tr/bootstrap/bootstrap_win.exe"
    },
    "osx": {
      "checksum": "1fce5c6e82429ac5e5dcd71ccf5ba41473319146",
      "checksumComp": "c649703942e9164cf106460351c2d242b76fe6ca",
      "url": "https://assets.sonoyuncu.com.tr/bootstrap/bootstrap_osx.zip"
    },
    "linux": {
      "checksum": "3d8c2ad879d7e750436c480fdc209a10a14554c3",
      "checksumComp": "f07d4f2905001fc359aabc732267e75e807ad1f3",
      "url": "https://assets.sonoyuncu.com.tr/bootstrap/bootstrap_linux.tar.gz"
    }
  },
  "launcher_jar_url": "https://assets.sonoyuncu.com.tr/minecraft-launcher/launcher.jar",
  "launcher_jar_checksum": "a9520f945c256d89910cae4891874ba6c31bc769",
  "launcher_path": "launcher.jar",
  "launcher_args": "-XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Dcom.sun.net.ssl.checkRevocation=false -XX:+UseConcMarkSweepGC -XX:+CMSIncrementalMode -XX:-UseAdaptiveSizePolicy -XX:+DisableAttachMechanism -Dcom.ibm.tools.attach.enable=true -Djna.encoding=UTF-8 -Dlog4j2.formatMsgNoLookups=true -Dr=1 -Xmn%initRAM%M -Xmx%maxRAM%M -Djava.net.preferIPv4Stack=true %runArgs%",
  "javaIntegrity": [
    {
      "path": "lib/rt.jar",
      "checksum32": "9d1b42f8a9b0f030276e00128bb940a9010ad654",
	  "checksum64": "9d1b42f8a9b0f030276e00128bb940a9010ad654"
    }
  ]
}
