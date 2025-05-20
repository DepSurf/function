# Function: <code>blk_trace_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115bd20)
Location: kernel/trace/blktrace.c:534
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8115bd20-ffffffff8115bd4c: blk_trace_setup.part.19 (STB_LOCAL)
ffffffff8115d1a0-ffffffff8115d24d: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81166610)
Location: kernel/trace/blktrace.c:534
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81166610-ffffffff8116663c: blk_trace_setup.part.21 (STB_LOCAL)
ffffffff81167b20-ffffffff81167bcd: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81171a70)
Location: kernel/trace/blktrace.c:534
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81171a70-ffffffff81171a9c: blk_trace_setup.part.24 (STB_LOCAL)
ffffffff81172f70-ffffffff8117301d: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811748f0)
Location: kernel/trace/blktrace.c:529
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811748f0-ffffffff8117491c: blk_trace_setup.part.19 (STB_LOCAL)
ffffffff81174ca0-ffffffff81174d4d: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811820e0)
Location: kernel/trace/blktrace.c:600
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811820e0-ffffffff81182142: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81191260)
Location: kernel/trace/blktrace.c:600
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81191260-ffffffff811912c2: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119e000)
Location: kernel/trace/blktrace.c:588
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8119e000-ffffffff8119e062: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811abcf0)
Location: kernel/trace/blktrace.c:582
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811abcf0-ffffffff811abd58: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b7550)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811b7550-ffffffff811b75b8: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d0b60)
Location: kernel/trace/blktrace.c:612
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811d0b60-ffffffff811d0bc8: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cdf80)
Location: kernel/trace/blktrace.c:603
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811cdf80-ffffffff811cdfe8: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cf570)
Location: kernel/trace/blktrace.c:600
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811cf570-ffffffff811cf5d5: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fc480)
Location: kernel/trace/blktrace.c:610
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811fc480-ffffffff811fc4e5: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81237e00)
Location: kernel/trace/blktrace.c:610
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81237e00-ffffffff81237e6f: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81283030)
Location: kernel/trace/blktrace.c:642
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81283030-ffffffff8128309f: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8129fce0)
Location: kernel/trace/blktrace.c:642
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff8129fce0-ffffffff8129fd4f: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bb410)
Location: kernel/trace/blktrace.c:642
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff812bb410-ffffffff812bb47f: blk_trace_setup (STB_GLOBAL)
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
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010236f50)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffff800010236f50-ffff800010236fc0: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c047214c)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c047214c-c04721ac: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c26d0)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0000000002c26d0-c0000000002c2754: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018cec0)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffe00018cec0-ffffffe00018cf20: blk_trace_setup (STB_GLOBAL)
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
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811afb70)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811afb70-ffffffff811afbd8: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a29c0)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811a29c0-ffffffff811a2a28: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ad940)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811ad940-ffffffff811ad9a8: blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, char *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bb810)
Location: kernel/trace/blktrace.c:583
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811bb810-ffffffff811bb878: blk_trace_setup (STB_GLOBAL)
```
</details>
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
