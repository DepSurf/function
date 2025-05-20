# Function: <code>compat_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120cfd0)
Location: fs/read_write.c:1101
Inline: False
Direct callers:
  - fs/read_write.c:__compat_sys_pwritev64
  - fs/read_write.c:compat_SyS_writev
```
**Symbols:**

```
ffffffff8120cfd0-ffffffff8120d03a: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81233860)
Location: fs/read_write.c:1217
Inline: True
```
**Symbols:**

```
ffffffff81233860-ffffffff812338cd: compat_writev.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff812463f0)
Location: fs/read_write.c:1246
Inline: True
```
**Symbols:**

```
ffffffff812463f0-ffffffff8124645d: compat_writev.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251920)
Location: fs/read_write.c:1257
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff81251920-ffffffff81251a59: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273290)
Location: fs/read_write.c:1260
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff81273290-ffffffff812733c9: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81299440)
Location: fs/read_write.c:1287
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff81299440-ffffffff81299559: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ae2c0)
Location: fs/read_write.c:1284
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812ae2c0-ffffffff812ae3d9: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812caf60)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812caf60-ffffffff812cb07b: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dc980)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812dc980-ffffffff812dca9b: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81313830)
Location: fs/read_write.c:1393
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_pwritev64
  - fs/read_write.c:__ia32_compat_sys_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff81313830-ffffffff81313956: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010382398)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffff800010382398-ffff8000103824c8: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000478a60)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
c000000000478a60-c000000000478bf4: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4f60)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812d4f60-ffffffff812d507b: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5be0)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812c5be0-ffffffff812c5cfb: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2d70)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812d2d70-ffffffff812d2e8b: compat_writev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t compat_writev(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e3bd0)
Location: fs/read_write.c:1309
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_pwritev64
  - fs/read_write.c:do_compat_writev
```
**Symbols:**

```
ffffffff812e3bd0-ffffffff812e3ceb: compat_writev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
