# Function: <code>stable_node_dup</code>

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
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81221dc0)
Location: mm/ksm.c:1317
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff81221dc0-ffffffff81222027: stable_node_dup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123d080)
Location: mm/ksm.c:1328
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff8123d080-ffffffff8123d365: stable_node_dup (STB_GLOBAL)
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
In mm/ksm.c (ffffffff8125fe8f)
Location: mm/ksm.c:1358
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff812745d2)
Location: mm/ksm.c:1356
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff812907d1)
Location: mm/ksm.c:1372
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff812a0551)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d4c00)
Location: mm/ksm.c:1354
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff812d4c00-ffffffff812d4ecb: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e0680)
Location: mm/ksm.c:1355
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff812e0680-ffffffff812e0945: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e76f0)
Location: mm/ksm.c:1353
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff812e76f0-ffffffff812e79b5: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132f620)
Location: mm/ksm.c:1349
Inline: False
Direct callers:
  - mm/ksm.c:__stable_node_chain
```
**Symbols:**

```
ffffffff8132f620-ffffffff8132f8e5: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *stable_node_dup(struct stable_node **_stable_node_dup, struct stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139f8c0)
Location: mm/ksm.c:1359
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff8139f8c0-ffffffff8139fc38: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *stable_node_dup(struct ksm_stable_node **_stable_node_dup, struct ksm_stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8141e730)
Location: mm/ksm.c:1375
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff8141e730-ffffffff8141eaa6: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *stable_node_dup(struct ksm_stable_node **_stable_node_dup, struct ksm_stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81453340)
Location: mm/ksm.c:1421
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff81453340-ffffffff814536b4: stable_node_dup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *stable_node_dup(struct ksm_stable_node **_stable_node_dup, struct ksm_stable_node **_stable_node, struct rb_root *root, bool prune_stale_stable_nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8148db90)
Location: mm/ksm.c:1620
Inline: False
Direct callers:
  - mm/ksm.c:stable_tree_insert
  - mm/ksm.c:stable_tree_search
```
**Symbols:**

```
ffffffff8148db90-ffffffff8148defe: stable_node_dup (STB_LOCAL)
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
In mm/ksm.c (ffff80001033fed8)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (c0546060)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (c00000000041d068)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffe000234010)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff81298b31)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff8128a6f1)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff81296941)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
In mm/ksm.c (ffffffff812a6721)
Location: mm/ksm.c:1354
Inline: True
Inline callers:
  - mm/ksm.c:__stable_node_chain
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
<code>struct stable_node **_stable_node_dup</code> ➡️ <code>struct ksm_stable_node **_stable_node_dup</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct stable_node **_stable_node</code> ➡️ <code>struct ksm_stable_node **_stable_node</code>
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
