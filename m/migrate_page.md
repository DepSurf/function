# Function: <code>migrate_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff811f1fe0)
Location: mm/migrate.c:593
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff811f1fe0-ffffffff811f202b: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81211020)
Location: mm/migrate.c:693
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff81211020-ffffffff8121106b: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812231e0)
Location: mm/migrate.c:695
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812231e0-ffffffff8122322b: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8122ec30)
Location: mm/migrate.c:681
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8122ec30-ffffffff8122ec7b: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124ad70)
Location: mm/migrate.c:738
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8124ad70-ffffffff8124adeb: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126ec40)
Location: mm/migrate.c:750
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff8126ec40-ffffffff8126ecb5: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812828b0)
Location: mm/migrate.c:679
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812828b0-ffffffff81282920: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129e8a0)
Location: mm/migrate.c:675
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff8129e8a0-ffffffff8129e90f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ae140)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812ae140-ffffffff812ae1af: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e4cd0)
Location: mm/migrate.c:696
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812e4cd0-ffffffff812e4d3f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ef6b0)
Location: mm/migrate.c:694
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812ef6b0-ffffffff812ef71f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f63a0)
Location: mm/migrate.c:674
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812f63a0-ffffffff812f640f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813409e0)
Location: mm/migrate.c:637
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff813409e0-ffffffff81340a4f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2390)
Location: mm/migrate.c:613
Inline: False
Direct callers:
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:move_to_new_folio
  - mm/migrate.c:__buffer_migrate_page
  - mm/migrate_device.c:migrate_vma_pages
```
**Symbols:**

```
ffffffff813b2390-ffffffff813b2493: migrate_page (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff8000103500c8)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
```
**Symbols:**

```
ffff8000103500c8-ffff800010350168: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c05517d4)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
```
**Symbols:**

```
c05517d4-c0551888: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000433810)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
c000000000433810-c0000000004338e8: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023edd8)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:__buffer_migrate_page
```
**Symbols:**

```
ffffffe00023edd8-ffffffe00023ee58: migrate_page (STB_GLOBAL)
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
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6720)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812a6720-ffffffff812a678f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812981c0)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812981c0-ffffffff8129822f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a4530)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812a4530-ffffffff812a459f: migrate_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b4880)
Location: mm/migrate.c:676
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma_pages
  - mm/migrate.c:move_to_new_page
  - mm/migrate.c:move_to_new_page
```
**Symbols:**

```
ffffffff812b4880-ffffffff812b48ef: migrate_page (STB_GLOBAL)
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
