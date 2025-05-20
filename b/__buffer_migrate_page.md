# Function: <code>__buffer_migrate_page</code>

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
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81282920)
Location: mm/migrate.c:739
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff81282920-ffffffff81282b57: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8129eab0)
Location: mm/migrate.c:735
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff8129eab0-ffffffff8129ed51: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ae350)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812ae350-ffffffff812ae5f1: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff812e6db5)
Location: mm/migrate.c:756
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812e4d40-ffffffff812e4fe0: __buffer_migrate_page.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff812f2105)
Location: mm/migrate.c:754
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812ef720-ffffffff812ef9b0: __buffer_migrate_page.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff812f8455)
Location: mm/migrate.c:734
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812f6410-ffffffff812f6696: __buffer_migrate_page.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff81342ac5)
Location: mm/migrate.c:697
Inline: True
Inline callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff81340a50-ffffffff81340cd2: __buffer_migrate_page.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff813b2850)
Location: mm/migrate.c:675
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff813b2850-ffffffff813b2be9: __buffer_migrate_page (STB_LOCAL)
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
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffff800010350168)
Location: mm/migrate.c:736
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffff800010350168-ffff800010350518: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c0551888)
Location: mm/migrate.c:736
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
c0551888-c0551c44: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000433e80)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
c000000000433e80-c000000000434318: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffe00023ee58)
Location: mm/migrate.c:736
Inline: False
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffe00023ee58-ffffffe00023f120: __buffer_migrate_page (STB_LOCAL)
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
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6930)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812a6930-ffffffff812a6bd1: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812983d0)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812983d0-ffffffff81298671: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a4740)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812a4740-ffffffff812a49e1: __buffer_migrate_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __buffer_migrate_page(struct address_space *mapping, struct page *newpage, struct page *page, enum migrate_mode mode, bool check_refs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b52a0)
Location: mm/migrate.c:736
Inline: True
Direct callers:
  - mm/migrate.c:buffer_migrate_page_norefs
  - mm/migrate.c:buffer_migrate_page
```
**Symbols:**

```
ffffffff812b52a0-ffffffff812b5538: __buffer_migrate_page (STB_LOCAL)
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
