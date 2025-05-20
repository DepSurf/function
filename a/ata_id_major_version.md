# Function: <code>ata_id_major_version</code>

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
In drivers/ata/libata-core.c (ffffffff815cc038)
Location: include/linux/ata.h:732
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_do_set_mode
```
```
In drivers/ata/libata-scsi.c (ffffffff815cfded)
Location: include/linux/ata.h:732
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
```
```
In drivers/ata/libata-transport.c (ffffffff815da716)
Location: include/linux/ata.h:732
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff8162712a)
Location: include/linux/ata.h:804
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8162ab38)
Location: include/linux/ata.h:804
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff816342c6)
Location: include/linux/ata.h:804
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81657d94)
Location: include/linux/ata.h:848
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8165afff)
Location: include/linux/ata.h:848
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81665416)
Location: include/linux/ata.h:848
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff8166c5af)
Location: include/linux/ata.h:849
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8166f624)
Location: include/linux/ata.h:849
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81679bd6)
Location: include/linux/ata.h:849
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff816d5c08)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff816d8c04)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff816e3236)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff817119bb)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff81717d6a)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff8171fad9)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81733e7f)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8173a45a)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff817423c9)
Location: include/linux/ata.h:851
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff8176f98e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8177369e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff8177e0a7)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff817939fe)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff817975fe)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff817a1d67)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81857cf5)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8185cc62)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81865c17)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81867f71)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_trusted
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8186bd32)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81874a17)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff8184a7f5)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8184e38f)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81857130)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff818d79e5)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff818db9fc)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff818e5bf0)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81a28860)
Location: include/linux/ata.h:836
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2c3b7)
Location: include/linux/ata.h:836
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81a37067)
Location: include/linux/ata.h:836
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81bab33f)
Location: include/linux/ata.h:808
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff81baf9b7)
Location: include/linux/ata.h:808
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81bbbe77)
Location: include/linux/ata.h:808
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81c023ef)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff81c072e7)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81c136e7)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81c5847a)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_config_cpr
  - drivers/ata/libata-core.c:ata_dev_config_cdl
  - drivers/ata/libata-core.c:ata_identify_page_supported
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5c3c7)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81c688a7)
Location: include/linux/ata.h:816
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffff80001099dc90)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffff8000109a462c)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffff8000109ada40)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (c0a6e318)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (c0a7298c)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (c0a7d010)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (c000000000a61cb0)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (c000000000a66628)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (c000000000a749c4)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffe0005fdfca)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffe00060166c)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffe00060aaaa)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff81758b0e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8175c70e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81766e27)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff817389ae)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8173c5ae)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81746c87)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff8178887e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff8178c47e)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff81796be7)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
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
In drivers/ata/libata-core.c (ffffffff817a26ce)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_do_set_mode
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_configure
  - drivers/ata/libata-core.c:ata_dev_read_id
```
```
In drivers/ata/libata-scsi.c (ffffffff817a62ce)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b1
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
```
In drivers/ata/libata-transport.c (ffffffff817b0a57)
Location: include/linux/ata.h:835
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
```
</details>
</li>
</ul>

## Differences
