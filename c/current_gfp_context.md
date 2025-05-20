# Function: <code>current_gfp_context</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c4e7d)
Location: include/linux/sched/mm.h:157
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811d52e7)
Location: include/linux/sched/mm.h:157
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d9c4d)
Location: include/linux/sched/mm.h:158
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff811ea817)
Location: include/linux/sched/mm.h:158
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811fa52d)
Location: include/linux/sched/mm.h:152
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8120bf8f)
Location: include/linux/sched/mm.h:152
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120cc9d)
Location: include/linux/sched/mm.h:152
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/vmscan.c (ffffffff8121ecd9)
Location: include/linux/sched/mm.h:152
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e3b9)
Location: include/linux/sched/mm.h:178
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff8127307d)
Location: include/linux/sched/mm.h:178
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff8123c549)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff81281eed)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812694bc)
Location: include/linux/sched/mm.h:182
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff8127af75)
Location: include/linux/sched/mm.h:182
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff812b17df)
Location: include/linux/sched/mm.h:182
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81273fee)
Location: include/linux/sched/mm.h:155
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff812859ac)
Location: include/linux/sched/mm.h:155
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff812bd15f)
Location: include/linux/sched/mm.h:155
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81278e30)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff8128a555)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff812c2006)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
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
In mm/vmscan.c (ffffffff812b6c0f)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff812ca975)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff81305980)
Location: include/linux/sched/mm.h:156
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
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
In mm/vmscan.c (ffffffff81312b0f)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff8132825c)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff81371e9f)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
```
```
In fs/ext4/extents.c (ffffffff814cbce4)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
```
```
In fs/ext4/inline.c (ffffffff814df4bd)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/page-io.c (ffffffff8150984c)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In mm/vmscan.c (ffffffff81385f55)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff8139d4cc)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff813ef6bf)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
```
```
In mm/huge_memory.c (ffffffff81441be0)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/ext4/extents.c (ffffffff815643a4)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
  - fs/ext4/extents.c:ext4_ext_truncate
```
```
In fs/ext4/inline.c (ffffffff815785d1)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/inline.c:ext4_inline_data_truncate
```
```
In fs/ext4/page-io.c (ffffffff815a443e)
Location: include/linux/sched/mm.h:203
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In mm/vmscan.c (ffffffff813b9222)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff813d05fc)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff8142323f)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
```
```
In mm/huge_memory.c (ffffffff81477587)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/ext4/extents.c (ffffffff8159c08c)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
```
```
In fs/ext4/page-io.c (ffffffff815dae40)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In mm/vmscan.c (ffffffff813e2222)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/percpu.c (ffffffff813fafbc)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
```
```
In mm/page_alloc.c (ffffffff8145016f)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages
```
```
In mm/huge_memory.c (ffffffff814a6cf8)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
```
In fs/ext4/extents.c (ffffffff815d4d3c)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_ext_truncate
```
```
In fs/ext4/page-io.c (ffffffff81613662)
Location: include/linux/sched/mm.h:235
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
```
</details>
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
In mm/vmscan.c (ffff8000102cd764)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffff80001031a674)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (c04f74bc)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (c0534c10)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (c00000000038b19c)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (c0000000003ed940)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffe0001ebc48)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffe00021fe28)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81234b99)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff8127a53d)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81227c09)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff8126c42d)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81232939)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff812782dd)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
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
In mm/vmscan.c (ffffffff81241df9)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
```
In mm/page_alloc.c (ffffffff81287ecd)
Location: include/linux/sched/mm.h:180
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:__alloc_pages_nodemask
  - mm/page_alloc.c:__alloc_pages_nodemask
```
</details>
</li>
</ul>

## Differences
