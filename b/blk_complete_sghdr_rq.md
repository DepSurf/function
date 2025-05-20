# Function: <code>blk_complete_sghdr_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff813cbe78)
Location: block/scsi_ioctl.c:254
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814106ba)
Location: block/scsi_ioctl.c:254
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8142ba4a)
Location: block/scsi_ioctl.c:257
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814437fc)
Location: block/scsi_ioctl.c:259
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81470289)
Location: block/scsi_ioctl.c:259
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814a44e6)
Location: block/scsi_ioctl.c:256
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814bef33)
Location: block/scsi_ioctl.c:256
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ed4d9)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81506919)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_complete_sghdr_rq(struct request *rq, struct sg_io_hdr *hdr, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567520)
Location: block/scsi_ioctl.c:248
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
```
**Symbols:**

```
ffffffff81567520-ffffffff8156762a: blk_complete_sghdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_complete_sghdr_rq(struct request *rq, struct sg_io_hdr *hdr, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815822c0)
Location: block/scsi_ioctl.c:246
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
```
**Symbols:**

```
ffffffff815822c0-ffffffff815823ca: blk_complete_sghdr_rq (STB_LOCAL)
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
In block/scsi_ioctl.c (ffffffff815893f1)
Location: block/scsi_ioctl.c:246
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010608010)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b3e58)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a4a94)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe000442724)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814feef9)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814ef409)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814faf89)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81514039)
Location: block/scsi_ioctl.c:242
Inline: True
Inline callers:
  - block/scsi_ioctl.c:sg_io
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
