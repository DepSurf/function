# Function: <code>fuse_get_unique</code>

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
In fs/fuse/dev.c (ffffffff8130da0f)
Location: fs/fuse/dev.c:327
Inline: True
Inline callers:
  - fs/fuse/dev.c:flush_bg_queue
  - fs/fuse/dev.c:__fuse_request_send
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
In fs/fuse/dev.c (ffffffff8134208c)
Location: fs/fuse/dev.c:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff81357fdc)
Location: fs/fuse/dev.c:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff8136cc3c)
Location: fs/fuse/dev.c:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff813944ec)
Location: fs/fuse/dev.c:307
Inline: True
Inline callers:
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff813c07b8)
Location: fs/fuse/dev.c:320
Inline: True
Inline callers:
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff813d9af8)
Location: fs/fuse/dev.c:362
Inline: True
Inline callers:
  - fs/fuse/dev.c:flush_bg_queue
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
In fs/fuse/dev.c (ffffffff81405681)
Location: fs/fuse/dev.c:364
Inline: True
Inline callers:
  - fs/fuse/dev.c:flush_bg_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81422ce5)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8141f100-ffffffff8141f117: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814703e5)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_read_single_forget
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8146dcd0-ffffffff8146dce7: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148acd7)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_read_single_forget
  - fs/fuse/dev.c:__fuse_request_send
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81488480-ffffffff81488497: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81492048)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8148de70-ffffffff8148de87: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e9b38)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814e58e0-ffffffff814e58f7: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81578355)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff815739f0-ffffffff81573a0d: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161d8e4)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81619030-ffffffff8161904d: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816559f8)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff816510f0-ffffffff8165110d: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168f158)
Location: fs/fuse/dev.c:195
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8168a700-ffffffff8168a71d: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010505afc)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffff800010501378-ffff8000105013a8: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c0634)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
c06be004-c06be038: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c0000000006490b4)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
c000000000645710-c00000000064572c: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe0003723e6)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffe00036e9d2-ffffffe00036e9fa: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141b2c5)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff814176e0-ffffffff814176f7: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140bd45)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81408160-ffffffff81408177: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417465)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff81413880-ffffffff81413897: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 fuse_get_unique(struct fuse_iqueue *fiq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142e1f3)
Location: fs/fuse/dev.c:191
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_request
  - fs/fuse/dev.c:flush_bg_queue
```
**Symbols:**

```
ffffffff8142a6b0-ffffffff8142a6c7: fuse_get_unique (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
