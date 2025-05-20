# Function: <code>scsi_eh_finish_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815a95b0)
Location: drivers/scsi/scsi_error.c:1128
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
  - drivers/scsi/scsi_error.c:scsi_error_handler
Direct callers:
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
```
**Symbols:**

```
ffffffff815a95b0-ffffffff815a95f8: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81604d05)
Location: drivers/scsi/scsi_error.c:1129
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81601500-ffffffff8160153b: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816343e7)
Location: drivers/scsi/scsi_error.c:1129
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_error_handler
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81630bf0-ffffffff81630c2b: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81646d3c)
Location: drivers/scsi/scsi_error.c:1116
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff816459e0-ffffffff81645a11: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816afd9c)
Location: drivers/scsi/scsi_error.c:1142
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff816ae9b0-ffffffff816ae9e1: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ec15d)
Location: drivers/scsi/scsi_error.c:1170
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff816ead60-ffffffff816ead91: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8170fc9d)
Location: drivers/scsi/scsi_error.c:1167
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8170e810-ffffffff8170e841: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174b4f4)
Location: drivers/scsi/scsi_error.c:1187
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81749fb0-ffffffff81749fe1: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8176f674)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8176e110-ffffffff8176e141: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81832867)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff818306d0-ffffffff81830701: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81843477)
Location: drivers/scsi/scsi_error.c:1198
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_host_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81841330-ffffffff81841361: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81826540)
Location: drivers/scsi/scsi_error.c:1211
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81824520-ffffffff81824551: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff818b1e60)
Location: drivers/scsi/scsi_error.c:1230
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff818afda0-ffffffff818afdd1: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff819fcee4)
Location: drivers/scsi/scsi_error.c:1235
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff819fac70-ffffffff819facaf: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7b174)
Location: drivers/scsi/scsi_error.c:1242
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81b78cb0-ffffffff81b78cef: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcee84)
Location: drivers/scsi/scsi_error.c:1275
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
```
**Symbols:**

```
ffffffff81bcc940-ffffffff81bcc97f: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c23aa4)
Location: drivers/scsi/scsi_error.c:1278
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_bus_reset
  - drivers/scsi/scsi_error.c:scsi_eh_target_reset
  - drivers/scsi/scsi_error.c:scsi_eh_bus_device_reset
  - drivers/scsi/scsi_error.c:scsi_eh_stu
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81c21570-ffffffff81c215af: scsi_eh_finish_cmd (STB_GLOBAL)
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
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffff800010972938)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffff800010971060-ffff8000109710a8: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c0a4718c)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
c0a45c9c-c0a45cdc: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (c000000000a2c01c)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
c000000000a2a4d0-c000000000a2a504: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffe0005db942)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffe0005da668-ffffffe0005da6aa: scsi_eh_finish_cmd (STB_GLOBAL)
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
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81723d64)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff81722800-ffffffff81722831: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816fd194)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff816fbc30-ffffffff816fbc61: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81762b34)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff817615d0-ffffffff81761601: scsi_eh_finish_cmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_eh_finish_cmd(struct scsi_cmnd *scmd, struct list_head *done_q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8177e194)
Location: drivers/scsi/scsi_error.c:1190
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_eh_test_devices
  - drivers/scsi/scsi_error.c:scsi_eh_get_sense
Direct callers:
  - drivers/ata/libata-eh.c:__ata_eh_qc_complete
  - drivers/ata/libata-eh.c:ata_scsi_cmd_error_handler
```
**Symbols:**

```
ffffffff8177cc30-ffffffff8177cc61: scsi_eh_finish_cmd (STB_GLOBAL)
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
