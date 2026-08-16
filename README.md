# 🇦🇺 MIB2 Australia RadioStationDB

Updated Australian **RadioStationDB (RSDB)** for compatible Volkswagen MIB2 / MIB2.5 infotainment systems.

This community project improves Australian FM radio station identification and station-logo matching on compatible MIB units.

The database was created and tested using a Volkswagen/Harman MIB2.5 High system in Australia.

---

## 📻 What does this update do?

Some MIB2 / MIB2.5 units using older or European RadioStationDB data may:

- Display no logo for Australian FM stations
- Display incorrect station information
- Fail to match Australian stations with the correct artwork
- Contain outdated Australian station data

This updated RSDB improves matching for Australian stations.

Testing in Victoria showed successful matching for stations including:

- triple j
- The Fox / Fox 101.9
- Triple M
- KIIS 101.1
- Nova 100
- Smooth FM
- Gold 104.3
- SBS
- Light 89.9
- ABC Classic
- PBS 106.7
- 3MBS
- 3RRR

Additional stations may also be recognised depending on your location and the RDS information broadcast by the station.

---

## 📸 Results

### Before

Some Australian stations previously appeared without matching artwork or station information.

<!-- Add before screenshot here later -->

### After

After installing the updated RadioStationDB, compatible stations are automatically matched by the MIB system.

<!-- Add after screenshots here later -->

The station logos shown by the MIB depend on the database match, available artwork and the RDS/PI information received from the station.

---

## ✅ Tested Configuration

This release has been successfully tested on:

**Volkswagen Harman MIB2.5 High / Discover Pro**

The database successfully loads and matches Australian FM stations on the tested unit.

---

## ⚠️ Compatibility

This database may work with other compatible Volkswagen Group MIB2 / MIB2.5 systems that use the same RadioStationDB architecture.

However, it has **NOT been tested on every MIB variant**.

Potential systems include certain:

- Volkswagen MIB2
- Volkswagen MIB2.5
- Harman MIB High units
- Discover Pro systems
- Other compatible MQB infotainment systems

### Do NOT assume compatibility based only on the vehicle model.

Different units may use different:

- Hardware
- Firmware
- Train versions
- Database formats
- Radio configurations
- Regions

**Always make a backup of your original RadioStationDB before changing anything.**

---

# 💾 Installation

## Method used during development/testing

The database was installed using the **M.I.B. (More Incredible Bash)** toolbox.

If your unit already has M.I.B. installed, the RadioStationDB backup/restore functionality can be used to work with the database.

### 1. BACK UP YOUR ORIGINAL DATABASE FIRST

Before installing anything:

Open M.I.B. and navigate to:

`Backup / Restore → Advanced Backup → RadioStationDB`

Create a backup of the RadioStationDB currently installed on your unit.

**Keep this backup somewhere safe.**

Do not continue until you have a working backup.

---

### 2. Download the release

Download the latest release from the **Releases** section of this GitHub repository.

Extract the archive if required.

Read the included release notes before copying files to your SD card.

---

### 3. Prepare the SD card

Use an SD card compatible with your MIB system and M.I.B. installation.

Follow the folder structure supplied with the release.

Do not rename database files or change the supplied directory structure unless you know exactly what you are doing.

---

### 4. Install / Restore

Use the appropriate M.I.B. RadioStationDB restore/update function to install the database.

Allow the operation to finish completely.

**Do not remove power or the SD card while data is being written.**

---

### 5. Restart the MIB

After installation, reboot the infotainment system.

A common MIB restart method is holding the power button for approximately 10 seconds until the unit restarts.

---

### 6. Test the radio

Open:

`Radio → FM`

Allow the unit to receive local stations and RDS information.

Some station information may take time to populate.

If you previously stored presets, you may need to tune or save them again before the new match becomes visible.

---

# 🔧 Troubleshooting

## Station works but has no logo

A missing logo does not necessarily mean the database installation failed.

Matching can depend on:

- RDS station name
- PI code
- Frequency
- Region
- Available station artwork
- Information transmitted by the radio station

Some stations may therefore remain without artwork.

---

## Wrong station logo

Delete the affected preset, tune to the station again and allow the MIB to receive fresh RDS information.

Then save the station again.

If the incorrect match remains, please open a GitHub Issue and include:

- Station name
- Frequency
- City / region
- MIB model
- Firmware train/version
- Screenshot if possible

This information can help improve future versions.

---

## Database does not work on my unit

Restore your original RadioStationDB backup.

Please do not experiment with incompatible databases if you do not have a known-good backup.

---

# 🧪 Help Improve the Database

Reports from other Australian states and cities are welcome.

Testing from users in:

- Melbourne
- Sydney
- Brisbane
- Adelaide
- Perth
- Canberra
- Hobart
- Darwin
- Regional Australia

would be especially useful.

If you test the database, please report:

**Vehicle:**  
**MIB unit:**  
**Part number:**  
**Firmware:**  
**Location:**  
**Stations working:**  
**Stations missing:**  

This will help determine compatibility across different MIB hardware and Australian radio markets.

---

# ⚠️ Important Warning

Modifying infotainment system files always carries some risk.

Use this project **at your own risk**.

Before making any changes:

1. Back up your original RadioStationDB.
2. Make sure you know how to restore it.
3. Do not interrupt power during write operations.
4. Do not install files intended for incompatible hardware.

The project author and contributors are not responsible for damage, loss of functionality, corrupted data or other problems resulting from use of these files.

---

# 🙏 Credits

Thanks to the Volkswagen MIB community and the developers and contributors behind the M.I.B. project and related MIB research/tools.

This Australian RadioStationDB project was created through community experimentation, database analysis and real-world testing on Australian FM radio stations.

---

# ℹ️ Disclaimer

This is an independent community project.

It is **not affiliated with, authorised by, sponsored by or endorsed by Volkswagen AG, Harman International, or any related company**.

Volkswagen, Harman and other product names, logos and trademarks belong to their respective owners.

Radio station names and logos belong to their respective owners.

No ownership of third-party trademarks, artwork or proprietary Volkswagen/Harman material is claimed.

---

## ⭐ Support the Project

If this database works on your MIB system, consider giving the repository a **Star ⭐**.

More testing from different MIB units and different parts of Australia will help improve future releases.
