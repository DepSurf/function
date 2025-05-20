# Function: <code>percpu_ref_resurrect</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff814e04e0)
Location: lib/percpu-refcount.c:379
Inline: False
Direct callers:
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff814e04e0-ffffffff814e054a: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8150c480)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8150c480-ffffffff8150c4f0: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8152a2d0)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8152a2d0-ffffffff8152a340: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8158d9f0)
Location: lib/percpu-refcount.c:390
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8158d9f0-ffffffff8158da60: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815aa670)
Location: lib/percpu-refcount.c:455
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_files_unregister
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff815aa670-ffffffff815aa6e5: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815b5290)
Location: lib/percpu-refcount.c:461
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff815b5290-ffffffff815b5305: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8161b630)
Location: lib/percpu-refcount.c:461
Inline: False
Direct callers:
  - mm/swapfile.c:enable_swap_info
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:__io_uring_register
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8161b630-ffffffff8161b6a5: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff816e8e40)
Location: lib/percpu-refcount.c:462
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff816e8e40-ffffffff816e8ebf: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff817d8f00)
Location: lib/percpu-refcount.c:463
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff817d8f00-ffffffff817d8f7f: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81818110)
Location: lib/percpu-refcount.c:463
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff81818110-ffffffff8181818f: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8185d410)
Location: lib/percpu-refcount.c:463
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - lib/percpu-refcount.c:percpu_ref_reinit
  - drivers/md/md.c:__mddev_resume
  - drivers/md/md.c:mddev_suspend
```
**Symbols:**

```
ffffffff8185d410-ffffffff8185d48f: percpu_ref_resurrect (STB_GLOBAL)
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
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffff8000106355d8)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffff8000106355d8-ffff8000106356f8: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c07db44c)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
c07db44c-c07db55c: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (c0000000007dad50)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
c0000000007dad50-c0000000007dae7c: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffe000462e10)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffe000462e10-ffffffe000462ea8: percpu_ref_resurrect (STB_GLOBAL)
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
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815228b0)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff815228b0-ffffffff81522920: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff81512b90)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff81512b90-ffffffff81512c00: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff8151e940)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff8151e940-ffffffff8151e9b0: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void percpu_ref_resurrect(struct percpu_ref *ref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu-refcount.c (ffffffff815381e0)
Location: lib/percpu-refcount.c:389
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_unfreeze_queue
  - lib/percpu-refcount.c:percpu_ref_reinit
```
**Symbols:**

```
ffffffff815381e0-ffffffff81538267: percpu_ref_resurrect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
