# Function: <code>mod_memcg_lruvec_state</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e6a8e)
Location: include/linux/memcontrol.h:983
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ee261)
Location: include/linux/memcontrol.h:1028
Inline: True
Inline callers:
  - mm/slub.c:kfree
  - mm/slub.c:kmem_cache_free
  - mm/slub.c:memcg_slab_post_alloc_hook
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
In mm/memcontrol.c (ffffffff813565e3)
Location: include/linux/memcontrol.h:1020
Inline: True
Inline callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cf3d0)
Location: include/linux/memcontrol.h:1044
Inline: False
Direct callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
```
**Symbols:**

```
ffffffff813cf3d0-ffffffff813cf406: mod_memcg_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81454670)
Location: include/linux/memcontrol.h:1044
Inline: False
Direct callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
```
**Symbols:**

```
ffffffff81454670-ffffffff814546c3: mod_memcg_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148a460)
Location: include/linux/memcontrol.h:1060
Inline: False
Direct callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
```
**Symbols:**

```
ffffffff8148a460-ffffffff8148a4b3: mod_memcg_lruvec_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_memcg_lruvec_state(struct lruvec *lruvec, enum node_stat_item idx, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b9d10)
Location: include/linux/memcontrol.h:1077
Inline: False
Direct callers:
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:mod_objcg_state
```
**Symbols:**

```
ffffffff814b9d10-ffffffff814b9d63: mod_memcg_lruvec_state (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
