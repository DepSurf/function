# Function: <code>warn_unsupported</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff8131d67c)
Location: fs/read_write.c:422
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff8135ce90)
Location: fs/splice.c:748
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:do_splice_to
```
**Symbols:**

```
ffffffff81bea494-ffffffff81bea4c4: warn_unsupported.part.0 (STB_LOCAL)
ffffffff8135ce90-ffffffff8135cf02: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff813237e7)
Location: fs/read_write.c:422
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff81363940)
Location: fs/splice.c:751
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:do_splice_to
```
**Symbols:**

```
ffffffff81bdc4ce-ffffffff81bdc4fe: warn_unsupported.part.0 (STB_LOCAL)
ffffffff81363940-ffffffff813639b2: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff81370cba)
Location: fs/read_write.c:411
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff813b2140)
Location: fs/splice.c:751
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:do_splice_to
```
**Symbols:**

```
ffffffff81cc37c6-ffffffff81cc37f6: warn_unsupported.part.0 (STB_LOCAL)
ffffffff813b2140-ffffffff813b21af: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/read_write.c (ffffffff813f006b)
Location: fs/read_write.c:408
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
Direct callers:
  - fs/read_write.c:__kernel_write
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff81437100)
Location: fs/splice.c:751
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:do_splice_to
```
**Symbols:**

```
ffffffff81e75f17-ffffffff81e75f58: warn_unsupported.part.0 (STB_LOCAL)
ffffffff81437100-ffffffff81437191: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147a8d6)
Location: fs/read_write.c:396
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff814c51c0)
Location: fs/splice.c:748
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
  - fs/splice.c:do_splice_to
```
**Symbols:**

```
ffffffff814c51c0-ffffffff814c5251: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814af427)
Location: fs/read_write.c:396
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff814fa600)
Location: fs/splice.c:920
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff814fa600-ffffffff814fa6ab: warn_unsupported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int warn_unsupported(struct file *file, const char *op);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e0ba6)
Location: fs/read_write.c:402
Inline: True
Inline callers:
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_write_iter
  - fs/read_write.c:__kernel_read
  - fs/read_write.c:__kernel_read
```
```
In fs/splice.c (ffffffff8152eef0)
Location: fs/splice.c:925
Inline: True
Direct callers:
  - fs/splice.c:do_splice
  - fs/splice.c:splice_file_range_actor
  - fs/splice.c:direct_splice_actor
```
**Symbols:**

```
ffffffff8152eef0-ffffffff8152ef9b: warn_unsupported (STB_LOCAL)
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
