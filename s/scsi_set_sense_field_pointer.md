# Function: <code>scsi_set_sense_field_pointer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81609840)
Location: drivers/scsi/scsi_common.c:309
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81609840-ffffffff8160992b: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81639120)
Location: drivers/scsi/scsi_common.c:309
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81639120-ffffffff8163920b: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8164dd30)
Location: drivers/scsi/scsi_common.c:309
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8164dd30-ffffffff8164de26: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816b7000)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff816b7000-ffffffff816b7111: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816f3330)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff816f3330-ffffffff816f3428: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8171ec90)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8171ec90-ffffffff8171ed88: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8175a380)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8175a380-ffffffff8175a47a: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8177e290)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8177e290-ffffffff8177e38a: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff818416b0)
Location: drivers/scsi/scsi_common.c:310
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff818416b0-ffffffff818417a6: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81851bd0)
Location: drivers/scsi/scsi_common.c:310
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81851bd0-ffffffff81851cc6: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81834c50)
Location: drivers/scsi/scsi_common.c:310
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81834c50-ffffffff81834d45: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff818c0fe0)
Location: drivers/scsi/scsi_common.c:319
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff818c0fe0-ffffffff818c10d5: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81a0d890)
Location: drivers/scsi/scsi_common.c:319
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81a0d890-ffffffff81a0d98b: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81b8d780)
Location: drivers/scsi/scsi_common.c:319
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81b8d780-ffffffff81b8d87b: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81be18d0)
Location: drivers/scsi/scsi_common.c:361
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81be18d0-ffffffff81be19c9: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81c36900)
Location: drivers/scsi/scsi_common.c:361
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
```
**Symbols:**

```
ffffffff81c36900-ffffffff81c369f9: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffff800010984938)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
**Symbols:**

```
ffff800010984938-ffff800010984a8c: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c0a56f10)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
c0a56f10-c0a57008: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c000000000a417e0)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
c000000000a417e0-c000000000a41968: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffe0005e95ea)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffe0005e95ea-ffffffe0005e9706: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81732980)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81732980-ffffffff81732a7a: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8170bda0)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8170bda0-ffffffff8170be9a: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81771750)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81771750-ffffffff8177184a: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int scsi_set_sense_field_pointer(u8 *buf, int buf_len, u16 fp, u8 bp, bool cd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8178cef0)
Location: drivers/scsi/scsi_common.c:310
Inline: True
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8178cef0-ffffffff8178cfea: scsi_set_sense_field_pointer (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
