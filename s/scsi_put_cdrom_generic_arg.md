# Function: <code>scsi_put_cdrom_generic_arg</code>

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
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command *cgc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815670c0)
Location: block/scsi_ioctl.c:690
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff815670c0-ffffffff8156717a: scsi_put_cdrom_generic_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_put_cdrom_generic_arg(const struct cdrom_generic_command *cgc, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81581f50)
Location: block/scsi_ioctl.c:681
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cdrom_send_packet
```
**Symbols:**

```
ffffffff81581f50-ffffffff8158200a: scsi_put_cdrom_generic_arg (STB_LOCAL)
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
In block/scsi_ioctl.c (ffffffff815897e1)
Location: block/scsi_ioctl.c:677
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
In drivers/scsi/scsi_ioctl.c (ffffffff818af2d1)
Location: drivers/scsi/scsi_ioctl.c:780
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
In drivers/scsi/scsi_ioctl.c (ffffffff819f9e3a)
Location: drivers/scsi/scsi_ioctl.c:763
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
In drivers/scsi/scsi_ioctl.c (ffffffff81b77d6c)
Location: drivers/scsi/scsi_ioctl.c:747
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
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
In drivers/scsi/scsi_ioctl.c (ffffffff81bcba8e)
Location: drivers/scsi/scsi_ioctl.c:750
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
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
In drivers/scsi/scsi_ioctl.c (ffffffff81c206be)
Location: drivers/scsi/scsi_ioctl.c:750
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_cdrom_send_packet
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
</ul>
