# Function: <code>__traceiter_iomap_readpage</code>

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
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff813ba170)
Location: fs/iomap/trace.h:41
Inline: False
```
**Symbols:**

```
ffffffff813ba170-ffffffff813ba1b7: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff813c12d0)
Location: fs/iomap/trace.h:41
Inline: False
```
**Symbols:**

```
ffffffff813c12d0-ffffffff813c1315: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81411140)
Location: fs/iomap/trace.h:50
Inline: False
```
**Symbols:**

```
ffffffff81411140-ffffffff81411185: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81486b50)
Location: fs/iomap/trace.h:50
Inline: False
```
**Symbols:**

```
ffffffff81486b50-ffffffff81486b9f: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff8151a500)
Location: fs/iomap/trace.h:50
Inline: False
```
**Symbols:**

```
ffffffff8151a500-ffffffff8151a54f: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81551d40)
Location: fs/iomap/trace.h:50
Inline: False
```
**Symbols:**

```
ffffffff81551d40-ffffffff81551d8f: __traceiter_iomap_readpage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_iomap_readpage(void *__data, struct inode *inode, int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/trace.c (ffffffff81587d00)
Location: fs/iomap/trace.h:50
Inline: False
```
**Symbols:**

```
ffffffff81587d00-ffffffff81587d4f: __traceiter_iomap_readpage (STB_GLOBAL)
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
