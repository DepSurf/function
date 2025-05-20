# Function: <code>ata_id_has_trim</code>

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
In drivers/ata/libata-scsi.c (ffffffff815d12e7)
Location: include/linux/ata.h:823
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
```
```
In drivers/ata/libata-transport.c (ffffffff815da716)
Location: include/linux/ata.h:823
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
In drivers/ata/libata-scsi.c (ffffffff8162ab38)
Location: include/linux/ata.h:900
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff816342c6)
Location: include/linux/ata.h:900
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
In drivers/ata/libata-scsi.c (ffffffff8165afff)
Location: include/linux/ata.h:949
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81665416)
Location: include/linux/ata.h:949
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
In drivers/ata/libata-scsi.c (ffffffff8166f624)
Location: include/linux/ata.h:957
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81679bd6)
Location: include/linux/ata.h:957
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
In drivers/ata/libata-scsi.c (ffffffff816d8c04)
Location: include/linux/ata.h:959
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff816e3236)
Location: include/linux/ata.h:959
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
In drivers/ata/libata-scsi.c (ffffffff81717d6a)
Location: include/linux/ata.h:959
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff8171fad9)
Location: include/linux/ata.h:959
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
In drivers/ata/libata-scsi.c (ffffffff8173a45a)
Location: include/linux/ata.h:959
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff817423c9)
Location: include/linux/ata.h:959
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
In drivers/ata/libata-scsi.c (ffffffff8177369e)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff8177e0a7)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff817975fe)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff817a1d67)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8185cc62)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81865c17)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8186bd32)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81874a17)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8184e38f)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81857130)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff818db9fc)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff818e5bf0)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff81a2c3b7)
Location: include/linux/ata.h:944
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81a37067)
Location: include/linux/ata.h:944
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
In drivers/ata/libata-scsi.c (ffffffff81baf9b7)
Location: include/linux/ata.h:916
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81bbbe77)
Location: include/linux/ata.h:916
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
In drivers/ata/libata-scsi.c (ffffffff81c072e7)
Location: include/linux/ata.h:924
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81c136e7)
Location: include/linux/ata.h:924
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
In drivers/ata/libata-scsi.c (ffffffff81c5c3c7)
Location: include/linux/ata.h:924
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81c688a7)
Location: include/linux/ata.h:924
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
In drivers/ata/libata-scsi.c (ffff8000109a462c)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffff8000109ada40)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (c0a7298c)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
```
```
In drivers/ata/libata-transport.c (c0a7d010)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (c000000000a66628)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (c000000000a749c4)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffe00060166c)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
```
```
In drivers/ata/libata-transport.c (ffffffe00060aaaa)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8175c70e)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81766e27)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8173c5ae)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81746c87)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff8178c47e)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff81796be7)
Location: include/linux/ata.h:943
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
In drivers/ata/libata-scsi.c (ffffffff817a62ce)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_read_cap
  - drivers/ata/libata-scsi.c:ata_scsiop_inq_b0
```
```
In drivers/ata/libata-transport.c (ffffffff817b0a57)
Location: include/linux/ata.h:943
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:show_ata_dev_trim
```
</details>
</li>
</ul>

## Differences
