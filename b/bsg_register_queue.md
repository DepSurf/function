# Function: <code>bsg_register_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d54d0)
Location: block/bsg.c:974
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff813d54d0-ffffffff813d56b1: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141b190)
Location: block/bsg.c:974
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff8141b190-ffffffff8141b371: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814366d0)
Location: block/bsg.c:977
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff814366d0-ffffffff814368b1: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81443f30)
Location: block/bsg.c:976
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81443f30-ffffffff8144410a: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81470ca0)
Location: block/bsg.c:967
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81470ca0-ffffffff81470eb2: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bsg.c (ffffffff814a5388)
Location: block/bsg.c:900
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff814a5200-ffffffff814a5358: bsg_register_queue.part.16 (STB_LOCAL)
ffffffff814a6337-ffffffff814a634e: bsg_register_queue.part.16.cold.21 (STB_LOCAL)
ffffffff814a6310-ffffffff814a6337: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:467
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff814c0336-ffffffff814c034d: bsg_register_queue.cold.12 (STB_LOCAL)
ffffffff814c0140-ffffffff814c02b4: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff814eea9a-ffffffff814eeab1: bsg_register_queue.cold (STB_LOCAL)
ffffffff814ee8a0-ffffffff814eea17: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff81507efa-ffffffff81507f11: bsg_register_queue.cold (STB_LOCAL)
ffffffff81507d00-ffffffff81507e77: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:407
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff8156913a-ffffffff81569151: bsg_register_queue.cold (STB_LOCAL)
ffffffff81568f40-ffffffff815690b4: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:409
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff81bf3b55-ffffffff81bf3b6c: bsg_register_queue.cold (STB_LOCAL)
ffffffff81583870-ffffffff815839e7: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:409
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff81be59b5-ffffffff81be59cc: bsg_register_queue.cold (STB_LOCAL)
ffffffff8158a680-ffffffff8158a7f7: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bsg_device *bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, bsg_sg_io_fn *sg_io_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:185
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue
```
**Symbols:**

```
ffffffff81cd9beb-ffffffff81cd9bff: bsg_register_queue.cold (STB_LOCAL)
ffffffff815ef310-ffffffff815ef49b: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bsg_device *bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, bsg_sg_io_fn *sg_io_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:185
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue
```
**Symbols:**

```
ffffffff81e8d6bb-ffffffff81e8d6cf: bsg_register_queue.cold (STB_LOCAL)
ffffffff816a02c0-ffffffff816a044f: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bsg_device *bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, bsg_sg_io_fn *sg_io_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8175ed90)
Location: block/bsg.c:187
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue
```
**Symbols:**

```
ffffffff8175ed90-ffffffff8175ef38: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bsg_device *bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, bsg_sg_io_fn *sg_io_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8179dc90)
Location: block/bsg.c:189
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue
```
**Symbols:**

```
ffffffff8179dc90-ffffffff8179de35: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bsg_device *bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, bsg_sg_io_fn *sg_io_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff817e16e0)
Location: block/bsg.c:189
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
  - drivers/scsi/scsi_bsg.c:scsi_bsg_register_queue
```
**Symbols:**

```
ffffffff817e16e0-ffffffff817e18b2: bsg_register_queue (STB_GLOBAL)
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
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffff80001060a8a8)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffff80001060a8a8-ffff80001060aa24: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c07b576c)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
c07b576c-c07b58d0: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (c0000000007a6bf0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
c0000000007a6bf0-c0000000007a6de0: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bsg.c (ffffffe000443858)
Location: block/bsg.c:406
Inline: True
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffe000443858-ffffffe00044399e: bsg_register_queue.part.0 (STB_LOCAL)
ffffffe000443b00-ffffffe000443b48: bsg_register_queue (STB_GLOBAL)
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
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff815004da-ffffffff815004f1: bsg_register_queue.cold (STB_LOCAL)
ffffffff815002e0-ffffffff81500457: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff814f09ea-ffffffff814f0a01: bsg_register_queue.cold (STB_LOCAL)
ffffffff814f07f0-ffffffff814f0967: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff814fc56a-ffffffff814fc581: bsg_register_queue.cold (STB_LOCAL)
ffffffff814fc370-ffffffff814fc4e7: bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int bsg_register_queue(struct request_queue *q, struct device *parent, const char *name, const struct bsg_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg.c (0)
Location: block/bsg.c:406
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_setup_queue
```
**Symbols:**

```
ffffffff8151561a-ffffffff81515631: bsg_register_queue.cold (STB_LOCAL)
ffffffff81515420-ffffffff81515597: bsg_register_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bsg_ops *ops</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*release)(struct device *)</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bsg_sg_io_fn *sg_io_fn</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct bsg_ops *ops</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct bsg_device *</code>
</li>
</ul>
</details>
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
