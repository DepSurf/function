# Function: <code>do_blk_trace_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115ced0)
Location: kernel/trace/blktrace.c:436
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff8115ced0-ffffffff8115d191: do_blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81167850)
Location: kernel/trace/blktrace.c:436
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff81167850-ffffffff81167b18: do_blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81172ca0)
Location: kernel/trace/blktrace.c:436
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff81172ca0-ffffffff81172f68: do_blk_trace_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811749b0)
Location: kernel/trace/blktrace.c:435
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
```
**Symbols:**

```
ffffffff811749b0-ffffffff81174c9f: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81181d50)
Location: kernel/trace/blktrace.c:486
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff81181d50-ffffffff8118202e: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81190ef0)
Location: kernel/trace/blktrace.c:486
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff81190ef0-ffffffff811911ac: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119db90)
Location: kernel/trace/blktrace.c:474
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff8119db90-ffffffff8119de64: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ab880)
Location: kernel/trace/blktrace.c:474
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811ab880-ffffffff811abb48: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b70e0)
Location: kernel/trace/blktrace.c:475
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811b70e0-ffffffff811b73a8: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:478
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811d06e0-ffffffff811d09a2: do_blk_trace_setup (STB_LOCAL)
ffffffff811d268a-ffffffff811d26be: do_blk_trace_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:473
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811cdb20-ffffffff811cddcd: do_blk_trace_setup (STB_LOCAL)
ffffffff81be5d7e-ffffffff81be5db2: do_blk_trace_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:472
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811cf1c0-ffffffff811cf4a6: do_blk_trace_setup (STB_LOCAL)
ffffffff81bd7b97-ffffffff81bd7bd0: do_blk_trace_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:482
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811fb820-ffffffff811fbac4: do_blk_trace_setup (STB_LOCAL)
ffffffff81cb60a9-ffffffff81cb60dd: do_blk_trace_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:482
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff81235b20-ffffffff81235dd7: do_blk_trace_setup (STB_LOCAL)
ffffffff81e670c5-ffffffff81e670f7: do_blk_trace_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81282560)
Location: kernel/trace/blktrace.c:514
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff81282560-ffffffff81282817: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8129f200)
Location: kernel/trace/blktrace.c:514
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff8129f200-ffffffff8129f4b4: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff812ba8e0)
Location: kernel/trace/blktrace.c:514
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff812ba8e0-ffffffff812babc3: do_blk_trace_setup (STB_LOCAL)
```
</details>
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
In kernel/trace/blktrace.c (ffff800010236b24)
Location: kernel/trace/blktrace.c:475
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
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
In kernel/trace/blktrace.c (c0471d94)
Location: kernel/trace/blktrace.c:475
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
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
In kernel/trace/blktrace.c (c0000000002c22e0)
Location: kernel/trace/blktrace.c:475
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
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
In kernel/trace/blktrace.c (ffffffe00018cc7c)
Location: kernel/trace/blktrace.c:475
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:__blk_trace_setup
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
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811af700)
Location: kernel/trace/blktrace.c:475
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811af700-ffffffff811af9c8: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a2550)
Location: kernel/trace/blktrace.c:475
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811a2550-ffffffff811a2818: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ad4d0)
Location: kernel/trace/blktrace.c:475
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811ad4d0-ffffffff811ad798: do_blk_trace_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_blk_trace_setup(struct request_queue *q, char *name, dev_t dev, struct block_device *bdev, struct blk_user_trace_setup *buts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bb3a0)
Location: kernel/trace/blktrace.c:475
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:compat_blk_trace_setup
  - kernel/trace/blktrace.c:__blk_trace_setup
```
**Symbols:**

```
ffffffff811bb3a0-ffffffff811bb668: do_blk_trace_setup (STB_LOCAL)
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
