# Function: <code>memcg_from_slab_page</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812495a1)
Location: mm/slab.h:268
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812b2805)
Location: mm/slab.h:268
Inline: True
Inline callers:
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff812579f1)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812c6f38)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc858)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:page_cgroup_ino
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffff8000102ef558)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffff800010369d00)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0512fa0)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (c055b054)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (c0000000003b3b94)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (c000000000458880)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffe000203234)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffe000247574)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81250041)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812bf518)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff81242fe1)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812b0608)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8124dde1)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812bd328)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/list_lru.c (ffffffff8125d78c)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/list_lru.c:list_lru_del
  - mm/list_lru.c:list_lru_add
```
```
In mm/memcontrol.c (ffffffff812cdb88)
Location: mm/slab.h:332
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_from_obj
  - mm/memcontrol.c:__mod_lruvec_slab_state
  - mm/memcontrol.c:page_cgroup_ino
```
</details>
</li>
</ul>

## Differences
