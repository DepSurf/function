# Function: <code>rb_last</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff813efde0)
Location: lib/rbtree.c:463
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff813efde0-ffffffff813efe00: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff814366b0)
Location: lib/rbtree.c:463
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff814366b0-ffffffff814366cc: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff814536a0)
Location: lib/rbtree.c:478
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff814536a0-ffffffff814536bc: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff818f3910)
Location: lib/rbtree.c:480
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_service_tree_add
  - drivers/iommu/iova.c:alloc_iova
```
**Symbols:**

```
ffffffff818f3910-ffffffff818f392c: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819799c0)
Location: lib/rbtree.c:515
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819799c0-ffffffff819799dc: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff819d6280)
Location: lib/rbtree.c:515
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff819d6280-ffffffff819d6298: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a0e4b0)
Location: lib/rbtree.c:515
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
```
**Symbols:**

```
ffffffff81a0e4b0-ffffffff81a0e4c8: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a7d8d0)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81a7d8d0-ffffffff81a7d8ed: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81ab4c00)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81ab4c00-ffffffff81ab4c1d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815ef840)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff815ef840-ffffffff815ef85d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81613fa0)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_input.c:tcp_collapse_ofo_queue
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81613fa0-ffffffff81613fbd: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff815f7600)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff815f7600-ffffffff815f761d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81664d90)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81664d90-ffffffff81664dad: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8177f220)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:generic_get_unmapped_area_topdown
  - mm/mmap.c:generic_get_unmapped_area
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff8177f220-ffffffff8177f244: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff8203bee0)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff8203bee0-ffffffff8203bf04: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff820ba450)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff820ba450-ffffffff820ba474: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff82194d60)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff82194d60-ffffffff82194d84: rb_last (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffff800010d8f520)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffff800010d8f520-ffff800010d8f540: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c0e89cc4)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
c0e89cc4-c0e89cf8: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (c000000000ed2130)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
c000000000ed2130-c000000000ed216c: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffe0008b7c2a)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffe0008b7c2a-ffffffe0008b7c44: rb_last (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a53a50)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81a53a50-ffffffff81a53a6d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81a10b30)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81a10b30-ffffffff81a10b4d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81abfe40)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81abfe40-ffffffff81abfe5d: rb_last (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rb_node *rb_last(const struct rb_root *root);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rbtree.c (ffffffff81acc310)
Location: lib/rbtree.c:479
Inline: False
Direct callers:
  - kernel/sched/fair.c:__pick_last_entity
  - mm/mmap.c:find_vma_prev
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:tcp_send_loss_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
**Symbols:**

```
ffffffff81acc310-ffffffff81acc32d: rb_last (STB_GLOBAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
