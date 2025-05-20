# Function: <code>get_mem_cgroup_from_objcg</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130cda3)
Location: mm/memcontrol.c:2727
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
In mm/memcontrol.c (ffffffff8135771c)
Location: mm/memcontrol.c:2795
Inline: True
Inline callers:
  - mm/memcontrol.c:uncharge_page
  - mm/memcontrol.c:obj_cgroup_charge_pages
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
In mm/slub.c (ffffffff813a682e)
Location: include/linux/memcontrol.h:533
Inline: True
```
```
In mm/memcontrol.c (ffffffff813d5bc8)
Location: include/linux/memcontrol.h:533
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
In kernel/bpf/syscall.c (ffffffff812c5e7d)
Location: include/linux/memcontrol.h:511
Inline: True
```
```
In kernel/bpf/memalloc.c (ffffffff8131be56)
Location: include/linux/memcontrol.h:511
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/slub.c (ffffffff81427e0e)
Location: include/linux/memcontrol.h:511
Inline: True
```
```
In mm/memcontrol.c (ffffffff8145b5a8)
Location: include/linux/memcontrol.h:511
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
In kernel/bpf/syscall.c (ffffffff812ecddd)
Location: include/linux/memcontrol.h:524
Inline: True
```
```
In kernel/bpf/memalloc.c (ffffffff8134c508)
Location: include/linux/memcontrol.h:524
Inline: True
Inline callers:
  - kernel/bpf/memalloc.c:bpf_mem_cache_alloc_flags
  - kernel/bpf/memalloc.c:alloc_bulk
```
```
In mm/slub.c (ffffffff8145c84e)
Location: include/linux/memcontrol.h:524
Inline: True
```
```
In mm/memcontrol.c (ffffffff81491218)
Location: include/linux/memcontrol.h:524
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
In kernel/bpf/syscall.c (ffffffff8130b58d)
Location: include/linux/memcontrol.h:528
Inline: True
```
```
In kernel/bpf/memalloc.c (ffffffff81371e7d)
Location: include/linux/memcontrol.h:528
Inline: True
```
```
In mm/slub.c (ffffffff81454d89)
Location: include/linux/memcontrol.h:528
Inline: True
```
```
In mm/zswap.c (ffffffff814709d8)
Location: include/linux/memcontrol.h:528
Inline: True
Inline callers:
  - mm/zswap.c:zswap_store
  - mm/zswap.c:zswap_store
```
```
In mm/memcontrol.c (ffffffff814c0b88)
Location: include/linux/memcontrol.h:528
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:uncharge_folio
  - mm/memcontrol.c:obj_cgroup_charge
  - mm/memcontrol.c:drain_obj_stock
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:obj_cgroup_uncharge_pages
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
