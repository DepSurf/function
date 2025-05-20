# Function: <code>sd_ioctl_common</code>

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
int sd_ioctl_common(struct block_device *bdev, fmode_t mode, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff81842d30)
Location: drivers/scsi/sd.c:1491
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff81842d30-ffffffff81842f0c: sd_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_ioctl_common(struct block_device *bdev, fmode_t mode, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818536c0)
Location: drivers/scsi/sd.c:1535
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff818536c0-ffffffff81853899: sd_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sd_ioctl_common(struct block_device *bdev, fmode_t mode, unsigned int cmd, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd.c (ffffffff818370e0)
Location: drivers/scsi/sd.c:1549
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_compat_ioctl
  - drivers/scsi/sd.c:sd_ioctl
```
**Symbols:**

```
ffffffff818370e0-ffffffff818372ad: sd_ioctl_common (STB_LOCAL)
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
