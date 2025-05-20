# Function: <code>new_non_cma_page</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a670)
Location: mm/gup.c:1389
Inline: False
```
**Symbols:**

```
ffffffff8124a670-ffffffff8124a717: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258b40)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffffffff81258b40-ffffffff81258be7: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0c60)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffff8000102f0c60-ffff8000102f0d3c: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0514094)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
c0514094-c05140e0: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b57b0)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
c0000000003b57b0-c0000000003b58e4: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe0002043c0)
Location: mm/gup.c:1392
Inline: True
```
**Symbols:**

```
ffffffe0002043c0-ffffffe00020443c: new_non_cma_page (STB_LOCAL)
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
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251190)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffffffff81251190-ffffffff81251237: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81244080)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffffffff81244080-ffffffff81244127: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124ef30)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffffffff8124ef30-ffffffff8124efd7: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *new_non_cma_page(struct page *page, long unsigned int private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125e8a0)
Location: mm/gup.c:1392
Inline: False
```
**Symbols:**

```
ffffffff8125e8a0-ffffffff8125e947: new_non_cma_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
