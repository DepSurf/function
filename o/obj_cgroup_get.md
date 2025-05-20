# Function: <code>obj_cgroup_get</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e4233)
Location: include/linux/memcontrol.h:717
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813044c5)
Location: include/linux/memcontrol.h:717
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ec490)
Location: include/linux/memcontrol.h:802
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8130bfc5)
Location: include/linux/memcontrol.h:802
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813343f1)
Location: include/linux/memcontrol.h:798
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813572bf)
Location: include/linux/memcontrol.h:798
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a5f23)
Location: include/linux/memcontrol.h:799
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff813d01ca)
Location: include/linux/memcontrol.h:799
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff814270e3)
Location: include/linux/memcontrol.h:781
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8145553e)
Location: include/linux/memcontrol.h:781
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8145c083)
Location: include/linux/memcontrol.h:794
Inline: True
Inline callers:
  - mm/slub.c:memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff8148b361)
Location: include/linux/memcontrol.h:794
Inline: True
Inline callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:get_obj_cgroup_from_page
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8131061f)
Location: include/linux/memcontrol.h:809
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
```
```
In kernel/bpf/memalloc.c (ffffffff81372d35)
Location: include/linux/memcontrol.h:809
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
  - kernel/bpf/memalloc.c:bpf_mem_alloc_init
```
```
In mm/percpu.c (ffffffff813fa0d8)
Location: include/linux/memcontrol.h:809
Inline: True
```
```
In mm/slub.c (ffffffff81455cbd)
Location: include/linux/memcontrol.h:809
Inline: True
Inline callers:
  - mm/slub.c:__memcg_slab_post_alloc_hook
```
```
In mm/memcontrol.c (ffffffff814b4de2)
Location: include/linux/memcontrol.h:809
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_folio
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
