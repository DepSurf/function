# Function: <code>__munlock_isolate_lru_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mlock.c (ffffffff811c2c90)
Location: mm/mlock.c:98
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff811c2c90-ffffffff811c2db8: __munlock_isolate_lru_page.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811de830)
Location: mm/mlock.c:101
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff811de830-ffffffff811de9fb: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811ee650)
Location: mm/mlock.c:101
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff811ee650-ffffffff811ee81c: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f95f0)
Location: mm/mlock.c:102
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff811f95f0-ffffffff811f97a1: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81211a20)
Location: mm/mlock.c:103
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff81211a20-ffffffff81211bd1: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81232770)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff81232770-ffffffff8123291c: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81245fb0)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff81245fb0-ffffffff8124615f: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812581a0)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff812581a0-ffffffff81258367: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81266670)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff81266670-ffffffff81266837: __munlock_isolate_lru_page (STB_LOCAL)
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
In mm/mlock.c (ffffffff81296bf9)
Location: mm/mlock.c:109
Inline: True
Inline callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff81296780-ffffffff8129691a: __munlock_isolate_lru_page.part.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fd6c8)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffff8000102fd6c8-ffff8000102fd8d4: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051caa8)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
c051caa8-c051cc28: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c8960)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
c0000000003c8960-c0000000003c8c08: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020bf6c)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffe00020bf6c-ffffffe00020c0b4: __munlock_isolate_lru_page (STB_LOCAL)
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
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125ecc0)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff8125ecc0-ffffffff8125ee87: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812510f0)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff812510f0-ffffffff812512b7: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125ca60)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff8125ca60-ffffffff8125cc27: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __munlock_isolate_lru_page(struct page *page, bool getpage);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126c440)
Location: mm/mlock.c:109
Inline: True
Direct callers:
  - mm/mlock.c:__munlock_pagevec
  - mm/mlock.c:munlock_vma_page
```
**Symbols:**

```
ffffffff8126c440-ffffffff8126c607: __munlock_isolate_lru_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
