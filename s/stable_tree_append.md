# Function: <code>stable_tree_append</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff811e4610)
Location: mm/ksm.c:1412
Inline: True
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff811e4610-ffffffff811e4661: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81202f40)
Location: mm/ksm.c:1384
Inline: True
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81202f40-ffffffff81202f91: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81214e20)
Location: mm/ksm.c:1413
Inline: True
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81214e20-ffffffff81214e71: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8121fea0)
Location: mm/ksm.c:1950
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8121fea0-ffffffff8121ff10: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123b0c0)
Location: mm/ksm.c:1961
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8123b0c0-ffffffff8123b130: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8125eb20)
Location: mm/ksm.c:1991
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8125eb20-ffffffff8125eb90: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81273350)
Location: mm/ksm.c:1989
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81273350-ffffffff812733c0: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128eb50)
Location: mm/ksm.c:2012
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8128eb50-ffffffff8128ebc0: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129e930)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8129e930-ffffffff8129e9a0: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d2f40)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812d2f40-ffffffff812d2fb0: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812de800)
Location: mm/ksm.c:1995
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812de800-ffffffff812de870: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e5fe0)
Location: mm/ksm.c:1991
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e5fe0-ffffffff812e6050: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132df30)
Location: mm/ksm.c:1987
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8132df30-ffffffff8132dfa0: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139e190)
Location: mm/ksm.c:1997
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8139e190-ffffffff8139e234: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void stable_tree_append(struct ksm_rmap_item *rmap_item, struct ksm_stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8141d310)
Location: mm/ksm.c:2013
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8141d310-ffffffff8141d3b4: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void stable_tree_append(struct ksm_rmap_item *rmap_item, struct ksm_stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81451c50)
Location: mm/ksm.c:2059
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81451c50-ffffffff81451cf4: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void stable_tree_append(struct ksm_rmap_item *rmap_item, struct ksm_stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8148bc80)
Location: mm/ksm.c:2258
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8148bc80-ffffffff8148bd24: stable_tree_append (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033da98)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffff80001033da98-ffff80001033db64: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0544624)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
c0544624-c0544700: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0000000004199f0)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
c0000000004199f0-c000000000419aa8: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe000233456)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
ffffffe000233456-ffffffe0002334fa: stable_tree_append (STB_LOCAL)
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
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81296f10)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81296f10-ffffffff81296f80: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81288b20)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81288b20-ffffffff81288b90: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81294d20)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81294d20-ffffffff81294d90: stable_tree_append (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void stable_tree_append(struct rmap_item *rmap_item, struct stable_node *stable_node, bool max_page_sharing_bypass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a4b90)
Location: mm/ksm.c:1994
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812a4b90-ffffffff812a4c00: stable_tree_append (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool max_page_sharing_bypass</code>
</li>
</ul>
</details>
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
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rmap_item *rmap_item</code> ➡️ <code>struct ksm_rmap_item *rmap_item</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct stable_node *stable_node</code> ➡️ <code>struct ksm_stable_node *stable_node</code>
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
