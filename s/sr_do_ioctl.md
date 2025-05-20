# Function: <code>sr_do_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff815c10b0)
Location: drivers/scsi/sr_ioctl.c:185
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
  - drivers/scsi/sr_vendor.c:sr_cd_check
```
**Symbols:**

```
ffffffff815c10b0-ffffffff815c130c: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff816197f0)
Location: drivers/scsi/sr_ioctl.c:185
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff816197f0-ffffffff81619a4d: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8164a480)
Location: drivers/scsi/sr_ioctl.c:185
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8164a480-ffffffff8164a6dd: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8165ed30)
Location: drivers/scsi/sr_ioctl.c:185
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8165ed30-ffffffff8165eec1: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff816c8340)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff816c8340-ffffffff816c84d1: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81704ce0)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81704ce0-ffffffff81704ee5: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81727290)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81727290-ffffffff81727436: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff817629d0)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff817629d0-ffffffff81762b76: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff817869c0)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff817869c0-ffffffff81786b66: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8184af40)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8184af40-ffffffff8184b0e6: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8185b360)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8185b360-ffffffff8185b506: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8183e350)
Location: drivers/scsi/sr_ioctl.c:182
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8183e350-ffffffff8183e4f6: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff818cae10)
Location: drivers/scsi/sr_ioctl.c:182
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff818cae10-ffffffff818cafc6: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81a17f90)
Location: drivers/scsi/sr_ioctl.c:188
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81a17f90-ffffffff81a1815e: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81b98ec0)
Location: drivers/scsi/sr_ioctl.c:188
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81b98ec0-ffffffff81b9908e: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81bef450)
Location: drivers/scsi/sr_ioctl.c:188
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81bef450-ffffffff81bef63f: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81c44bf0)
Location: drivers/scsi/sr_ioctl.c:188
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81c44bf0-ffffffff81c44ddf: sr_do_ioctl (STB_GLOBAL)
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
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffff80001098d4f8)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffff80001098d4f8-ffff80001098d6f4: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (c0a5f6dc)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_ioctl.c:sr_fake_playtrkind
  - drivers/scsi/sr_ioctl.c:sr_read_tocentry
  - drivers/scsi/sr_ioctl.c:sr_read_tochdr
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
c0a5f6dc-c0a5f8dc: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (c000000000a4ea30)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
c000000000a4ea30-c000000000a4ece0: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffe0005f18dc)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffe0005f18dc-ffffffe0005f1a72: sr_do_ioctl (STB_GLOBAL)
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
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8173b0b0)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8173b0b0-ffffffff8173b256: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8171cd50)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8171cd50-ffffffff8171cef6: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff8177b840)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff8177b840-ffffffff8177b9e6: sr_do_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sr_do_ioctl(Scsi_CD *cd, struct packet_command *cgc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sr_ioctl.c (ffffffff81795670)
Location: drivers/scsi/sr_ioctl.c:186
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_packet
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_audio_ioctl
  - drivers/scsi/sr_ioctl.c:sr_select_speed
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
  - drivers/scsi/sr_ioctl.c:sr_tray_move
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
**Symbols:**

```
ffffffff81795670-ffffffff81795816: sr_do_ioctl (STB_GLOBAL)
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
