# Function: <code>fuse_dequeue_forget</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814203f0)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff8141f260-ffffffff8141f2e8: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146f155)
Location: fs/fuse/dev.c:1050
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_read_single_forget
```
**Symbols:**

```
ffffffff8146de30-ffffffff8146dec4: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814898b5)
Location: fs/fuse/dev.c:1071
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_read_single_forget
```
**Symbols:**

```
ffffffff814885e0-ffffffff81488674: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148f135)
Location: fs/fuse/dev.c:1068
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff8148dfd0-ffffffff8148e060: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e6ba5)
Location: fs/fuse/dev.c:1084
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff814e5a40-ffffffff814e5ad0: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81573b70)
Location: fs/fuse/dev.c:1076
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff81573b70-ffffffff81573c0f: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816191e0)
Location: fs/fuse/dev.c:1077
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff816191e0-ffffffff8161927f: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81652a2e)
Location: fs/fuse/dev.c:1079
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff816512a0-ffffffff8165133f: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168c03e)
Location: fs/fuse/dev.c:1079
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff8168a8b0-ffffffff8168a94f: fuse_dequeue_forget (STB_GLOBAL)
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
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010501438)
Location: fs/fuse/dev.c:1051
Inline: True
```
**Symbols:**

```
ffff800010501438-ffff800010501500: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c0678)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
```
**Symbols:**

```
c06be15c-c06be228: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c0000000006490c8)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
  - fs/fuse/dev.c:fuse_dev_do_read
```
**Symbols:**

```
c000000000645960-c000000000645a3c: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe00036fcf0)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffe00036eb18-ffffffe00036eb9a: fuse_dequeue_forget (STB_GLOBAL)
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
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814189d0)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff81417840-ffffffff814178c8: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409450)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff814082c0-ffffffff81408348: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81414b70)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff814139e0-ffffffff81413a68: fuse_dequeue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct fuse_forget_link *fuse_dequeue_forget(struct fuse_iqueue *fiq, unsigned int max, unsigned int *countp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142b3dd)
Location: fs/fuse/dev.c:1051
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_abort_conn
```
**Symbols:**

```
ffffffff8142a810-ffffffff8142a898: fuse_dequeue_forget (STB_GLOBAL)
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
