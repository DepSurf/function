# Function: <code>dax_layout_busy_page</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/dax.c (ffffffff812f78f0)
Location: fs/dax.c:630
Inline: True
```
**Symbols:**

```
ffffffff812f78f0-ffffffff812f7b27: dax_layout_busy_page.part.35 (STB_LOCAL)
ffffffff812f7b30-ffffffff812f7b5c: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8130e660)
Location: fs/dax.c:569
Inline: False
```
**Symbols:**

```
ffffffff8130e660-ffffffff8130e8c1: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81334d90)
Location: fs/dax.c:575
Inline: False
```
**Symbols:**

```
ffffffff81334d90-ffffffff81335011: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81348970)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffff81348970-ffffffff81348bf1: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8138dca0)
Location: fs/dax.c:576
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_break_layouts
```
**Symbols:**

```
ffffffff8138dca0-ffffffff8138df76: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8139f250)
Location: fs/dax.c:641
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_break_layouts
```
**Symbols:**

```
ffffffff8139f250-ffffffff8139f26c: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813a6a10)
Location: fs/dax.c:653
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_break_layouts
```
**Symbols:**

```
ffffffff813a6a10-ffffffff813a6a2c: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813f64a0)
Location: fs/dax.c:653
Inline: False
```
**Symbols:**

```
ffffffff813f64a0-ffffffff813f64bc: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81468810)
Location: fs/dax.c:653
Inline: False
```
**Symbols:**

```
ffffffff81468810-ffffffff81468836: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff814f92b0)
Location: fs/dax.c:753
Inline: False
```
**Symbols:**

```
ffffffff814f92b0-ffffffff814f92d6: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81530880)
Location: fs/dax.c:753
Inline: False
```
**Symbols:**

```
ffffffff81530880-ffffffff815308a6: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81565760)
Location: fs/dax.c:739
Inline: False
```
**Symbols:**

```
ffffffff81565760-ffffffff81565786: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffff800010408d80)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffff800010408d80-ffff8000104090a4: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: include/linux/dax.h:177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (c0000000005150d0)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
c0000000005150d0-c000000000515464: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffe0002b319e)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffe0002b319e-ffffffe0002b3422: dax_layout_busy_page (STB_GLOBAL)
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
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81340f50)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffff81340f50-ffffffff813411d1: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81331930)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffff81331930-ffffffff81331ba5: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8133ea20)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffff8133ea20-ffffffff8133eca1: dax_layout_busy_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *dax_layout_busy_page(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff813518f0)
Location: fs/dax.c:576
Inline: False
```
**Symbols:**

```
ffffffff813518f0-ffffffff81351b5a: dax_layout_busy_page (STB_GLOBAL)
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
