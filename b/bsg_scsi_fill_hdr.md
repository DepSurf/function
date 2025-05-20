# Function: <code>bsg_scsi_fill_hdr</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a56e0)
Location: block/bsg.c:143
Inline: False
```
**Symbols:**

```
ffffffff814a56e0-ffffffff814a5792: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814c0080)
Location: block/bsg.c:72
Inline: False
```
**Symbols:**

```
ffffffff814c0080-ffffffff814c0132: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff814ee7c0-ffffffff814ee89e: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff814eea7d-ffffffff814eea9a: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff81507c20-ffffffff81507cfe: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff81507edd-ffffffff81507efa: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff81568e60-ffffffff81568f3e: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff8156911d-ffffffff8156913a: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff81583790-ffffffff8158386e: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff81bf3b38-ffffffff81bf3b55: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff8158a5a0-ffffffff8158a678: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff81be5998-ffffffff81be59b5: bsg_scsi_fill_hdr.cold (STB_LOCAL)
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffff80001060a010)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffff80001060a010-ffff80001060a250: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c07b560c)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
c07b560c-c07b576c: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c0000000007a67c0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
c0000000007a67c0-c0000000007a6928: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffe000443a24)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffe000443a24-ffffffe000443b00: bsg_scsi_fill_hdr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff81500200-ffffffff815002de: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff815004bd-ffffffff815004da: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff814f0710-ffffffff814f07ee: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff814f09cd-ffffffff814f09ea: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff814fc290-ffffffff814fc36e: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff814fc54d-ffffffff814fc56a: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bsg_scsi_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:65
Inline: False
```
**Symbols:**

```
ffffffff81515340-ffffffff8151541e: bsg_scsi_fill_hdr (STB_LOCAL)
ffffffff815155fd-ffffffff8151561a: bsg_scsi_fill_hdr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
