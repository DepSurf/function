# Function: <code>putback_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct zs_pool *pool, struct size_class *class, struct page *first_page);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81205610)
Location: mm/zsmalloc.c:1686
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81205610-ffffffff812056b8: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81229fb0)
Location: mm/zsmalloc.c:1856
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81229fb0-ffffffff8122a049: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123c500)
Location: mm/zsmalloc.c:1816
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff8123c500-ffffffff8123c599: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81248150)
Location: mm/zsmalloc.c:1795
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81248150-ffffffff812481ed: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81268310)
Location: mm/zsmalloc.c:1799
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81268310-ffffffff812683ad: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128cca0)
Location: mm/zsmalloc.c:1802
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff8128cca0-ffffffff8128cd3c: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a1c20)
Location: mm/zsmalloc.c:1789
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812a1c20-ffffffff812a1cbc: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bceb0)
Location: mm/zsmalloc.c:1779
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812bceb0-ffffffff812bcf49: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812ceda0)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812ceda0-ffffffff812cee39: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813065e1)
Location: mm/zsmalloc.c:1778
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81305a00-ffffffff81305b05: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312349)
Location: mm/zsmalloc.c:1727
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81311760-ffffffff81311865: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8131816a)
Location: mm/zsmalloc.c:1726
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
Direct callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff813175f0-ffffffff813176f7: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81364670)
Location: mm/zsmalloc.c:1725
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
Direct callers:
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff81363c50-ffffffff81363d53: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e2623)
Location: mm/zsmalloc.c:1702
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff813e09c0-ffffffff813e0adf: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81469b50)
Location: mm/zsmalloc.c:1910
Inline: True
Inline callers:
  - mm/zsmalloc.c:__zs_compact
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff81467640-ffffffff81467751: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149c060)
Location: mm/zsmalloc.c:1676
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff8149c060-ffffffff8149c19f: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cb780)
Location: mm/zsmalloc.c:1658
Inline: False
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:__zs_compact
```
**Symbols:**

```
ffffffff814cb780-ffffffff814cb8bf: putback_zspage (STB_LOCAL)
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
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff8000103739e0)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffff8000103739e0-ffff800010373a90: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0560034)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
c0560034-c05600d4: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c000000000465740)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
c000000000465740-c00000000046582c: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024c742)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffe00024c742-ffffffe00024c7d4: putback_zspage (STB_LOCAL)
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
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7380)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812c7380-ffffffff812c7419: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b83c0)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812b83c0-ffffffff812b8459: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5190)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812c5190-ffffffff812c5229: putback_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum fullness_group putback_zspage(struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d5c70)
Location: mm/zsmalloc.c:1776
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_page_putback
  - mm/zsmalloc.c:zs_page_migrate
```
**Symbols:**

```
ffffffff812d5c70-ffffffff812d5d09: putback_zspage (STB_LOCAL)
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
<code>struct zspage *zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zs_pool *pool</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *first_page</code>
</li>
<li>
<b>Param reordered. </b>
<code>pool, class, first_page</code> ➡️ <code>class, zspage</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>enum fullness_group</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
