# Function: <code>split_page_memcg</code>

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
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309330)
Location: mm/memcontrol.c:3302
Inline: False
Direct callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81309330-ffffffff81309396: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f8e0)
Location: mm/memcontrol.c:3134
Inline: False
Direct callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8130f8e0-ffffffff8130f973: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135ab70)
Location: mm/memcontrol.c:3302
Inline: False
Direct callers:
  - mm/page_alloc.c:split_page
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8135ab70-ffffffff8135ac00: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d41c0)
Location: mm/memcontrol.c:3306
Inline: False
Direct callers:
  - mm/page_alloc.c:split_page
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff813d41c0-ffffffff813d42d2: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81459ba0)
Location: mm/memcontrol.c:3406
Inline: False
Direct callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:split_page
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff81459ba0-ffffffff81459cb2: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148f830)
Location: mm/memcontrol.c:3417
Inline: False
Direct callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:split_page
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff8148f830-ffffffff8148f942: split_page_memcg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void split_page_memcg(struct page *head, unsigned int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf070)
Location: mm/memcontrol.c:3609
Inline: False
Direct callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:split_page
  - mm/huge_memory.c:__split_huge_page
```
**Symbols:**

```
ffffffff814bf070-ffffffff814bf17c: split_page_memcg (STB_GLOBAL)
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
