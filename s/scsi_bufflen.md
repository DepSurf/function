# Function: <code>scsi_bufflen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a7b11)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff815ba7ca)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
```
```
In drivers/scsi/sr.c (ffffffff815bff2a)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff815d0a53)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815ff901)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81613125)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff816186c7)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81629da3)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162ef61)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81643217)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81649347)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8165aab3)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643d4c)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff816596c7)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8165dc5a)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8166f0c3)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ace5c)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff816c4097)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff816c7242)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff816d86a3)
Location: include/scsi/scsi_cmnd.h:192
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e9375)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff8170073b)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81703bbd)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff817155c2)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170ce75)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81723457)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8172608c)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81737b92)
Location: include/scsi/scsi_cmnd.h:198
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81748553)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff8175ec69)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff817617bc)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81773b82)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176c6a3)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81782bb8)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff817857ac)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81797af2)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e9a6)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff818461f5)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81849a5c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8185d6c6)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f9e6)
Location: include/scsi/scsi_cmnd.h:189
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff8185617e)
Location: include/scsi/scsi_cmnd.h:189
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81859fb4)
Location: include/scsi/scsi_cmnd.h:189
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8186c780)
Location: include/scsi/scsi_cmnd.h:189
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81822c46)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81838f2a)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8183cfc4)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8184f3cb)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ad568)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff818c557c)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff818c9950)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff818dca3b)
Location: include/scsi/scsi_cmnd.h:195
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f826c)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81a11fdd)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81a16cbb)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2fe71)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75c3c)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81b922cd)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81b97b1b)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb3433)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc955c)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be21ea)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/scsi/sd.c (ffffffff81be87c0)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81bee09a)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0a891)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1e14c)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c3730a)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/scsi/sd.c (ffffffff81c3dd1e)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81c437a7)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5f941)
Location: include/scsi/scsi_cmnd.h:191
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096eca0)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffff8000109897e0)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffff80001098c06c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffff8000109a1a54)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a4411c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (c0a5b940)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (c0a5e3e8)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (c0a719dc)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a2808c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (c000000000a49b24)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (c000000000a4d06c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (c000000000a66d4c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8e5e)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffe0005eda42)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffe0005f06be)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffe000600b02)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720d93)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff817372a8)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff81739e9c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8175cc02)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816fa1c3)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/storvsc_drv.c (ffffffff817140ce)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/scsi/sd.c (ffffffff81718f48)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8171bb3c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8173caa2)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175fb63)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81777a38)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8177a62c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c972)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177b1c3)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_finish_command
```
```
In drivers/scsi/sd.c (ffffffff81791858)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_done
  - drivers/scsi/sd.c:sd_completed_bytes
  - drivers/scsi/sd.c:sd_completed_bytes
```
```
In drivers/scsi/sr.c (ffffffff8179445c)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_init_command
  - drivers/scsi/sr.c:sr_done
```
```
In drivers/ata/libata-scsi.c (ffffffff817a67c2)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_security_inout_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_zbc_in_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:ata_scsi_pass_thru
  - drivers/ata/libata-scsi.c:atapi_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
</ul>

## Differences
