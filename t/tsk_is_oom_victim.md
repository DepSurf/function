# Function: <code>tsk_is_oom_victim</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b546b)
Location: include/linux/oom.h:61
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd185)
Location: include/linux/oom.h:63
Inline: True
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
In kernel/cgroup/cpuset.c (ffffffff8113d5a6)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff811d1d95)
Location: include/linux/oom.h:64
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d7b3b)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff8125cdf1)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/cgroup/cpuset.c (ffffffff8114bebe)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff811f2b83)
Location: include/linux/oom.h:64
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f8d14)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff81281827)
Location: include/linux/oom.h:64
Inline: True
Inline callers:
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
In kernel/cgroup/cpuset.c (ffffffff81158b0e)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81204ba3)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120bda4)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff81298805)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
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
In kernel/cgroup/cpuset.c (ffffffff811651f8)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff8121bf51)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271f3b)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812b3b65)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff811710d8)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff812298e1)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff81280396)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812c5477)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff81182df2)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81256601)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b4a10)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812fb0ca)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff8117fd54)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81261211)
Location: include/linux/oom.h:75
Inline: True
```
```
In mm/page_alloc.c (ffffffff81be7d30)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff81306f59)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff81180834)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81266291)
Location: include/linux/oom.h:75
Inline: True
```
```
In mm/page_alloc.c (ffffffff81bd9b27)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff8130d5d4)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff811a8624)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff812a2ab7)
Location: include/linux/oom.h:75
Inline: True
```
```
In mm/page_alloc.c (ffffffff81cbd9eb)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff81358781)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff811d9799)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff812fa8a7)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_alloc.c (ffffffff81e6f858)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff813d271d)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff8121ebb9)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81365067)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_alloc.c (ffffffff813ebd71)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff81457ea0)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff81234ca9)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81397527)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_alloc.c (ffffffff81420d7c)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff8148dbe2)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff8124e8c9)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff813c1357)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_evaluate_task
```
```
In mm/page_alloc.c (ffffffff8144db3c)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff814bd552)
Location: include/linux/oom.h:75
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffff8000101e46bc)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffff8000102b7628)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffff80001031828c)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffff80001036835c)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (c0425598)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (c04e42dc)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (c0532840)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (c05597dc)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (c000000000254e4c)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (c00000000036f318)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (c0000000003ea990)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (c000000000455fb4)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffe00015a96c)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffe0001db984)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021e0d2)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffe0002460f0)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff811696f8)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff81221f31)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff812789e6)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812bda57)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff8115c8f8)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff812150e1)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126a8d6)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812aeb7c)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff811674c8)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff8121fcd1)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff81276786)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812bb867)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
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
In kernel/cgroup/cpuset.c (ffffffff81174b3a)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:__cpuset_node_allowed
```
```
In mm/oom_kill.c (ffffffff8122edb1)
Location: include/linux/oom.h:74
Inline: True
```
```
In mm/page_alloc.c (ffffffff81286346)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:warn_alloc
```
```
In mm/memcontrol.c (ffffffff812cc017)
Location: include/linux/oom.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_out_of_memory
```
</details>
</li>
</ul>

## Differences
