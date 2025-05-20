# Function: <code>blk_trace_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115ae90)
Location: kernel/trace/blktrace.c:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:blk_trace_shutdown
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8115ae90-ffffffff8115aebe: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81167e69)
Location: kernel/trace/blktrace.c:316
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81165770-ffffffff8116579e: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811732b9)
Location: kernel/trace/blktrace.c:316
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81170bd0-ffffffff81170bfe: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81176129)
Location: kernel/trace/blktrace.c:315
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_shutdown
  - kernel/trace/blktrace.c:blk_trace_ioctl
  - kernel/trace/blktrace.c:compat_blk_trace_setup
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81173c60-ffffffff81173c8e: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81180e60)
Location: kernel/trace/blktrace.c:369
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81180e60-ffffffff81180e94: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81190000)
Location: kernel/trace/blktrace.c:369
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff81190000-ffffffff81190034: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119d810)
Location: kernel/trace/blktrace.c:357
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff8119d810-ffffffff8119d844: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ab550)
Location: kernel/trace/blktrace.c:357
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811ab550-ffffffff811ab586: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b6d50)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811b6d50-ffffffff811b6d86: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d0a60)
Location: kernel/trace/blktrace.c:361
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811d0a60-ffffffff811d0a96: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cde80)
Location: kernel/trace/blktrace.c:361
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811cde80-ffffffff811cdeb6: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cf120)
Location: kernel/trace/blktrace.c:360
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811cf120-ffffffff811cf1b4: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811fc140)
Location: kernel/trace/blktrace.c:370
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff811fc140-ffffffff811fc1b3: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81236440)
Location: kernel/trace/blktrace.c:370
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff81236440-ffffffff812364b2: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812830b0)
Location: kernel/trace/blktrace.c:402
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff812830b0-ffffffff81283166: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8129fd60)
Location: kernel/trace/blktrace.c:402
Inline: False
Direct callers:
  - block/genhd.c:disk_release
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff8129fd60-ffffffff8129fe16: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812bb490)
Location: kernel/trace/blktrace.c:402
Inline: False
Direct callers:
  - block/genhd.c:disk_release
  - drivers/scsi/sg.c:sg_device_destroy
  - drivers/scsi/sg.c:sg_ioctl_common
```
**Symbols:**

```
ffffffff812bb490-ffffffff812bb546: blk_trace_remove (STB_GLOBAL)
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
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010235c88)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffff800010235c88-ffff800010235cc8: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0471cc4)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0471cc4-c0471cfc: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c0580)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
c0000000002c0580-c0000000002c05e4: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018c63e)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffe00018c63e-ffffffe00018c67e: blk_trace_remove (STB_GLOBAL)
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
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811af370)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811af370-ffffffff811af3a6: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a21c0)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811a21c0-ffffffff811a21f6: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ad140)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811ad140-ffffffff811ad176: blk_trace_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_trace_remove(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bb010)
Location: kernel/trace/blktrace.c:358
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_ioctl
```
**Symbols:**

```
ffffffff811bb010-ffffffff811bb046: blk_trace_remove (STB_GLOBAL)
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
