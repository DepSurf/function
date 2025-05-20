# Function: <code>sg_ioctl_common</code>

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
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81850580)
Location: drivers/scsi/sg.c:918
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81850580-ffffffff81851084: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818609d0)
Location: drivers/scsi/sg.c:918
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff818609d0-ffffffff8186147d: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818436d0)
Location: drivers/scsi/sg.c:917
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_compat_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff818436d0-ffffffff81844209: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818d01a0)
Location: drivers/scsi/sg.c:921
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff818d01a0-ffffffff818d0cd2: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a1d420)
Location: drivers/scsi/sg.c:917
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81a1d420-ffffffff81a1dedb: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9e730)
Location: drivers/scsi/sg.c:917
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81b9e730-ffffffff81b9f1eb: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf4d50)
Location: drivers/scsi/sg.c:917
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81bf4d50-ffffffff81bf5905: sg_ioctl_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int sg_ioctl_common(struct file *filp, Sg_device *sdp, Sg_fd *sfp, unsigned int cmd_in, void *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c4a690)
Location: drivers/scsi/sg.c:917
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81c4a690-ffffffff81c4b274: sg_ioctl_common (STB_LOCAL)
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
