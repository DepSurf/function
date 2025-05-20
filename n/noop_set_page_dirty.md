# Function: <code>noop_set_page_dirty</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6140)
Location: fs/libfs.c:1063
Inline: True
```
**Symbols:**

```
ffffffff812c6140-ffffffff812c614d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812db340)
Location: fs/libfs.c:1063
Inline: True
```
**Symbols:**

```
ffffffff812db340-ffffffff812db34d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f9970)
Location: fs/libfs.c:1082
Inline: False
```
**Symbols:**

```
ffffffff812f9970-ffffffff812f997d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130b5a0)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff8130b5a0-ffffffff8130b5ad: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81344db0)
Location: fs/libfs.c:1158
Inline: True
```
**Symbols:**

```
ffffffff81344db0-ffffffff81344dbd: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813510a0)
Location: fs/libfs.c:1162
Inline: True
```
**Symbols:**

```
ffffffff813510a0-ffffffff813510ad: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81357d90)
Location: fs/libfs.c:1165
Inline: True
```
**Symbols:**

```
ffffffff81357d90-ffffffff81357d9d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103bfb20)
Location: fs/libfs.c:1122
Inline: True
```
**Symbols:**

```
ffff8000103bfb20-ffff8000103bfb3c: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059c8b4)
Location: fs/libfs.c:1122
Inline: True
```
**Symbols:**

```
c059c8b4-c059c8d0: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004be4f0)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
c0000000004be4f0-c0000000004be500: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe00028037a)
Location: fs/libfs.c:1122
Inline: True
```
**Symbols:**

```
ffffffe00028037a-ffffffe000280396: noop_set_page_dirty (STB_GLOBAL)
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
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81303b80)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81303b80-ffffffff81303b8d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f47a0)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff812f47a0-ffffffff812f47ad: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81301970)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81301970-ffffffff8130197d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int noop_set_page_dirty(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81312d40)
Location: fs/libfs.c:1122
Inline: False
```
**Symbols:**

```
ffffffff81312d40-ffffffff81312d4d: noop_set_page_dirty (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
