# Function: <code>rwsem_is_contended</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120645c)
Location: include/linux/rwsem.h:112
Inline: True
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
In mm/vmscan.c (ffffffff81218fe4)
Location: include/linux/rwsem.h:112
Inline: True
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
In mm/vmscan.c (ffffffff81228f9f)
Location: include/linux/rwsem.h:109
Inline: True
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
In mm/vmscan.c (ffffffff81236d3f)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffff81266bfe)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127164e)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff813c9122)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff8121bfae)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/vmscan.c (ffffffff8127685e)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff813d01ef)
Location: include/linux/rwsem.h:117
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81252eae)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/vmscan.c (ffffffff812b407b)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff8142180f)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff8129b03e)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/vmscan.c (ffffffff8131002d)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff81498667)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff812f7374)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/vmscan.c (ffffffff8138363d)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff8152c9b9)
Location: include/linux/rwsem.h:119
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81325244)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In mm/vmscan.c (ffffffff813b4e6d)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_slab
  - mm/vmscan.c:shrink_slab_memcg
```
```
In fs/proc/task_mmu.c (ffffffff815657cb)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In kernel/bpf/task_iter.c (ffffffff81349454)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_vma_seq_get_next
```
```
In fs/proc/task_mmu.c (ffffffff8159c99d)
Location: include/linux/rwsem.h:120
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:show_smaps_rollup
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
In mm/vmscan.c (ffff8000102c8358)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (c04f1b20)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (c000000000382cb0)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffe0001e6dcc)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffff8122f38f)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffff8122244f)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffff8122d12f)
Location: include/linux/rwsem.h:119
Inline: True
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
In mm/vmscan.c (ffffffff8123c56f)
Location: include/linux/rwsem.h:119
Inline: True
```
</details>
</li>
</ul>

## Differences
