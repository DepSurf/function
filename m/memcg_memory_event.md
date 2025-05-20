# Function: <code>memcg_memory_event</code>

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
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f3cb7)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
```
```
In mm/vmscan.c (ffffffff8120b3cb)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff81286601)
Location: include/linux/memcontrol.h:729
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
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
In mm/oom_kill.c (ffffffff81204949)
Location: include/linux/memcontrol.h:769
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8121e0b3)
Location: include/linux/memcontrol.h:769
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff8129b56e)
Location: include/linux/memcontrol.h:769
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121c0c0)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8122d746)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812b6753)
Location: include/linux/memcontrol.h:749
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812ae7f0-ffffffff812ae858: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81229a52)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8123b928)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812c8623)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812c0200-ffffffff812c0268: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812568a5)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812689f1)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff812fdf0a)
Location: include/linux/memcontrol.h:764
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812f5410-ffffffff812f547b: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8126143b)
Location: include/linux/memcontrol.h:1035
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81273462)
Location: include/linux/memcontrol.h:1035
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff8130a3ac)
Location: include/linux/memcontrol.h:1035
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff81300a70-ffffffff81300aff: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81265c77)
Location: include/linux/memcontrol.h:1076
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81278782)
Location: include/linux/memcontrol.h:1076
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff81310c45)
Location: include/linux/memcontrol.h:1076
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffffffff81307240-ffffffff813072cf: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a24a4)
Location: include/linux/memcontrol.h:1068
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812b64dc)
Location: include/linux/memcontrol.h:1068
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff8135bf09)
Location: include/linux/memcontrol.h:1068
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:try_charge_memcg
```
**Symbols:**

```
ffffffff81350eb0-ffffffff81350f75: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fa40c)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8131197e)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff813d5802)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff813c95f0-ffffffff813c96b6: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81364b7c)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81384fa9)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/memcontrol.c (ffffffff8145b29d)
Location: include/linux/memcontrol.h:1101
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff8144e920-ffffffff8144e9e6: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8139703c)
Location: include/linux/memcontrol.h:1117
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813b6b09)
Location: include/linux/memcontrol.h:1117
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
```
```
In mm/memcontrol.c (ffffffff81490f0d)
Location: include/linux/memcontrol.h:1117
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff814843e0-ffffffff814844a6: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0db0)
Location: include/linux/memcontrol.h:1125
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff813df9c9)
Location: include/linux/memcontrol.h:1125
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
```
```
In mm/memcontrol.c (ffffffff814c087a)
Location: include/linux/memcontrol.h:1125
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff814b3960-ffffffff814b3a26: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b782c)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccb40)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffff800010365d38)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_max_write
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
```
**Symbols:**

```
ffff8000103648b0-ffff800010364968: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4478)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c04f67ac)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (c055cc30)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
c0554544-c05545e8: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036f630)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c00000000038a340)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (c00000000045af90)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
c00000000044de60-c00000000044df30: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dbb2c)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffe0001eb35a)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffe000248c06)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffe0002414de-ffffffe000241572: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812220a2)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81233f78)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812c0c03)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812b87e0-ffffffff812b8848: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81215252)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81226fe8)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812b1c7b)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812a99b0-ffffffff812a9a18: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121fe42)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81231d18)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812bea13)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812b65f0-ffffffff812b6658: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void memcg_memory_event(struct mem_cgroup *memcg, enum memcg_memory_event event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ef27)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81241178)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/memcontrol.c (ffffffff812cf483)
Location: include/linux/memcontrol.h:786
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
Direct callers:
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
```
**Symbols:**

```
ffffffff812c6dc0-ffffffff812c6e28: memcg_memory_event (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
