# Function: <code>stable_tree_insert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e679c)
Location: mm/ksm.c:1258
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81205750)
Location: mm/ksm.c:1230
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8121762f)
Location: mm/ksm.c:1259
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812231e3)
Location: mm/ksm.c:1760
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123e722)
Location: mm/ksm.c:1771
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81261d40)
Location: mm/ksm.c:1801
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812765db)
Location: mm/ksm.c:1799
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129174c)
Location: mm/ksm.c:1821
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a14cc)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d4f20)
Location: mm/ksm.c:1803
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812d4f20-ffffffff812d520c: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e09a0)
Location: mm/ksm.c:1804
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e09a0-ffffffff812e0c89: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e7a10)
Location: mm/ksm.c:1800
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e7a10-ffffffff812e7cf9: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132f940)
Location: mm/ksm.c:1796
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8132f940-ffffffff8132fc29: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139fc40)
Location: mm/ksm.c:1806
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8139fc40-ffffffff8139ffe8: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ksm_stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8141eac0)
Location: mm/ksm.c:1822
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8141eac0-ffffffff8141ee68: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ksm_stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814536d0)
Location: mm/ksm.c:1868
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff814536d0-ffffffff81453a72: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ksm_stable_node *stable_tree_insert(struct page *kpage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8148df10)
Location: mm/ksm.c:2067
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8148df10-ffffffff8148e2af: stable_tree_insert (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff800010340e08)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
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
In mm/ksm.c (c0547070)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041e678)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe00023571c)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:ksm_do_scan
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81299aac)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128b66c)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812978bc)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a7693)
Location: mm/ksm.c:1803
Inline: True
Inline callers:
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct stable_node *</code> ➡️ <code>struct ksm_stable_node *</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
