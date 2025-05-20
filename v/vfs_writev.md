# Function: <code>vfs_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120cc40)
Location: fs/read_write.c:863
Inline: False
Direct callers:
  - fs/read_write.c:SyS_writev
  - fs/read_write.c:SyS_pwritev
```
**Symbols:**

```
ffffffff8120cc40-ffffffff8120cc84: vfs_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233230)
Location: fs/read_write.c:898
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81233230-ffffffff81233277: vfs_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81245db0)
Location: fs/read_write.c:927
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81245db0-ffffffff81245df7: vfs_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251640)
Location: fs/read_write.c:988
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81251640-ffffffff8125174b: vfs_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272fb0)
Location: fs/read_write.c:992
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81272fb0-ffffffff812730bb: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299070)
Location: fs/read_write.c:1019
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81299070-ffffffff81299161: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812adef0)
Location: fs/read_write.c:1016
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812adef0-ffffffff812adfe1: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cab80)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812cab80-ffffffff812cac6f: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc5a0)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812dc5a0-ffffffff812dc68f: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313370)
Location: fs/read_write.c:1114
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81313370-ffffffff8131346a: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8131ec90)
Location: fs/read_write.c:930
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff8131ec90-ffffffff8131edd3: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813246d0)
Location: fs/read_write.c:928
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff813246d0-ffffffff81324809: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81372310)
Location: fs/read_write.c:919
Inline: False
Direct callers:
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81372310-ffffffff81372449: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f03d0)
Location: fs/read_write.c:930
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff813f03d0-ffffffff813f057b: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81478770)
Location: fs/read_write.c:923
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff81478770-ffffffff8147891b: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ad1c0)
Location: fs/read_write.c:922
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff814ad1c0-ffffffff814ad374: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814de9d0)
Location: fs/read_write.c:942
Inline: False
Direct callers:
  - fs/read_write.c:__ia32_sys_pwritev
  - fs/read_write.c:__x64_sys_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff814de9d0-ffffffff814ded00: vfs_writev (STB_LOCAL)
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
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381fb0)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffff800010381fb0-ffff8000103820bc: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056c388)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
c056c388-c056c480: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c0000000004785a0)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
c0000000004785a0-c000000000478714: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000256ace)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffe000256ace-ffffffe000256b94: vfs_writev (STB_LOCAL)
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
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4b80)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812d4b80-ffffffff812d4c6f: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5800)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812c5800-ffffffff812c58ef: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2990)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812d2990-ffffffff812d2a7f: vfs_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_writev(struct file *file, const struct iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e37f0)
Location: fs/read_write.c:1030
Inline: False
Direct callers:
  - fs/read_write.c:do_pwritev
  - fs/read_write.c:do_writev
  - fs/read_write.c:do_writev
```
**Symbols:**

```
ffffffff812e37f0-ffffffff812e38df: vfs_writev (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
