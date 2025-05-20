# Function: <code>__get_any_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812020f0)
Location: mm/memory-failure.c:1530
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812020f0-ffffffff8120219c: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81226350)
Location: mm/memory-failure.c:1500
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81226350-ffffffff812263fc: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81238920)
Location: mm/memory-failure.c:1496
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81238920-ffffffff812389cc: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812444d0)
Location: mm/memory-failure.c:1499
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812444d0-ffffffff8124457c: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81264360)
Location: mm/memory-failure.c:1497
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff81264360-ffffffff8126440c: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1623
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812885b0-ffffffff8128860a: __get_any_page (STB_LOCAL)
ffffffff8128a97d-ffffffff8128a9d7: __get_any_page.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff8129f8ff)
Location: mm/memory-failure.c:1627
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff8129d580-ffffffff8129d5da: __get_any_page (STB_LOCAL)
ffffffff8129f8e4-ffffffff8129f93e: __get_any_page.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812bab90)
Location: mm/memory-failure.c:1620
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b8860-ffffffff812b88ba: __get_any_page (STB_LOCAL)
ffffffff812bab75-ffffffff812babcf: __get_any_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812cca6c)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812ca740-ffffffff812ca79a: __get_any_page (STB_LOCAL)
ffffffff812cca51-ffffffff812ccaab: __get_any_page.cold (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff81301df5)
Location: mm/memory-failure.c:1662
Inline: True
Inline callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
Direct callers:
  - mm/memory-failure.c:get_any_page
  - mm/memory-failure.c:get_any_page
```
**Symbols:**

```
ffffffff81300180-ffffffff813001b9: __get_any_page.part.0 (STB_LOCAL)
ffffffff81302ad7-ffffffff81302b33: __get_any_page.part.0.cold (STB_LOCAL)
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
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffff80001036e5a0)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffff80001036e5a0-ffff80001036e674: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c00000000045e710)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
c00000000045e710-c00000000045e838: __get_any_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812c504c)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c2d20-ffffffff812c2d7a: __get_any_page (STB_LOCAL)
ffffffff812c5031-ffffffff812c508b: __get_any_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812b608c)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812b3d70-ffffffff812b3dca: __get_any_page (STB_LOCAL)
ffffffff812b6071-ffffffff812b60cb: __get_any_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812c2e5c)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812c0b30-ffffffff812c0b8a: __get_any_page (STB_LOCAL)
ffffffff812c2e41-ffffffff812c2e9b: __get_any_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __get_any_page(struct page *p, long unsigned int pfn, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (ffffffff812d38fc)
Location: mm/memory-failure.c:1626
Inline: True
Direct callers:
  - mm/memory-failure.c:soft_offline_page
  - mm/memory-failure.c:soft_offline_page
```
**Symbols:**

```
ffffffff812d15f0-ffffffff812d164a: __get_any_page (STB_LOCAL)
ffffffff812d38e1-ffffffff812d393b: __get_any_page.cold (STB_LOCAL)
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
