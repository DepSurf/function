# Function: <code>__put_compound_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119ca70)
Location: mm/swap.c:76
Inline: False
```
**Symbols:**

```
ffffffff8119ca70-ffffffff8119ca9e: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b2980)
Location: mm/swap.c:81
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
**Symbols:**

```
ffffffff811b2980-ffffffff811b29ae: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c3010)
Location: mm/swap.c:82
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
**Symbols:**

```
ffffffff811c3010-ffffffff811c303e: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811cb470)
Location: mm/swap.c:82
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff811cb470-ffffffff811cb49e: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811e03b0)
Location: mm/swap.c:82
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff811e03b0-ffffffff811e03e4: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81201330)
Location: mm/swap.c:83
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff81201330-ffffffff81201367: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812145e0)
Location: mm/swap.c:82
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff812145e0-ffffffff81214617: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81223c90)
Location: mm/swap.c:83
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff81223c90-ffffffff81223ccb: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81231a20)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff81231a20-ffffffff81231a5b: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125e8ec)
Location: mm/swap.c:103
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268877)
Location: mm/swap.c:101
Inline: True
Inline callers:
  - mm/swap.c:release_pages
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
In mm/swap.c (ffffffff8126e5e7)
Location: mm/swap.c:101
Inline: True
Inline callers:
  - mm/swap.c:release_pages
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
In mm/swap.c (ffffffff812ab5f3)
Location: mm/swap.c:101
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8130541d)
Location: mm/swap.c:109
Inline: True
Inline callers:
  - mm/swap.c:release_pages
  - mm/swap.c:put_pages_list
  - mm/swap.c:__put_page
```
</details>
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
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0bd0)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
**Symbols:**

```
ffff8000102c0bd0-ffff8000102c0c24: __put_compound_page (STB_LOCAL)
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
In mm/swap.c (c04eccf4)
Location: mm/swap.c:84
Inline: True
Inline callers:
  - mm/swap.c:release_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c00000000037b390)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
c00000000037b390-c00000000037b440: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e2bea)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap.c:__put_page
```
**Symbols:**

```
ffffffe0001e2bea-ffffffe0001e2c3a: __put_compound_page (STB_LOCAL)
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
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8122a070)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff8122a070-ffffffff8122a0ab: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121d190)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff8121d190-ffffffff8121d1cb: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81227e10)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff81227e10-ffffffff81227e4b: __put_compound_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __put_compound_page(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81237150)
Location: mm/swap.c:84
Inline: False
Direct callers:
  - mm/swap.c:release_pages
```
**Symbols:**

```
ffffffff81237150-ffffffff8123718b: __put_compound_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
