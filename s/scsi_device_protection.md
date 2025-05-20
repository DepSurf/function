# Function: <code>scsi_device_protection</code>

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
In drivers/scsi/sd.c (ffffffff815bba83)
Location: include/scsi/scsi_device.h:500
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_revalidate_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81616d8e)
Location: include/scsi/scsi_device.h:513
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81646856)
Location: include/scsi/scsi_device.h:518
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:read_capacity_16
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8165b3d9)
Location: include/scsi/scsi_device.h:517
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff816c4a53)
Location: include/scsi/scsi_device.h:533
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81700f95)
Location: include/scsi/scsi_device.h:533
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81723e13)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
  - drivers/scsi/sd.c:sd_setup_read_write_cmnd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8175da9b)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8178196b)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8184756b)
Location: include/scsi/scsi_device.h:554
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81856f7b)
Location: include/scsi/scsi_device.h:555
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81839ceb)
Location: include/scsi/scsi_device.h:556
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818c636b)
Location: include/scsi/scsi_device.h:563
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_protection_type
  - drivers/scsi/sd.c:sd_read_protection_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81a12e97)
Location: include/scsi/scsi_device.h:571
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81b93233)
Location: include/scsi/scsi_device.h:572
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81be975a)
Location: include/scsi/scsi_device.h:574
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81c3ecba)
Location: include/scsi/scsi_device.h:595
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:read_capacity_16
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffff8000109886d0)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c0a5a710)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (c000000000a48320)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffe0005ec76c)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff8173605b)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81717cfb)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817767eb)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff817905cb)
Location: include/scsi/scsi_device.h:545
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_read_capacity
  - drivers/scsi/sd.c:sd_read_capacity
```
</details>
</li>
</ul>

## Differences
