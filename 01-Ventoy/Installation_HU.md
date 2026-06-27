# 💾 Telepítés

> Ismerd meg, hogyan telepítheted a Ventoyt a pendrive-odra, valamint a telepítés során elérhető legfontosabb beállításokat.

---

# 📝 Áttekintés

A Ventoy telepítése gyors és egyszerű folyamat. A hagyományos bootolható USB-készítő programokkal ellentétben a Ventoyt elegendő **egyetlen alkalommal** telepíteni a pendrive-ra.

A telepítés után a pendrive úgy használható, mint egy hagyományos adattároló: egyszerűen másold rá a kívánt ISO fájlokat, és máris készen áll a használatra. Nincs szükség a pendrive újraformázására vagy a Ventoy újratelepítésére minden egyes operációs rendszer telepítése előtt.

> **Figyelem:** A Ventoy telepítése a kiválasztott pendrive teljes tartalmát törli.

---

# 📋 Mielőtt elkezded

A telepítés előtt győződj meg arról, hogy:

* ✅ Letöltötted és kicsomagoltad a Ventoy legfrissebb verzióját.
* ✅ A használni kívánt USB pendrive csatlakoztatva van.
* ✅ A fontos adatokról biztonsági mentést készítettél.
* ✅ Rendelkezel rendszergazdai jogosultsággal.

---

# 🚀 A Ventoy telepítése

1. Nyisd meg a kicsomagolt Ventoy mappát.
2. Indítsd el a **Ventoy2Disk.exe** alkalmazást rendszergazdaként.
3. A **Device** mezőben válaszd ki a pendrive-odat.
4. Ellenőrizd még egyszer, hogy valóban a megfelelő eszközt választottad ki.
5. Kattints az **Install** gombra.
6. Fogadd el a figyelmeztető üzeneteket.
7. Várd meg, amíg a telepítés befejeződik.

A folyamat végén a Windows ismét felismeri a pendrive-ot.

Ezzel a Ventoy sikeresen telepítésre került.

---

# 📂 A Ventoy használata

Nyisd meg a pendrive-ot a Fájlkezelőben.

A Ventoy telepítése után ugyanúgy használható, mint egy hagyományos USB meghajtó.

Egyszerűen másold rá a használni kívánt ISO fájlokat.

Például:

```text
Fedora.iso
Debian.iso
Arch.iso
```

Miután minden fájlt átmásoltál, biztonságosan távolítsd el a pendrive-ot.

---

# 💾 GPT vagy MBR?

A Ventoy telepítése során kiválasztható, hogy a pendrive **GPT** vagy **MBR** partíciós sémát használjon.

### GPT (Ajánlott)

A **GPT (GUID Partition Table)** a modern partíciós séma, amelyet a mai számítógépek többsége használ.

Előnyei:

* UEFI rendszerek teljes támogatása
* Secure Boot kompatibilitás
* Jobb kompatibilitás modern hardverekkel
* Korszerűbb és megbízhatóbb megoldás

### MBR

Az **MBR (Master Boot Record)** egy régebbi partíciós séma.

Előnyei:

* Régebbi, BIOS-alapú számítógépekkel is kompatibilis
* Legacy rendszerek esetén hasznos lehet

Hátrányai:

* Régebbi technológia
* Korlátozottabb lehetőségek
* Modern rendszereknél általában nincs rá szükség

> **Ajánlás:** Ha nem régi, kizárólag Legacy BIOS-os számítógépet használsz, válaszd a **GPT** partíciós sémát.

---

# 🔐 Secure Boot

A legtöbb modern számítógép **UEFI Secure Boot** funkciót használ.

A Ventoy teljes mértékben támogatja a Secure Boot használatát, azonban előfordulhat, hogy az első indításkor engedélyezned kell a Ventoy saját biztonsági kulcsát.

Ez teljesen normális folyamat.

Csak kövesd a képernyőn megjelenő utasításokat, és egyszer regisztráld a Ventoy kulcsát. Ezt követően a rendszer minden további indításkor automatikusan működni fog.

Ha régebbi, Legacy BIOS-os számítógépet használsz, a Secure Boot nem releváns.

---

# ✅ A telepítés befejezése

Gratulálok!

A Ventoy pendrive elkészült, és használatra kész.

Mostantól egy új operációs rendszer telepítéséhez mindössze ennyit kell tenned:

1. Letölteni a kívánt ISO fájlt.
2. Rámásolni a pendrive-ra.
3. A pendrive-ról bootolni.
4. Kiválasztani az indítani kívánt ISO-t a Ventoy menüjéből.

A Ventoyt ezután már nem kell újratelepítened.

---

# 💡 Hasznos tanácsok

* Időnként frissítsd a Ventoy legújabb verziójára.
* Adj egyértelmű neveket az ISO fájloknak.
* Több ISO esetén érdemes mappákba rendezni őket.
* A pendrive eltávolítása előtt mindig használd a biztonságos hardvereltávolítást.

---

# 👋 Záró gondolatok

A Ventoy egyik legnagyobb előnye az egyszerűsége. A telepítés után a pendrive egy univerzális, több rendszer indítására alkalmas eszközzé válik, amelyre bármikor új ISO fájlokat másolhatsz anélkül, hogy újra kellene készítened az egész meghajtót.

A következő útmutatóban megismerheted a Ventoy testreszabási lehetőségeit, például a Secure Boot beállításait, a témák használatát, a plugineket és egyéb hasznos konfigurációkat.