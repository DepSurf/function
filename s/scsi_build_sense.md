# Function: <code>scsi_build_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81829650)
Location: drivers/scsi/scsi_lib.c:3235
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81829650-ffffffff81829685: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b4f40)
Location: drivers/scsi/scsi_lib.c:3228
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff818b4f40-ffffffff818b4f75: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819ffec0)
Location: drivers/scsi/scsi_lib.c:3312
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff819ffec0-ffffffff819fff04: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7e0d0)
Location: drivers/scsi/scsi_lib.c:3317
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81b7e0d0-ffffffff81b7e114: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd1eb0)
Location: drivers/scsi/scsi_lib.c:3336
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81bd1eb0-ffffffff81bd1ef4: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_build_sense(struct scsi_cmnd *scmd, int desc, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c26b20)
Location: drivers/scsi/scsi_lib.c:3333
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffffffff81c26b20-ffffffff81c26b64: scsi_build_sense (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
