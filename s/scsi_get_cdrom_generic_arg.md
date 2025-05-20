# Function: <code>scsi_get_cdrom_generic_arg</code>

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
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command *cgc, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567180)
Location: block/scsi_ioctl.c:660
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff81567180-ffffffff81567265: scsi_get_cdrom_generic_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command *cgc, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81582010)
Location: block/scsi_ioctl.c:651
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff81582010-ffffffff815820f5: scsi_get_cdrom_generic_arg (STB_LOCAL)
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
In block/scsi_ioctl.c (ffffffff81589683)
Location: block/scsi_ioctl.c:647
Inline: True
Inline callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
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
In drivers/scsi/scsi_ioctl.c (ffffffff818af173)
Location: drivers/scsi/scsi_ioctl.c:750
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
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
In drivers/scsi/scsi_ioctl.c (ffffffff819f9c7b)
Location: drivers/scsi/scsi_ioctl.c:733
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
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
In drivers/scsi/scsi_ioctl.c (ffffffff81b77bcb)
Location: drivers/scsi/scsi_ioctl.c:717
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command *cgc, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb0c0)
Location: drivers/scsi/scsi_ioctl.c:720
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff81bcb0c0-ffffffff81bcb1bf: scsi_get_cdrom_generic_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_get_cdrom_generic_arg(struct cdrom_generic_command *cgc, const void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81c1fcf0)
Location: drivers/scsi/scsi_ioctl.c:720
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff81c1fcf0-ffffffff81c1fdef: scsi_get_cdrom_generic_arg (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
