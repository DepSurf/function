# Function: <code>put_sg_io_hdr</code>

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
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567270)
Location: block/scsi_ioctl.c:558
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81567270-ffffffff8156733c: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81582100)
Location: block/scsi_ioctl.c:548
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81582100-ffffffff815821cc: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81588e30)
Location: block/scsi_ioctl.c:544
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81588e30-ffffffff81588f06: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff818ae7c0)
Location: drivers/scsi/scsi_ioctl.c:647
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff818ae7c0-ffffffff818ae896: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff819f9330)
Location: drivers/scsi/scsi_ioctl.c:630
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff819f9330-ffffffff819f9400: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81b77460)
Location: drivers/scsi/scsi_ioctl.c:614
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81b77460-ffffffff81b77530: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb1d0)
Location: drivers/scsi/scsi_ioctl.c:617
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81bcb1d0-ffffffff81bcb2a0: put_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int put_sg_io_hdr(const struct sg_io_hdr *hdr, void *argp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81c1fe00)
Location: drivers/scsi/scsi_ioctl.c:617
Inline: True
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
  - drivers/scsi/sg.c:sg_new_read
```
**Symbols:**

```
ffffffff81c1fe00-ffffffff81c1fed0: put_sg_io_hdr (STB_GLOBAL)
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
