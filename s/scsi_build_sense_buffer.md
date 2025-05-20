# Function: <code>scsi_build_sense_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff815b1490)
Location: drivers/scsi/scsi_common.c:231
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_start_stop_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_invalid_field
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
```
**Symbols:**

```
ffffffff815b1490-ffffffff815b14c3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81609710)
Location: drivers/scsi/scsi_common.c:231
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81609710-ffffffff81609743: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81638ff0)
Location: drivers/scsi/scsi_common.c:231
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81638ff0-ffffffff81639023: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8164db10)
Location: drivers/scsi/scsi_common.c:231
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8164db10-ffffffff8164db43: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816b6de0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff816b6de0-ffffffff816b6e13: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff816f3150)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff816f3150-ffffffff816f3183: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8171eab0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8171eab0-ffffffff8171eae3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8175a190)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8175a190-ffffffff8175a1c3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8177e0a0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8177e0a0-ffffffff8177e0d3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81841630)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
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
ffffffff81841630-ffffffff81841663: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81851b50)
Location: drivers/scsi/scsi_common.c:232
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
ffffffff81851b50-ffffffff81851b83: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81834be0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
```
**Symbols:**

```
ffffffff81834be0-ffffffff81834c13: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff818c0f10)
Location: drivers/scsi/scsi_common.c:241
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
```
**Symbols:**

```
ffffffff818c0f10-ffffffff818c0f43: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81a0d620)
Location: drivers/scsi/scsi_common.c:241
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
```
**Symbols:**

```
ffffffff81a0d620-ffffffff81a0d671: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81b8d4c0)
Location: drivers/scsi/scsi_common.c:241
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
```
**Symbols:**

```
ffffffff81b8d4c0-ffffffff81b8d511: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81be1620)
Location: drivers/scsi/scsi_common.c:283
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81be1620-ffffffff81be1671: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81c36650)
Location: drivers/scsi/scsi_common.c:283
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_build_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-sata.c:ata_eh_read_sense_success_ncq_log
```
**Symbols:**

```
ffffffff81c36650-ffffffff81c366a1: scsi_build_sense_buffer (STB_GLOBAL)
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
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffff800010984660)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
```
**Symbols:**

```
ffff800010984660-ffff8000109846f0: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c0a56c68)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
c0a56c68-c0a56cb8: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (c000000000a414d0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
c000000000a414d0-c000000000a41520: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffe0005e93dc)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffe0005e93dc-ffffffe0005e944c: scsi_build_sense_buffer (STB_GLOBAL)
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
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81732790)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81732790-ffffffff817327c3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8170bbb0)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8170bbb0-ffffffff8170bbe3: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff81771560)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff81771560-ffffffff81771593: scsi_build_sense_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void scsi_build_sense_buffer(int desc, u8 *buf, u8 key, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_common.c (ffffffff8178cd00)
Location: drivers/scsi/scsi_common.c:232
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_out_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_mode_sense
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rw_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_verify_xlat
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_gen_passthru_sense
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
```
**Symbols:**

```
ffffffff8178cd00-ffffffff8178cd33: scsi_build_sense_buffer (STB_GLOBAL)
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
