# Function: <code>__traceiter_ext4_write_end</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81431200)
Location: include/trace/events/ext4.h:398
Inline: False
```
**Symbols:**

```
ffffffff81431200-ffffffff8143125b: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81437df0)
Location: include/trace/events/ext4.h:398
Inline: False
```
**Symbols:**

```
ffffffff81437df0-ffffffff81437e49: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148ba70)
Location: include/trace/events/ext4.h:398
Inline: False
```
**Symbols:**

```
ffffffff8148ba70-ffffffff8148bac9: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8150f8c0)
Location: include/trace/events/ext4.h:404
Inline: False
```
**Symbols:**

```
ffffffff8150f8c0-ffffffff8150f928: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815aa820)
Location: include/trace/events/ext4.h:406
Inline: False
```
**Symbols:**

```
ffffffff815aa820-ffffffff815aa888: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e1140)
Location: include/trace/events/ext4.h:420
Inline: False
```
**Symbols:**

```
ffffffff815e1140-ffffffff815e11a8: __traceiter_ext4_write_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_write_end(void *__data, struct inode *inode, loff_t pos, unsigned int len, unsigned int copied);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81619b50)
Location: include/trace/events/ext4.h:420
Inline: False
```
**Symbols:**

```
ffffffff81619b50-ffffffff81619bb8: __traceiter_ext4_write_end (STB_GLOBAL)
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
