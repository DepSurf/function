# Function: <code>scsi_cmd_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff813cc5b0)
Location: block/scsi_ioctl.c:562
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff813cc5b0-ffffffff813cc9cc: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81410900)
Location: block/scsi_ioctl.c:562
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81410900-ffffffff81410d22: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff8142bc90)
Location: block/scsi_ioctl.c:565
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff8142bc90-ffffffff8142c0b2: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff81443a50)
Location: block/scsi_ioctl.c:563
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81443a50-ffffffff81443e81: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffff814704e0)
Location: block/scsi_ioctl.c:563
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814704e0-ffffffff81470911: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:559
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814a4b91-ffffffff814a4bdc: scsi_cmd_ioctl.cold.12 (STB_LOCAL)
ffffffff814a4740-ffffffff814a4b2b: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:559
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814bf651-ffffffff814bf69c: scsi_cmd_ioctl.cold.12 (STB_LOCAL)
ffffffff814bf200-ffffffff814bf5eb: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814edea1-ffffffff814edeed: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff814eda50-ffffffff814ede36: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81507311-ffffffff8150735d: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff81506ec0-ffffffff815072a6: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:776
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81568447-ffffffff8156849c: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff81567d90-ffffffff81568024: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:767
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81bf3ae3-ffffffff81bf3b38: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff81582af0-ffffffff81582d85: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:763
Inline: False
Direct callers:
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81be5943-ffffffff81be5998: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff81589930-ffffffff81589bb6: scsi_cmd_ioctl (STB_GLOBAL)
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
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffff800010608c08)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffff800010608c08-ffff80001060966c: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c07b459c)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
c07b459c-c07b4b80: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (c0000000007a53a0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
c0000000007a53a0-c0000000007a5b68: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/scsi_ioctl.c (ffffffe000442c00)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffe000442c00-ffffffe000442fe2: scsi_cmd_ioctl (STB_GLOBAL)
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
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814ff8f1-ffffffff814ff93d: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff814ff4a0-ffffffff814ff886: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814efe01-ffffffff814efe4d: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff814ef9b0-ffffffff814efd96: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff814fb981-ffffffff814fb9cd: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff814fb530-ffffffff814fb916: scsi_cmd_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int scsi_cmd_ioctl(struct request_queue *q, struct gendisk *bd_disk, fmode_t mode, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/scsi_ioctl.c (0)
Location: block/scsi_ioctl.c:545
Inline: False
Direct callers:
  - block/scsi_ioctl.c:scsi_cmd_blk_ioctl
  - block/bsg.c:bsg_ioctl
```
**Symbols:**

```
ffffffff81514a31-ffffffff81514a7d: scsi_cmd_ioctl.cold (STB_LOCAL)
ffffffff815145e0-ffffffff815149c6: scsi_cmd_ioctl (STB_GLOBAL)
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
