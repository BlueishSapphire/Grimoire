# Grimoire
Where I keep my tomes.

Terminology:

- **Spell Types**
	- **Concentration**: *a spell that runs continuously as a background process*
	- **Cantrip**: *a spell that runs once, quickly*
	- **Ritual**: *a spell that runs once, slowly*

- **Spell Planes**
	- **Windows**: *a spell that supports Windows systems*
	- **Posix**: *a spell that supports Posix systems*
	- **Patron**: *a spell that runs on an attacker Kali machine*

# Contents

- [Patron Spells](#patron-spells)
	- [`crack_passwd`](#crack_passwd)
	- [`remote_ffmpeg_injection`](#remote_ffmpeg_injection)
	- [`remote_php_upload`](#remote_php_upload)
	- [`remote_ssh`](#remote_ssh)
	- [`remote_ssti`](#remote_ssti)
	- [`scan_nmap`](#scan_nmap)
	- [`scan_smbmap`](#scan_smbmap)
	- [`scan_sqlmap`](#scan_sqlmap)
	- [`scan_wpscan`](#scan_wpscan)

- [Spells of Privelege](#spells-of-privelege)
	- [`try_all_privesc`](#try_all_privesc)
	- [`run_peas`](#run_peas)
	- [`exploit_cron`](#exploit_cron)
	- [`exploit_kernel`](#exploit_kernel)
	- [`exploit_sudo`](#exploit_sudo)
	- [`exploit_suid`](#exploit_suid)

- [Spells of Persistence](#spells-of-persistence)
	- [`backdoor_cron`](#backdoor_cron)
	- [`backdoor_kernel`](#backdoor_kernel)
	- [`backdoor_ldpreload`](#backdoor_ldpreload)
	- [`backdoor_ldso`](#backdoor_ldso)
	- [`backdoor_pam`](#backdoor_pam)
	- [`backdoor_passwd`](#backdoor_passwd)
	- [`backdoor_rhfs`](#backdoor_rhfs)
	- [`backdoor_shell_configs`](#backdoor_shell_configs)
	- [`backdoor_sudo`](#backdoor_sudo)
	- [`backdoor_systemd`](#backdoor_systemd)
	- [`backdoor_user`](#backdoor_user)
	- [`backdoor_sticky_keys`](#backdoor_sticky_keys)
	- [`minecraft_server_shell`](#minecraft_server_shell)
	- [`knock_knock_shell`](#knock_knock_shell)
	- [`drop_useful_utils`](#drop_useful_utils)

- [Spells of Affect](#spells-of-affect)
	- [`change_user_password`](#change_user_password)
	- [`swap_ids`](#swap_ids)
	- [`usermod`](#usermod)
	- [`call_upon_sparta`](#call_upon_sparta)

- [Spells of Competition](#spells-of-competition)
	- [`get_flag`](#get_flag)

- [Spells of Annoyance](#spells-of-annoyance)
	- [`disable_command`](#disable_command)
	- [`replace_bootloader`](#replace_bootloader)
	- [`send_wall_message`](#send_wall_message)
	- [`kill_all_sessions`](#kill_all_sessions)

# Patron Spells

## `crack_passwd`
- Type: *Ritual*
- Planes: *Patron*

TODO

## `remote_ffmpeg_injection`
- Type: *Cantrip*
- Planes: *Patron, Posix, Windows*

TODO

## `remote_php_upload`
- Type: *Cantrip*
- Planes: *Patron, Posix, Windows*

TODO

## `remote_ssh`
- Type: *Cantrip*
- Planes: *Patron, Posix, Windows*

TODO

## `remote_ssti`
- Type: *Cantrip*
- Planes: *Patron, Posix, Windows*

TODO

## `scan_nmap`
- Type: *Ritual*
- Planes: *Patron, Posix, Windows*

TODO

## `scan_smbmap`
- Type: *Ritual*
- Planes: *Patron*

TODO

## `scan_sqlmap`
- Type: *Ritual*
- Planes: *Patron*

TODO

## `scan_wpscan`
- Type: *Ritual*
- Planes: *Patron*

TODO

# Spells of Privelege

## `try_all_privesc`
- Type: *Ritual*
- Planes: *Posix, Windows*

TODO

## `run_peas`
- Type: *Ritual*
- Planes: *Posix, Windows*

TODO

## `exploit_cron`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `exploit_kernel`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `exploit_sudo`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `exploit_suid`
- Type: *Cantrip*
- Planes: *Posix*

TODO

# Spells of Persistence

## `backdoor_cron`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_kernel`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_ldpreload`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_ldso`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_pam`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_passwd`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_rhfs`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_shell_configs`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_sudo`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_systemd`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `backdoor_user`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

## `backdoor_sticky_keys`
- Type: *Cantrip*
- Planes: *Windows*

TODO

## `minecraft_server_shell`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

## `knock_knock_shell`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

## `drop_useful_utils`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

# Spells of Affect

## `change_user_password`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

## `swap_ids`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `usermod`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO

## `call_upon_sparta`
- Type: *Cantrip*
- Planes: *Posix, Windows*

TODO - finish the `windows_create_user` and `posix_create_user` functions

### Parameters

- **Username Format**
A string containing the format for the usernames generated, where the following substitutions are available:
	- `{num}` The number of users created so far
	- `{word}` The next word from the wordlist file
	- `{rand_int}` A random number between 0 and 2^31-1
	- `{rand_word}` A random word from the wordlist file

- **User Count**
The number of users to be generated

- **Wordlist File**
The wordlist file (only loaded if `{word}` or `{rand_word}` is used). Included wordlists:
	- `creatures.txt` A list of fantastical creatures from D&D 5e
	- `leet.txt` A list of leet-speak usernames
	- `spartans.txt` A list of Classical Greek sounding names, including kings of Sparta

### Examples
- **300 Spartans**
	- Username Format: `spartan{num}`
	- User Count: `300`
	- Wordlist File: 
- **300 Spartan Kings**
	- Username Format: `{rand_word}`
	- User Count: `300`
	- Wordlist File: `spartans.txt`
- **Mystical Army**
	- Username Format: `{rand_word}`
	- User Count: `64`
	- Wordlist File: `creatures.txt`


# Spells of Competition

## `get_flag`
- Type: *Concentration*
- Planes: *Posix*

TODO

# Spells of Annoyance

## `disable_command`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `replace_bootloader`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `send_wall_message`
- Type: *Cantrip*
- Planes: *Posix*

TODO

## `kill_all_sessions`
- Type: *Cantrip*
- Planes: *Posix*

TODO


