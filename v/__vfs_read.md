# Function: <code>__vfs_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120c190)
Location: fs/read_write.c:428
Inline: False
Direct callers:
  - fs/read_write.c:vfs_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff8120c190-ffffffff8120c1c1: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81232430)
Location: fs/read_write.c:448
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81232430-ffffffff81232461: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81244da0)
Location: fs/read_write.c:448
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81244da0-ffffffff81244dd1: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8124fe10)
Location: fs/read_write.c:406
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff8124fe10-ffffffff8124fe41: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81273bf0)
Location: fs/read_write.c:407
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81273bf0-ffffffff81273c24: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8129a930)
Location: fs/read_write.c:412
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff8129a930-ffffffff8129a964: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812af810)
Location: fs/read_write.c:412
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812af810-ffffffff812af844: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812cc490)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812cc490-ffffffff812cc4c4: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ddeb0)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812ddeb0-ffffffff812ddee4: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010384010)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffff800010384010-ffff80001038409c: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056cee4)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
c056cee4-c056cf2c: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c00000000047a090)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
c00000000047a090-c00000000047a0f8: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe00025726a)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffe00025726a-ffffffe0002572d4: __vfs_read (STB_GLOBAL)
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
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d6490)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812d6490-ffffffff812d64c4: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c7110)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812c7110-ffffffff812c7144: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d42a0)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812d42a0-ffffffff812d42d4: __vfs_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __vfs_read(struct file *file, char *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e5100)
Location: fs/read_write.c:421
Inline: False
Direct callers:
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff812e5100-ffffffff812e5134: __vfs_read (STB_GLOBAL)
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
