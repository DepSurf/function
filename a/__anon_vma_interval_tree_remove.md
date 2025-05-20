# Function: <code>__anon_vma_interval_tree_remove</code>

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
In mm/interval_tree.c (ffffffff811b8b96)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff811d2e36)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff811e2cf6)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff811ed166)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81203563)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81224215)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81237255)
Location: mm/interval_tree.c:72
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81248815)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81256c65)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81284d90)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff81284d90-ffffffff81285050: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff8128f070)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff8128f070-ffffffff8128f330: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812946e0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff812946e0-ffffffff8129499d: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff812d4d40)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff812d4d40-ffffffff812d4ffd: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81333e30)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff81333e30-ffffffff81334126: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813aaab0)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff813aaab0-ffffffff813aad9c: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff813dee80)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff813dee80-ffffffff813df15b: __anon_vma_interval_tree_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __anon_vma_interval_tree_remove(struct anon_vma_chain *node, struct rb_root_cached *root);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/interval_tree.c (ffffffff81409590)
Location: mm/interval_tree.c:71
Inline: False
Direct callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
```
**Symbols:**

```
ffffffff81409590-ffffffff8140986b: __anon_vma_interval_tree_remove (STB_LOCAL)
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
In mm/interval_tree.c (ffff8000102ee548)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (c051236c)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (c0000000003b263c)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffe0002026b0)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff8124f2b5)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff81242255)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff8124d055)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
In mm/interval_tree.c (ffffffff8125ca15)
Location: mm/interval_tree.c:71
Inline: True
Inline callers:
  - mm/interval_tree.c:anon_vma_interval_tree_remove
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
