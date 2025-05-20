# Function: <code>blk_complete_sgv4_hdr_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d56c0)
Location: block/bsg.c:393
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_read
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff813d56c0-ffffffff813d583d: blk_complete_sgv4_hdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141b380)
Location: block/bsg.c:393
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_read
```
**Symbols:**

```
ffffffff8141b380-ffffffff8141b538: blk_complete_sgv4_hdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814368c0)
Location: block/bsg.c:393
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_read
```
**Symbols:**

```
ffffffff814368c0-ffffffff81436a71: blk_complete_sgv4_hdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81444110)
Location: block/bsg.c:387
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_read
```
**Symbols:**

```
ffffffff81444110-ffffffff814442be: blk_complete_sgv4_hdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814709c0)
Location: block/bsg.c:387
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_read
```
**Symbols:**

```
ffffffff814709c0-ffffffff81470b6e: blk_complete_sgv4_hdr_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_complete_sgv4_hdr_rq(struct request *rq, struct sg_io_v4 *hdr, struct bio *bio, struct bio *bidi_bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a4d90)
Location: block/bsg.c:383
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_read
```
**Symbols:**

```
ffffffff814a4d90-ffffffff814a4e0f: blk_complete_sgv4_hdr_rq (STB_LOCAL)
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
In block/bsg.c (ffffffff814bfc1e)
Location: block/bsg.c:221
Inline: True
Inline callers:
  - block/bsg.c:bsg_ioctl
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
