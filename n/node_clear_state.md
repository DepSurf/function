# Function: <code>node_clear_state</code>

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
In arch/x86/mm/init_64.c (ffffffff81f77c4e)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff811ad8b9)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/memory_hotplug.c (ffffffff811efaf7)
Location: include/linux/nodemask.h:408
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
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
In arch/x86/mm/init_64.c (ffffffff81fa0394)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff811c6b05)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpuup_callback
```
```
In mm/memory_hotplug.c (ffffffff8120ef49)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
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
In arch/x86/mm/init_64.c (ffffffff81fdb8fe)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff811d6c6c)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff8122104d)
Location: include/linux/nodemask.h:417
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
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
In arch/x86/mm/init_64.c (ffffffff820bc8d2)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff811dfacc)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff8122c914)
Location: include/linux/nodemask.h:413
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
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
In arch/x86/mm/init_64.c (ffffffff826c331f)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff811f58dc)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81248148)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff826ed543)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff81216b5c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff8126ba7c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828a40d5)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff81229a6c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81a21dc9)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828bc573)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff8123970c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81a9242d)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828c2a1a)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff81247a0c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812abce0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff82ce5e37)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff81275bf6)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812e05e0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
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
In arch/x86/mm/init_64.c (ffffffff82fd37b8)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff812804d6)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812ebdc0)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
  - mm/memory_hotplug.c:node_states_clear_node
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
In arch/x86/mm/init_64.c (ffffffff831de3e8)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff812855d6)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812c6738)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In arch/x86/mm/init_64.c (ffffffff832c1676)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff812c3f8a)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff8130b19e)
Location: include/linux/nodemask.h:424
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In arch/x86/mm/init_64.c (ffffffff83473d05)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff813217b5)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81373c2f)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In arch/x86/mm/init_64.c (ffffffff83e9b93e)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff813957c5)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff813f1378)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In arch/x86/mm/init_64.c (ffffffff836bf3de)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff813c83e5)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81424eb8)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In arch/x86/mm/init_64.c (ffffffff838efe7e)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff813f2dd5)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff814520f8)
Location: include/linux/nodemask.h:431
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:offline_pages
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
In mm/vmstat.c (ffff8000102dbf08)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
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
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:473
Inline: True
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
In mm/vmstat.c (c00000000039bab0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (c00000000042d5a8)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In mm/vmstat.c (0)
Location: include/linux/nodemask.h:473
Inline: True
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
In arch/x86/mm/init_64.c (ffffffff828ad9f0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff8124005c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812a42c0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828a5c8e)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff8123305c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff81295d90)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828c08ef)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff8123ddfc)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812a20d0)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
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
In arch/x86/mm/init_64.c (ffffffff828c3a3a)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:paging_init
  - arch/x86/mm/init_64.c:paging_init
```
```
In mm/vmstat.c (ffffffff8124d52c)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_cpu_dead
```
```
In mm/memory_hotplug.c (ffffffff812b2360)
Location: include/linux/nodemask.h:423
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_offline_node
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
</details>
</li>
</ul>

## Differences
