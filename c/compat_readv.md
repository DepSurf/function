# Function: <code>compat_readv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120ced0)
Location: fs/read_write.c:1024
Inline: False
Direct callers:
  - fs/read_write.c:__compat_sys_preadv64
  - fs/read_write.c:compat_SyS_readv
```
**Symbols:**

```
ffffffff8120ced0-ffffffff8120cf37: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81233680)
Location: fs/read_write.c:1110
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81233680-ffffffff812336ea: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81246210)
Location: fs/read_write.c:1139
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81246210-ffffffff8124627a: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81251220)
Location: fs/read_write.c:1152
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81251220-ffffffff81251307: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81272b80)
Location: fs/read_write.c:1155
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81272b80-ffffffff81272c67: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81298a70)
Location: fs/read_write.c:1182
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81298a70-ffffffff81298b3b: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad8f0)
Location: fs/read_write.c:1179
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812ad8f0-ffffffff812ad9bb: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ca580)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812ca580-ffffffff812ca64d: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812dbfa0)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812dbfa0-ffffffff812dc06d: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81312b80)
Location: fs/read_write.c:1285
Inline: False
Direct callers:
  - fs/read_write.c:__x32_compat_sys_preadv64
  - fs/read_write.c:__ia32_compat_sys_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff81312b80-ffffffff81312c54: compat_readv (STB_LOCAL)
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
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010381a40)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffff800010381a40-ffff800010381b24: compat_readv (STB_LOCAL)
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
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000477f30)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
c000000000477f30-c00000000047802c: compat_readv (STB_LOCAL)
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
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d4580)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812d4580-ffffffff812d464d: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c5200)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812c5200-ffffffff812c52cd: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d2390)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812d2390-ffffffff812d245d: compat_readv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t compat_readv(struct file *file, const struct compat_iovec *vec, long unsigned int vlen, loff_t *pos, rwf_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e31f0)
Location: fs/read_write.c:1201
Inline: False
Direct callers:
  - fs/read_write.c:do_compat_preadv64
  - fs/read_write.c:do_compat_readv
```
**Symbols:**

```
ffffffff812e31f0-ffffffff812e32bd: compat_readv (STB_LOCAL)
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
