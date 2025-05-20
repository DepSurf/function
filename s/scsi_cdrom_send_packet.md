# Function: <code>scsi_cdrom_send_packet</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815678c0)
Location: block/scsi_ioctl.c:719
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff815678c0-ffffffff81567a51: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81582620)
Location: block/scsi_ioctl.c:710
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff81582620-ffffffff815827b1: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81589650)
Location: block/scsi_ioctl.c:706
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff81589650-ffffffff81589923: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct scsi_device *sdev, struct gendisk *disk, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff818af140)
Location: drivers/scsi/scsi_ioctl.c:809
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff818af140-ffffffff818af413: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct scsi_device *sdev, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff819f9c20)
Location: drivers/scsi/scsi_ioctl.c:792
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff819f9c20-ffffffff819f9f5d: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct scsi_device *sdev, fmode_t mode, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77b70)
Location: drivers/scsi/scsi_ioctl.c:776
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81b77b70-ffffffff81b77eb3: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct scsi_device *sdev, bool open_for_write, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb900)
Location: drivers/scsi/scsi_ioctl.c:779
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81bcb900-ffffffff81bcbb63: scsi_cdrom_send_packet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_cdrom_send_packet(struct scsi_device *sdev, bool open_for_write, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81c20530)
Location: drivers/scsi/scsi_ioctl.c:779
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81c20530-ffffffff81c20793: scsi_cdrom_send_packet (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct scsi_device *sdev</code>
</li>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gendisk *bd_disk</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param reordered. </b>
<code>sdev, disk, mode, arg</code> ➡️ <code>sdev, mode, arg</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_for_write</code>
</li>
<li>
<b>Param removed. </b>
<code>fmode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
