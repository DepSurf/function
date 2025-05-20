# Function: <code>sg_new_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff815c3120)
Location: drivers/scsi/sg.c:546
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_read
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff815c3120-ffffffff815c3213: sg_new_read.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161b900)
Location: drivers/scsi/sg.c:546
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff8161b900-ffffffff8161ba32: sg_new_read.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164c560)
Location: drivers/scsi/sg.c:535
Inline: True
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff8164c560-ffffffff8164c692: sg_new_read.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81661850)
Location: drivers/scsi/sg.c:535
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81661850-ffffffff816619dd: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816ca9b0)
Location: drivers/scsi/sg.c:535
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff816ca9b0-ffffffff816cab3d: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff817072a0)
Location: drivers/scsi/sg.c:570
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff817072a0-ffffffff8170742d: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81729de0)
Location: drivers/scsi/sg.c:570
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81729de0-ffffffff81729f6d: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81765490)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81765490-ffffffff81765626: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81789480)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81789480-ffffffff81789616: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184e450)
Location: drivers/scsi/sg.c:559
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff8184e450-ffffffff8184e610: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185e1d0)
Location: drivers/scsi/sg.c:559
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff8185e1d0-ffffffff8185e390: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818411f0)
Location: drivers/scsi/sg.c:559
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff818411f0-ffffffff818413ab: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff818cde80)
Location: drivers/scsi/sg.c:562
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff818cde80-ffffffff818ce04b: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81a1b480)
Location: drivers/scsi/sg.c:558
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81a1b480-ffffffff81a1b635: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81b9c5e0)
Location: drivers/scsi/sg.c:558
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81b9c5e0-ffffffff81b9c795: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81bf2bc0)
Location: drivers/scsi/sg.c:558
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81bf2bc0-ffffffff81bf2d74: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81c484b0)
Location: drivers/scsi/sg.c:558
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
**Symbols:**

```
ffffffff81c484b0-ffffffff81c48664: sg_new_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffff800010992e38)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffff800010992e38-ffff800010993230: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a6285c)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0a6285c-c0a62a4c: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a52840)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c000000000a52840-c000000000a52aa0: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f441c)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffe0005f441c-ffffffe0005f456c: sg_new_read (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173db70)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8173db70-ffffffff8173dd06: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8171f810)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8171f810-ffffffff8171f9a6: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177e300)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8177e300-ffffffff8177e496: sg_new_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t sg_new_read(Sg_fd *sfp, char *buf, size_t count, Sg_request *srp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81798110)
Location: drivers/scsi/sg.c:565
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81798110-ffffffff817982a6: sg_new_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
