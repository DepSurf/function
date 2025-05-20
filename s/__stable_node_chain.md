# Function: <code>__stable_node_chain</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81222030)
Location: mm/ksm.c:1463
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81222030-ffffffff8122207b: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123d370)
Location: mm/ksm.c:1474
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8123d370-ffffffff8123d3bb: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8125fe20)
Location: mm/ksm.c:1504
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8125fe20-ffffffff81260178: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81274560)
Location: mm/ksm.c:1502
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81274560-ffffffff812748aa: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81290760)
Location: mm/ksm.c:1518
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff81290760-ffffffff81290ab2: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a04e0)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812a04e0-ffffffff812a0832: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d4ed0)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812d4ed0-ffffffff812d4f17: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e0950)
Location: mm/ksm.c:1501
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812e0950-ffffffff812e0997: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e79c0)
Location: mm/ksm.c:1499
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812e79c0-ffffffff812e7a07: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132f8f0)
Location: mm/ksm.c:1495
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff8132f8f0-ffffffff8132f937: __stable_node_chain (STB_LOCAL)
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
In mm/ksm.c (ffffffff8139fd4d)
Location: mm/ksm.c:1505
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
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
In mm/ksm.c (ffffffff8141ebcd)
Location: mm/ksm.c:1521
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
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
In mm/ksm.c (ffffffff814537e0)
Location: mm/ksm.c:1567
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
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
In mm/ksm.c (ffffffff8148e020)
Location: mm/ksm.c:1766
Inline: True
Inline callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
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
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033fe30)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffff80001033fe30-ffff800010340154: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0545fd8)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
c0545fd8-c0546320: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c00000000041cf80)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
c00000000041cf80-c00000000041d47c: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe000233f86)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
ffffffe000233f86-ffffffe0002341f4: __stable_node_chain (STB_LOCAL)
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
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81298ac0)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff81298ac0-ffffffff81298e12: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128a680)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff8128a680-ffffffff8128a9d2: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812968d0)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812968d0-ffffffff81296c22: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *__stable_node_chain(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a66b0)
Location: mm/ksm.c:1500
Inline: False
Direct callers:
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff812a66b0-ffffffff812a69fd: __stable_node_chain (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
