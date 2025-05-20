# Function: <code>iomap_invalidatepage</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81325aa0)
Location: fs/iomap.c:552
Inline: True
```
**Symbols:**

```
ffffffff81325aa0-ffffffff81325b06: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134cc70)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff8134cc70-ffffffff8134ccd6: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81364f40)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff81364f40-ffffffff81364fa6: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813ac0b0)
Location: fs/iomap/buffered-io.c:497
Inline: True
```
**Symbols:**

```
ffffffff813ac0b0-ffffffff813ac18d: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bdf60)
Location: fs/iomap/buffered-io.c:478
Inline: True
```
**Symbols:**

```
ffffffff813bdf60-ffffffff813be00d: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c5120)
Location: fs/iomap/buffered-io.c:478
Inline: True
```
**Symbols:**

```
ffffffff813c5120-ffffffff813c51cd: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414b60)
Location: fs/iomap/buffered-io.c:479
Inline: True
```
**Symbols:**

```
ffffffff81414b60-ffffffff81414c06: iomap_invalidatepage (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042a9e0)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffff80001042a9e0-ffff80001042aa70: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f4c50)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
c05f4c50-c05f4cf8: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053c370)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
c00000000053c370-c00000000053c428: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffe0002c8b54)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffe0002c8b54-ffffffe0002c8be6: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135d520)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff8135d520-ffffffff8135d586: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134e1c0)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff8134e1c0-ffffffff8134e226: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135aff0)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff8135aff0-ffffffff8135b056: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iomap_invalidatepage(struct page *page, unsigned int offset, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136e770)
Location: fs/iomap/buffered-io.c:471
Inline: True
```
**Symbols:**

```
ffffffff8136e770-ffffffff8136e7d6: iomap_invalidatepage (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
