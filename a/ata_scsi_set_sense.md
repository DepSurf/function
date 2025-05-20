# Function: <code>ata_scsi_set_sense</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff815d08a1)
Location: drivers/ata/libata-scsi.c:273
Inline: True
Inline callers:
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
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8162d711)
Location: drivers/ata/libata-scsi.c:273
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8162cae0-ffffffff8162cb20: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8165e768)
Location: drivers/ata/libata-scsi.c:351
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8165dc10-ffffffff8165dc50: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8167312d)
Location: drivers/ata/libata-scsi.c:351
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81672650-ffffffff8167268d: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff816dc71d)
Location: drivers/ata/libata-scsi.c:352
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff816dbc40-ffffffff816dbc7d: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81718e8d)
Location: drivers/ata/libata-scsi.c:352
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff817183c0-ffffffff817183fc: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8173b53d)
Location: drivers/ata/libata-scsi.c:353
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8173aa10-ffffffff8173aa4c: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81777162)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81776660-ffffffff8177669c: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8179b0c2)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8179a5c0-ffffffff8179a5fc: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185efbc)
Location: drivers/ata/libata-scsi.c:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8185e0c0-ffffffff8185e0fc: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8186dfe8)
Location: drivers/ata/libata-scsi.c:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8186d0f0-ffffffff8186d12c: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8185084c)
Location: drivers/ata/libata-scsi.c:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8184fc90-ffffffff8184fcc1: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff818de04e)
Location: drivers/ata/libata-scsi.c:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff818dd400-ffffffff818dd431: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81a2f503)
Location: drivers/ata/libata-scsi.c:191
Inline: True
Inline callers:
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
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_gen_ata_sense
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81a2ded0-ffffffff81a2df23: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81bb2a77)
Location: drivers/ata/libata-scsi.c:207
Inline: True
Inline callers:
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
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_request_sense
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81bb18b0-ffffffff81bb1903: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c09fa7)
Location: drivers/ata/libata-scsi.c:211
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81c08da0-ffffffff81c08ddc: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c5f05c)
Location: drivers/ata/libata-scsi.c:211
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
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
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_get_success_sense
  - drivers/ata/libata-sata.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff81c5de80-ffffffff81c5debc: ata_scsi_set_sense (STB_GLOBAL)
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
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffff8000109a5b10)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffff8000109a4988-ffff8000109a49f8: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c0a75c50)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
c0a74d70-c0a74db8: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (c000000000a6b978)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
c000000000a6a9e0-c000000000a6aa34: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffe000604814)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffe000603e02-ffffffe000603e60: ata_scsi_set_sense (STB_GLOBAL)
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
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817601b2)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8175f6b0-ffffffff8175f6ec: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81740012)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8173f510-ffffffff8173f54c: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff8178ff42)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff8178f440-ffffffff8178f47c: ata_scsi_set_sense (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ata_scsi_set_sense(struct ata_device *dev, struct scsi_cmnd *cmd, u8 sk, u8 asc, u8 ascq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff817a9d82)
Location: drivers/ata/libata-scsi.c:337
Inline: True
Inline callers:
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
  - drivers/ata/libata-scsi.c:ata_scsi_set_invalid_field
Direct callers:
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_analyze_ncq_error
```
**Symbols:**

```
ffffffff817a9280-ffffffff817a92bc: ata_scsi_set_sense (STB_GLOBAL)
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
