# Function: <code>free_zspage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_zspage(struct page *first_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81204fa0)
Location: mm/zsmalloc.c:886
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_malloc
```
**Symbols:**

```
ffffffff81204fa0-ffffffff812050bd: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8122bb20)
Location: mm/zsmalloc.c:1014
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8122bb20-ffffffff8122bb98: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8123e080)
Location: mm/zsmalloc.c:1014
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8123e080-ffffffff8123e0f8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81249a20)
Location: mm/zsmalloc.c:1006
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81249a20-ffffffff81249a98: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81269c80)
Location: mm/zsmalloc.c:1010
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81269c80-ffffffff81269cf8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8128e610)
Location: mm/zsmalloc.c:993
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8128e610-ffffffff8128e688: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812a28b0)
Location: mm/zsmalloc.c:980
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812a28b0-ffffffff812a296b: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812bdb20)
Location: mm/zsmalloc.c:970
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812bdb20-ffffffff812bdbe8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812cfa10)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812cfa10-ffffffff812cfad8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81306400)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81306400-ffffffff813064c1: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312160)
Location: mm/zsmalloc.c:960
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81312160-ffffffff81312221: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813183cb)
Location: mm/zsmalloc.c:960
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813648d3)
Location: mm/zsmalloc.c:960
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
  - mm/zsmalloc.c:zs_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e0890)
Location: mm/zsmalloc.c:952
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff813e0890-ffffffff813e09bf: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81467dc0)
Location: mm/zsmalloc.c:1051
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff81467dc0-ffffffff81467f29: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149cdf0)
Location: mm/zsmalloc.c:884
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff8149cdf0-ffffffff8149cf2a: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814cc5c0)
Location: mm/zsmalloc.c:879
Inline: True
Direct callers:
  - mm/zsmalloc.c:__zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff814cc5c0-ffffffff814cc6ef: free_zspage (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffff800010374638)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffff800010374638-ffff800010374768: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0561438)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
c0561438-c0561574: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (c0000000004678f0)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
c0000000004678f0-c000000000467a68: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffe00024d602)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffe00024d602-ffffffe00024d6ea: free_zspage (STB_LOCAL)
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
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c7ff0)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812c7ff0-ffffffff812c80b8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812b9030)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812b9030-ffffffff812b90f8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812c5e00)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812c5e00-ffffffff812c5ec8: free_zspage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_zspage(struct zs_pool *pool, struct size_class *class, struct zspage *zspage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff812d7650)
Location: mm/zsmalloc.c:967
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_compact
  - mm/zsmalloc.c:zs_free
```
**Symbols:**

```
ffffffff812d7650-ffffffff812d7718: free_zspage (STB_LOCAL)
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
<code>struct zs_pool *pool</code>
</li>
<li>
<b>Param added. </b>
<code>struct size_class *class</code>
</li>
<li>
<b>Param added. </b>
<code>struct zspage *zspage</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page *first_page</code>
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
