# Function: <code>do_splice_direct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123de10)
Location: fs/splice.c:1312
Inline: False
Direct callers:
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8123de10-ffffffff8123ded4: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81265ee0)
Location: fs/splice.c:1316
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81265ee0-ffffffff81265fa4: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279870)
Location: fs/splice.c:1060
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81279870-ffffffff81279934: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81286dd0)
Location: fs/splice.c:1056
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81286dd0-ffffffff81286e92: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a95c0)
Location: fs/splice.c:1040
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff812a95c0-ffffffff812a9682: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812d0100)
Location: fs/splice.c:1041
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff812d0100-ffffffff812d01c2: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812e5540)
Location: fs/splice.c:1045
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff812e5540-ffffffff812e5602: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81303d50)
Location: fs/splice.c:1042
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81303d50-ffffffff81303e14: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81316dd0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81316dd0-ffffffff81316e94: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81352160)
Location: fs/splice.c:1038
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81352160-ffffffff81352224: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135d1e0)
Location: fs/splice.c:955
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8135d1e0-ffffffff8135d2a4: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81363c80)
Location: fs/splice.c:956
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff81363c80-ffffffff81363d44: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b2470)
Location: fs/splice.c:958
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff813b2470-ffffffff813b2534: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814374a0)
Location: fs/splice.c:954
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff814374a0-ffffffff81437578: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c55a0)
Location: fs/splice.c:953
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff814c55a0-ffffffff814c5678: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fadb0)
Location: fs/splice.c:1173
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff814fadb0-ffffffff814fae90: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8152f980)
Location: fs/splice.c:1230
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8152f980-ffffffff8152fa39: do_splice_direct (STB_GLOBAL)
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
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffff8000103cd7a0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffff8000103cd7a0-ffff8000103cd894: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c05a9380)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
c05a9380-c05a946c: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (c0000000004cf7c0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
c0000000004cf7c0-c0000000004cf8ec: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffe00028aa92)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffe00028aa92-ffffffe00028ab42: do_splice_direct (STB_GLOBAL)
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
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130f3b0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8130f3b0-ffffffff8130f474: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812fffc0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff812fffc0-ffffffff81300084: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8130d1a0)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8130d1a0-ffffffff8130d264: do_splice_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int do_splice_direct(struct file *in, loff_t *ppos, struct file *out, loff_t *opos, size_t len, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8131e990)
Location: fs/splice.c:1043
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
```
**Symbols:**

```
ffffffff8131e990-ffffffff8131ea54: do_splice_direct (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
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
