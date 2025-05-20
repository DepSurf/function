# Function: <code>put_huge_zero_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f3d40)
Location: mm/huge_memory.c:203
Inline: True
Direct callers:
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811f3d40-ffffffff811f3d56: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812140d0)
Location: mm/huge_memory.c:89
Inline: True
Direct callers:
  - mm/swap.c:release_pages
  - mm/swap_state.c:free_page_and_swap_cache
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
**Symbols:**

```
ffffffff812140d0-ffffffff812140e6: put_huge_zero_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81225ee0)
Location: mm/huge_memory.c:89
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff81225ee0-ffffffff81225ef6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812318a0)
Location: mm/huge_memory.c:92
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812318a0-ffffffff812318b6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8124f550)
Location: mm/huge_memory.c:92
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff8124f550-ffffffff8124f566: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812730f0)
Location: mm/huge_memory.c:92
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812730f0-ffffffff81273106: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81287660)
Location: mm/huge_memory.c:102
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff81287660-ffffffff81287676: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1c30)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812a1c30-ffffffff812a1c46: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b2fe0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812b2fe0-ffffffff812b2ff6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812e8390)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812e8390-ffffffff812e83a6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f38d0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812f38d0-ffffffff812f38e6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9c60)
Location: mm/huge_memory.c:119
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812f9c60-ffffffff812f9c76: put_huge_zero_page (STB_LOCAL)
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
In mm/huge_memory.c (ffffffff81345d09)
Location: mm/huge_memory.c:119
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
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
In mm/huge_memory.c (ffffffff813bbee1)
Location: mm/huge_memory.c:118
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143e431)
Location: mm/huge_memory.c:181
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81473c11)
Location: mm/huge_memory.c:182
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a3111)
Location: mm/huge_memory.c:220
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
  - mm/huge_memory.c:mm_get_huge_zero_page
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
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103541d0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffff8000103541d0-ffff800010354224: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043d95c)
Location: mm/huge_memory.c:107
Inline: True
Inline callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ab5c0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812ab5c0-ffffffff812ab5d6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129cec0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff8129cec0-ffffffff8129ced6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a93d0)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812a93d0-ffffffff812a93e6: put_huge_zero_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_huge_zero_page();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b9970)
Location: mm/huge_memory.c:107
Inline: True
Direct callers:
  - mm/huge_memory.c:mm_put_huge_zero_page
```
**Symbols:**

```
ffffffff812b9970-ffffffff812b9986: put_huge_zero_page (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
