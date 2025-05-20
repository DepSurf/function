# Function: <code>bsg_setup_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bsg_setup_queue(struct device *dev, struct request_queue *q, char *name, bsg_job_fn *job_fn, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff813d6c10)
Location: block/bsg-lib.c:211
Inline: False
```
**Symbols:**

```
ffffffff813d6c10-ffffffff813d6c92: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bsg_setup_queue(struct device *dev, struct request_queue *q, char *name, bsg_job_fn *job_fn, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8141c900)
Location: block/bsg-lib.c:211
Inline: False
```
**Symbols:**

```
ffffffff8141c900-ffffffff8141c982: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bsg_setup_queue(struct device *dev, struct request_queue *q, char *name, bsg_job_fn *job_fn, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81437e80)
Location: block/bsg-lib.c:230
Inline: False
```
**Symbols:**

```
ffffffff81437e80-ffffffff81437f02: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, char *name, bsg_job_fn *job_fn, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81445610)
Location: block/bsg-lib.c:242
Inline: False
```
**Symbols:**

```
ffffffff81445610-ffffffff81445701: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, int dd_job_size, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814720d0)
Location: block/bsg-lib.c:255
Inline: False
```
**Symbols:**

```
ffffffff814720d0-ffffffff814721e6: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:307
Inline: False
```
**Symbols:**

```
ffffffff814a6a1f-ffffffff814a6a34: bsg_setup_queue.cold.5 (STB_LOCAL)
ffffffff814a6470-ffffffff814a656b: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:340
Inline: False
```
**Symbols:**

```
ffffffff814c0a4b-ffffffff814c0a6c: bsg_setup_queue.cold.7 (STB_LOCAL)
ffffffff814c0710-ffffffff814c0825: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:360
Inline: False
```
**Symbols:**

```
ffffffff814ef241-ffffffff814ef25d: bsg_setup_queue.cold (STB_LOCAL)
ffffffff814eee20-ffffffff814eef2d: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffff815086e4-ffffffff81508700: bsg_setup_queue.cold (STB_LOCAL)
ffffffff815082d0-ffffffff815083dd: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffff815699e8-ffffffff81569a04: bsg_setup_queue.cold (STB_LOCAL)
ffffffff815697f0-ffffffff815698f8: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:365
Inline: False
```
**Symbols:**

```
ffffffff81bf3b6c-ffffffff81bf3b88: bsg_setup_queue.cold (STB_LOCAL)
ffffffff81584080-ffffffff81584188: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:365
Inline: False
```
**Symbols:**

```
ffffffff81be59cc-ffffffff81be59e8: bsg_setup_queue.cold (STB_LOCAL)
ffffffff8158ae80-ffffffff8158af88: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815efe70)
Location: block/bsg-lib.c:366
Inline: False
```
**Symbols:**

```
ffffffff815efe70-ffffffff815eff87: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff816a0de0)
Location: block/bsg-lib.c:360
Inline: False
```
**Symbols:**

```
ffffffff816a0de0-ffffffff816a0f12: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8175f9a0)
Location: block/bsg-lib.c:361
Inline: False
```
**Symbols:**

```
ffffffff8175f9a0-ffffffff8175fada: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8179e880)
Location: block/bsg-lib.c:361
Inline: False
```
**Symbols:**

```
ffffffff8179e880-ffffffff8179e9bc: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff817e2300)
Location: block/bsg-lib.c:361
Inline: False
```
**Symbols:**

```
ffffffff817e2300-ffffffff817e2467: bsg_setup_queue (STB_GLOBAL)
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
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060ad90)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffff80001060ad90-ffff80001060aed0: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b5d4c)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
c07b5d4c-c07b5e5c: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a78a0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
c0000000007a78a0-c0000000007a7a84: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443fc4)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffe000443fc4-ffffffe0004440d4: bsg_setup_queue (STB_GLOBAL)
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
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffff81500cc4-ffffffff81500ce0: bsg_setup_queue.cold (STB_LOCAL)
ffffffff815008b0-ffffffff815009bd: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
Direct callers:
  - drivers/scsi/scsi_transport_fc.c:fc_remote_port_create
  - drivers/scsi/scsi_transport_fc.c:fc_host_setup
```
**Symbols:**

```
ffffffff814f11d4-ffffffff814f11f0: bsg_setup_queue.cold (STB_LOCAL)
ffffffff814f0dc0-ffffffff814f0ecd: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffff814fcd54-ffffffff814fcd70: bsg_setup_queue.cold (STB_LOCAL)
ffffffff814fc940-ffffffff814fca4d: bsg_setup_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct request_queue *bsg_setup_queue(struct device *dev, const char *name, bsg_job_fn *job_fn, bsg_timeout_fn *timeout, int dd_job_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bsg-lib.c (0)
Location: block/bsg-lib.c:362
Inline: False
```
**Symbols:**

```
ffffffff81515e04-ffffffff81515e20: bsg_setup_queue.cold (STB_LOCAL)
ffffffff815159f0-ffffffff81515afd: bsg_setup_queue (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, q, name, job_fn, dd_job_size</code> ➡️ <code>dev, name, job_fn, dd_job_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>struct request_queue *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*release)(struct device *)</code>
</li>
<li>
<b>Param type changed. </b>
<code>char *name</code> ➡️ <code>const char *name</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void (*release)(struct device *)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bsg_timeout_fn *timeout</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, name, job_fn, dd_job_size</code> ➡️ <code>dev, name, job_fn, timeout, dd_job_size</code>
</li>
</ul>
</details>
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
