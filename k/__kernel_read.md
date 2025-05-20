# Function: <code>__kernel_read</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81314cc0)
Location: fs/read_write.c:422
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81314cc0-ffffffff81314e26: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:430
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81bea4df-ffffffff81bea4fa: __kernel_read.cold (STB_LOCAL)
ffffffff8131fef0-ffffffff813201b0: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:430
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81bdc519-ffffffff81bdc534: __kernel_read.cold (STB_LOCAL)
ffffffff813258f0-ffffffff81325bab: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:419
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81cc3811-ffffffff81cc382c: __kernel_read.cold (STB_LOCAL)
ffffffff81373560-ffffffff8137382d: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/read_write.c (0)
Location: fs/read_write.c:416
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81e75f6c-ffffffff81e75f80: __kernel_read.cold (STB_LOCAL)
ffffffff813f1b20-ffffffff813f1e0b: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81479ea0)
Location: fs/read_write.c:404
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff81479ea0-ffffffff8147a15a: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814ae970)
Location: fs/read_write.c:404
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - fs/verity/enable.c:build_merkle_tree
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff814ae970-ffffffff814aec5b: __kernel_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __kernel_read(struct file *file, void *buf, size_t count, loff_t *pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0090)
Location: fs/read_write.c:410
Inline: False
Direct callers:
  - fs/read_write.c:kernel_read
  - fs/verity/enable.c:build_merkle_tree
  - security/integrity/iint.c:integrity_kernel_read
```
**Symbols:**

```
ffffffff814e0090-ffffffff814e03be: __kernel_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
