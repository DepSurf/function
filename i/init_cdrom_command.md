# Function: <code>init_cdrom_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815fda60)
Location: drivers/cdrom/cdrom.c:1580
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff815fda60-ffffffff815fdad2: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165e025)
Location: drivers/cdrom/cdrom.c:1580
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8165d9f0-ffffffff8165da62: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168be15)
Location: drivers/cdrom/cdrom.c:1580
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8168b7e0-ffffffff8168b852: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a08b0)
Location: drivers/cdrom/cdrom.c:1578
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff816a08b0-ffffffff816a0921: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170baa0)
Location: drivers/cdrom/cdrom.c:1578
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8170baa0-ffffffff8170bb11: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174aee0)
Location: drivers/cdrom/cdrom.c:1575
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8174aee0-ffffffff8174af52: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8176f100)
Location: drivers/cdrom/cdrom.c:1575
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8176f100-ffffffff8176f172: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817acf60)
Location: drivers/cdrom/cdrom.c:1576
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff817acf60-ffffffff817acfd2: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817dd240)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff817dd240-ffffffff817dd2b2: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818afa93)
Location: drivers/cdrom/cdrom.c:1586
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff818abc70-ffffffff818abce2: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818be813)
Location: drivers/cdrom/cdrom.c:1569
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff818ba8b0-ffffffff818ba922: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a1303)
Location: drivers/cdrom/cdrom.c:1569
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff8189dc00-ffffffff8189dc72: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81935b98)
Location: drivers/cdrom/cdrom.c:1569
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff819312b0-ffffffff81931322: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a8cf58)
Location: drivers/cdrom/cdrom.c:1570
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff81a88250-ffffffff81a882d3: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0dcb8)
Location: drivers/cdrom/cdrom.c:1570
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff81c09390-ffffffff81c09413: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c700b0)
Location: drivers/cdrom/cdrom.c:1553
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff81c700b0-ffffffff81c70133: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d24960)
Location: drivers/cdrom/cdrom.c:1553
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:dvd_read_physical
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_read_mech_status
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_dvd_rw_close_write
  - drivers/cdrom/cdrom.c:cdrom_open_write
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff81d24960-ffffffff81d249e3: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0a618)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffff800010a0a618-ffff800010a0a688: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae2218)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_subchannel
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_open_write
  - drivers/cdrom/cdrom.c:cdrom_mrw_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
c0ae2218-c0ae2278: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac0010)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
c000000000ac0010-c000000000ac00b4: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe00063191e)
Location: drivers/cdrom/cdrom.c:1583
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffe0006312ec-ffffffe000631352: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81795620)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff81795620-ffffffff81795692: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817872f0)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff817872f0-ffffffff81787362: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d20c0)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff817d20c0-ffffffff817d2132: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_cdrom_command(struct packet_command *cgc, void *buf, int len, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ec360)
Location: drivers/cdrom/cdrom.c:1583
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:mmc_ioctl_dvd_read_struct
  - drivers/cdrom/cdrom.c:dvd_do_auth
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_load_unload
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_open
  - drivers/cdrom/cdrom.c:cdrom_ram_open_write
  - drivers/cdrom/cdrom.c:mo_open_write
  - drivers/cdrom/cdrom.c:cdrom_get_random_writable
  - drivers/cdrom/cdrom.c:cdrom_get_media_event
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_mrw_exit
  - drivers/cdrom/cdrom.c:cdrom_is_mrw
  - drivers/cdrom/cdrom.c:cdrom_mrw_probe_pc
  - drivers/cdrom/cdrom.c:cdrom_get_disc_info
```
**Symbols:**

```
ffffffff817ec360-ffffffff817ec3d2: init_cdrom_command (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
