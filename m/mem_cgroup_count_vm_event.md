# Function: <code>mem_cgroup_count_vm_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118fadd)
Location: include/linux/memcontrol.h:469
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff811aae12)
Location: include/linux/memcontrol.h:469
Inline: True
Inline callers:
  - mm/shmem.c:shmem_fault
```
```
In mm/memory.c (ffffffff811bec1d)
Location: include/linux/memcontrol.h:469
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In fs/dax.c (ffffffff8125ddf2)
Location: include/linux/memcontrol.h:469
Inline: True
Inline callers:
  - fs/dax.c:__dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a3a43)
Location: include/linux/memcontrol.h:518
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff811c0f6c)
Location: include/linux/memcontrol.h:518
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff811daa85)
Location: include/linux/memcontrol.h:518
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff81287ec8)
Location: include/linux/memcontrol.h:518
Inline: True
Inline callers:
  - fs/dax.c:dax_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b3d9f)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - mm/filemap.c:filemap_fault
```
```
In mm/shmem.c (ffffffff811d156b)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
```
```
In mm/memory.c (ffffffff811ea5f9)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
```
```
In fs/dax.c (ffffffff8129c825)
Location: include/linux/memcontrol.h:536
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
</details>
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
