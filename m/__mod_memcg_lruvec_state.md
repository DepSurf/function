# Function: <code>__mod_memcg_lruvec_state</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306040)
Location: mm/memcontrol.c:798
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/memcontrol.c:__mod_lruvec_state
```
**Symbols:**

```
ffffffff81306040-ffffffff81306127: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130c4f0)
Location: mm/memcontrol.c:686
Inline: False
Direct callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
  - mm/memcontrol.c:__mod_lruvec_state
```
**Symbols:**

```
ffffffff8130c4f0-ffffffff8130c5cf: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81356470)
Location: mm/memcontrol.c:721
Inline: False
Direct callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__mod_lruvec_state
```
**Symbols:**

```
ffffffff81356470-ffffffff81356543: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cf2e0)
Location: mm/memcontrol.c:695
Inline: False
Direct callers:
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mod_memcg_lruvec_state
```
**Symbols:**

```
ffffffff813cf2e0-ffffffff813cf3c5: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81454560)
Location: mm/memcontrol.c:765
Inline: False
Direct callers:
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mod_memcg_lruvec_state
```
**Symbols:**

```
ffffffff81454560-ffffffff81454657: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148a330)
Location: mm/memcontrol.c:790
Inline: False
Direct callers:
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mod_memcg_lruvec_state
```
**Symbols:**

```
ffffffff8148a330-ffffffff8148a450: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b9b60)
Location: mm/memcontrol.c:838
Inline: False
Direct callers:
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mod_memcg_lruvec_state
```
**Symbols:**

```
ffffffff814b9b60-ffffffff814b9cfc: __mod_memcg_lruvec_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
