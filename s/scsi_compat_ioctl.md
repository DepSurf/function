# Function: <code>scsi_compat_ioctl</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_compat_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff818301c0)
Location: drivers/scsi/scsi_ioctl.c:288
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sr.c:sr_block_compat_ioctl
  - drivers/scsi/sg.c:sg_compat_ioctl
```
**Symbols:**

```
ffffffff818301c0-ffffffff8183020e: scsi_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsi_compat_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81840e80)
Location: drivers/scsi/scsi_ioctl.c:288
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sr.c:sr_block_compat_ioctl
  - drivers/scsi/sg.c:sg_compat_ioctl
```
**Symbols:**

```
ffffffff81840e80-ffffffff81840ece: scsi_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_compat_ioctl(struct scsi_device *sdev, int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81824070)
Location: drivers/scsi/scsi_ioctl.c:288
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sr.c:sr_block_compat_ioctl
  - drivers/scsi/sg.c:sg_compat_ioctl
```
**Symbols:**

```
ffffffff81824070-ffffffff818240be: scsi_compat_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
