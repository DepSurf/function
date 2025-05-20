# Function: <code>do_loop_readv_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, io_fn_t fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bc20)
Location: fs/read_write.c:695
Inline: False
Direct callers:
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
```
**Symbols:**

```
ffffffff8120bc20-ffffffff8120bcb7: do_loop_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, io_fn_t fn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231a60)
Location: fs/read_write.c:726
Inline: False
Direct callers:
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
**Symbols:**

```
ffffffff81231a60-ffffffff81231b06: do_loop_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_loop_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, io_fn_t fn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244010)
Location: fs/read_write.c:726
Inline: False
Direct callers:
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
**Symbols:**

```
ffffffff81244010-ffffffff812440b6: do_loop_readv_writev (STB_LOCAL)
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
In fs/read_write.c (ffffffff81250eb3)
Location: fs/read_write.c:681
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffff81272ab3)
Location: fs/read_write.c:686
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffff812989a1)
Location: fs/read_write.c:713
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffff812ad822)
Location: fs/read_write.c:713
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffff812ca4a2)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbec2)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff813132f3)
Location: fs/read_write.c:755
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff81310a20-ffffffff81310ae3: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff8131ebf1)
Location: fs/read_write.c:750
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff8131ca80-ffffffff8131cb43: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81324631)
Location: fs/read_write.c:748
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff81322bf0-ffffffff81322cb6: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81372271)
Location: fs/read_write.c:739
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff813700e0-ffffffff813701a6: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff813f031a)
Location: fs/read_write.c:750
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff813eebb0-ffffffff813eec83: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff8147869a)
Location: fs/read_write.c:743
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff814774b0-ffffffff81477583: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff814ad0d5)
Location: fs/read_write.c:743
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff814abe30-ffffffff814abf0c: do_loop_readv_writev.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff814debb0)
Location: fs/read_write.c:749
Inline: True
Inline callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
```
**Symbols:**

```
ffffffff814dd1e0-ffffffff814dd2bb: do_loop_readv_writev.part.0 (STB_LOCAL)
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
In fs/read_write.c (ffff800010381940)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (c056c0d0)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (c000000000477dc0)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
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
In fs/read_write.c (ffffffe000256884)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d44a2)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5122)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d22b2)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3112)
Location: fs/read_write.c:727
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_read
  - fs/read_write.c:do_iter_read
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
