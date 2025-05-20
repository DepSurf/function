# Function: <code>do_iter_readv_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, iter_fn_t fn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120bf60)
Location: fs/read_write.c:679
Inline: True
Direct callers:
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
```
**Symbols:**

```
ffffffff8120bf60-ffffffff8120bffd: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, iter_fn_t fn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81231920)
Location: fs/read_write.c:701
Inline: False
Direct callers:
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
**Symbols:**

```
ffffffff81231920-ffffffff81231a52: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, iter_fn_t fn, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81243ed0)
Location: fs/read_write.c:701
Inline: False
Direct callers:
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
**Symbols:**

```
ffffffff81243ed0-ffffffff81244002: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124f880)
Location: fs/read_write.c:659
Inline: True
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff8124f880-ffffffff8124f9e5: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812717c0)
Location: fs/read_write.c:664
Inline: True
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812717c0-ffffffff81271935: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81297610)
Location: fs/read_write.c:691
Inline: True
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff81297610-ffffffff812977a8: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ac2c0)
Location: fs/read_write.c:691
Inline: True
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812ac2c0-ffffffff812ac47c: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c89c0)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812c89c0-ffffffff812c8b85: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812da3d0)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812da3d0-ffffffff812da595: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81310830)
Location: fs/read_write.c:732
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff81310830-ffffffff813109d8: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131d240)
Location: fs/read_write.c:727
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff8131d240-ffffffff8131d3e5: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813233b0)
Location: fs/read_write.c:725
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff813233b0-ffffffff81323552: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813708a0)
Location: fs/read_write.c:716
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff813708a0-ffffffff81370a45: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813ef430)
Location: fs/read_write.c:727
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff813ef430-ffffffff813ef5cb: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814775a0)
Location: fs/read_write.c:720
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff814775a0-ffffffff814776f3: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814abf20)
Location: fs/read_write.c:720
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_write
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff814abf20-ffffffff814ac076: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814dd2d0)
Location: fs/read_write.c:726
Inline: False
Direct callers:
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_readv
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iter_read
```
**Symbols:**

```
ffffffff814dd2d0-ffffffff814dd494: do_iter_readv_writev (STB_LOCAL)
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
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff80001037f708)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffff80001037f708-ffff80001037f8e0: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0569d64)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
c0569d64-c0569f40: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000475810)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
c000000000475810-c000000000475a98: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe0002553fa)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffe0002553fa-ffffffe000255584: do_iter_readv_writev (STB_LOCAL)
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
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d29b0)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812d29b0-ffffffff812d2b75: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c3630)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812c3630-ffffffff812c37f5: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d07c0)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812d07c0-ffffffff812d0985: do_iter_readv_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t do_iter_readv_writev(struct file *filp, struct iov_iter *iter, loff_t *ppos, int type, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e15f0)
Location: fs/read_write.c:704
Inline: False
Direct callers:
  - fs/read_write.c:do_iter_read
```
**Symbols:**

```
ffffffff812e15f0-ffffffff812e17b5: do_iter_readv_writev (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
<li>
<b>Param removed. </b>
<code>iter_fn_t fn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int flags</code> ➡️ <code>rwf_t flags</code>
</li>
</ul>
</details>
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
