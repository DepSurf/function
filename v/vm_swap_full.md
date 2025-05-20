# Function: <code>vm_swap_full</code>

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
In mm/vmscan.c (ffffffff811a301d)
Location: include/linux/swap.h:420
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/memory.c (ffffffff811bff79)
Location: include/linux/swap.h:420
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/swapfile.c (ffffffff811d4b58)
Location: include/linux/swap.h:420
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:free_swap_and_cache
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
In mm/swapfile.c (ffffffff811f2a3f)
Location: include/linux/swap.h:390
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
```
```
In mm/memcontrol.c (ffffffff81224c35)
Location: include/linux/swap.h:390
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff812034af)
Location: include/linux/swap.h:365
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
  - mm/swapfile.c:scan_swap_map
```
```
In mm/memcontrol.c (ffffffff81237225)
Location: include/linux/swap.h:365
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e932)
Location: include/linux/swap.h:380
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff81242ce5)
Location: include/linux/swap.h:380
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8122a094)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff81262b35)
Location: include/linux/swap.h:450
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8124b324)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff81286ce5)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8125fb06)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff8129bbf5)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8127a746)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812b6dd5)
Location: include/linux/swap.h:436
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8128a226)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812c8ca5)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff812bcec0)
Location: include/linux/swap.h:445
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812fe2d5)
Location: include/linux/swap.h:445
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff812c89e0)
Location: include/linux/swap.h:446
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff8130a805)
Location: include/linux/swap.h:446
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff812cf41f)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff81310e55)
Location: include/linux/swap.h:472
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff813149c5)
Location: include/linux/swap.h:479
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff8135c145)
Location: include/linux/swap.h:479
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8137ffe7)
Location: include/linux/swap.h:467
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff813d5a85)
Location: include/linux/swap.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff813fe937)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff8145b4d5)
Location: include/linux/swap.h:473
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff81431887)
Location: include/linux/swap.h:468
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff81491145)
Location: include/linux/swap.h:468
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff8146ac77)
Location: include/linux/swap.h:460
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff814c0ab5)
Location: include/linux/swap.h:460
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffff8000103251b0)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffff80001036bb78)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (c053cbf0)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (c055d1f8)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (c0000000003fb410)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (c00000000045b830)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffe00022573e)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffe00024915e)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff81282806)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812c1285)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff81274326)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812b22d5)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff81280616)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812bf095)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
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
In mm/swapfile.c (ffffffff812903b6)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
  - mm/swapfile.c:scan_swap_map_slots
```
```
In mm/memcontrol.c (ffffffff812cfb05)
Location: include/linux/swap.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
```
</details>
</li>
</ul>

## Differences
