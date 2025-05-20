# Function: <code>__es_tree_search</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812db170)
Location: fs/ext4/extents_status.c:207
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
  - fs/ext4/extents_status.c:ext4_es_cache_extent
```
**Symbols:**

```
ffffffff812db170-ffffffff812db1d2: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130ab00)
Location: fs/ext4/extents_status.c:207
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
**Symbols:**

```
ffffffff8130ab00-ffffffff8130ab63: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81320b00)
Location: fs/ext4/extents_status.c:207
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
**Symbols:**

```
ffffffff81320b00-ffffffff81320b63: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812efab0)
Location: fs/ext4/extents_status.c:207
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
**Symbols:**

```
ffffffff812efab0-ffffffff812efb14: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813145b0)
Location: fs/ext4/extents_status.c:208
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
**Symbols:**

```
ffffffff813145b0-ffffffff81314611: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81342420)
Location: fs/ext4/extents_status.c:207
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:ext4_es_find_delayed_extent_range
```
**Symbols:**

```
ffffffff81342420-ffffffff81342483: __es_tree_search.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81359d20)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff81359d20-ffffffff81359d83: __es_tree_search.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81382d90)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff81382d90-ffffffff81382df1: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139b290)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff8139b290-ffffffff8139b2f1: __es_tree_search.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff813e67d0)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff813e67d0-ffffffff813e6831: __es_tree_search.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff813f8b00)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff813f8b00-ffffffff813f8b61: __es_tree_search.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff813feb00)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff813feb00-ffffffff813feb61: __es_tree_search.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff814512b0)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff814512b0-ffffffff81451311: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814ce810)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff814ce810-ffffffff814ce883: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81567050)
Location: fs/ext4/extents_status.c:208
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff81567050-ffffffff815670c3: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159ecd0)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff8159ecd0-ffffffff8159ed43: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d7840)
Location: fs/ext4/extents_status.c:211
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff815d7840-ffffffff815d78b3: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046de68)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffff80001046de68-ffff80001046df18: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct extent_status *__es_tree_search(struct rb_root *root, ext4_lblk_t lblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062f42c)
Location: fs/ext4/extents_status.c:210
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
c062f42c-c062f4bc: __es_tree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058ddc0)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
c00000000058ddc0-c00000000058de90: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002faf6e)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffe0002faf6e-ffffffe0002fafe8: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393870)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff81393870-ffffffff813938d1: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384300)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff81384300-ffffffff81384361: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813911d0)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff813911d0-ffffffff81391231: __es_tree_search.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a5060)
Location: fs/ext4/extents_status.c:210
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:__es_remove_extent
  - fs/ext4/extents_status.c:ext4_es_cache_extent
  - fs/ext4/extents_status.c:__es_find_extent_range
```
**Symbols:**

```
ffffffff813a5060-ffffffff813a50c1: __es_tree_search.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
