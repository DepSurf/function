# Function: <code>blk_fill_sghdr_rq</code>

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
In block/scsi_ioctl.c (ffffffff813cbd76)
Location: block/scsi_ioctl.c:230
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
In block/scsi_ioctl.c (ffffffff81410595)
Location: block/scsi_ioctl.c:230
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
In block/scsi_ioctl.c (ffffffff8142b925)
Location: block/scsi_ioctl.c:233
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
In block/scsi_ioctl.c (ffffffff81443719)
Location: block/scsi_ioctl.c:233
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
In block/scsi_ioctl.c (ffffffff814701a9)
Location: block/scsi_ioctl.c:233
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
In block/scsi_ioctl.c (ffffffff814a43fc)
Location: block/scsi_ioctl.c:230
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
In block/scsi_ioctl.c (ffffffff814bee41)
Location: block/scsi_ioctl.c:230
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
In block/scsi_ioctl.c (ffffffff814ed3e6)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffff81506826)
Location: block/scsi_ioctl.c:216
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
int blk_fill_sghdr_rq(struct request_queue *q, struct request *rq, struct sg_io_hdr *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81567430)
Location: block/scsi_ioctl.c:222
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
```
**Symbols:**

```
ffffffff81567430-ffffffff81567518: blk_fill_sghdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_fill_sghdr_rq(struct request_queue *q, struct request *rq, struct sg_io_hdr *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff815821d0)
Location: block/scsi_ioctl.c:220
Inline: False
Direct callers:
  - block/scsi_ioctl.c:sg_io
```
**Symbols:**

```
ffffffff815821d0-ffffffff815822b8: blk_fill_sghdr_rq (STB_LOCAL)
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
In block/scsi_ioctl.c (ffffffff81589309)
Location: block/scsi_ioctl.c:220
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
In block/scsi_ioctl.c (ffff800010607f64)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (c07b3d44)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (c0000000007a49b4)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffe000442678)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffff814fee06)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffff814ef316)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffff814fae96)
Location: block/scsi_ioctl.c:216
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
In block/scsi_ioctl.c (ffffffff81513f46)
Location: block/scsi_ioctl.c:216
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
