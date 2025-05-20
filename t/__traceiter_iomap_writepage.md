# Function: <code>__traceiter_iomap_writepage</code>

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
int __traceiter_iomap_writepage(void *__data, struct inode *inode, long unsigned int off, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff813ba210)
Location: fs/iomap/trace.h:74
Inline: False
```
**Symbols:**

```
ffffffff813ba210-ffffffff813ba261: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, long unsigned int off, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff813c1370)
Location: fs/iomap/trace.h:74
Inline: False
```
**Symbols:**

```
ffffffff813c1370-ffffffff813c13bf: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, loff_t off, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff814111e0)
Location: fs/iomap/trace.h:82
Inline: False
```
**Symbols:**

```
ffffffff814111e0-ffffffff8141122f: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, loff_t off, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81486bf0)
Location: fs/iomap/trace.h:82
Inline: False
```
**Symbols:**

```
ffffffff81486bf0-ffffffff81486c4b: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, loff_t off, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff8151a5c0)
Location: fs/iomap/trace.h:82
Inline: False
```
**Symbols:**

```
ffffffff8151a5c0-ffffffff8151a61b: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, loff_t off, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81551e20)
Location: fs/iomap/trace.h:82
Inline: False
```
**Symbols:**

```
ffffffff81551e20-ffffffff81551e7b: __traceiter_iomap_writepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_iomap_writepage(void *__data, struct inode *inode, loff_t off, u64 len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81587de0)
Location: fs/iomap/trace.h:82
Inline: False
```
**Symbols:**

```
ffffffff81587de0-ffffffff81587e3b: __traceiter_iomap_writepage (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int off</code> ➡️ <code>loff_t off</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int len</code> ➡️ <code>u64 len</code>
</li>
</ul>
</details>
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
