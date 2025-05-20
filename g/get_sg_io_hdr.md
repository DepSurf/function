# Function: <code>get_sg_io_hdr</code>

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
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567340)
Location: block/scsi_ioctl.c:601
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff81567340-ffffffff8156742a: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81581d00)
Location: block/scsi_ioctl.c:591
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff81581d00-ffffffff81581dea: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81588d40)
Location: block/scsi_ioctl.c:587
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_ioctl
```
**Symbols:**

```
ffffffff81588d40-ffffffff81588e2a: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff818ae8a0)
Location: drivers/scsi/scsi_ioctl.c:690
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff818ae8a0-ffffffff818ae98a: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff819f9400)
Location: drivers/scsi/scsi_ioctl.c:673
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff819f9400-ffffffff819f94f3: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81b772c0)
Location: drivers/scsi/scsi_ioctl.c:657
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81b772c0-ffffffff81b773b3: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81bcaf20)
Location: drivers/scsi/scsi_ioctl.c:660
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81bcaf20-ffffffff81bcb013: get_sg_io_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_sg_io_hdr(struct sg_io_hdr *hdr, const void *argp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_ioctl.c (ffffffff81c1fb50)
Location: drivers/scsi/scsi_ioctl.c:660
Inline: False
Direct callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl
```
**Symbols:**

```
ffffffff81c1fb50-ffffffff81c1fc43: get_sg_io_hdr (STB_GLOBAL)
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
