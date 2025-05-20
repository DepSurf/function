# Function: <code>register_one_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_one_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff81560bd0)
Location: drivers/base/node.c:568
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff81560bd0-ffffffff81560de2: register_one_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_one_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815b5310)
Location: drivers/base/node.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff815b5310-ffffffff815b5522: register_one_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_one_node(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/node.c (ffffffff815e45e0)
Location: drivers/base/node.c:579
Inline: False
Direct callers:
  - arch/x86/kernel/topology.c:topology_init
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:try_online_node
```
**Symbols:**

```
ffffffff815e45e0-ffffffff815e480e: register_one_node (STB_GLOBAL)
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
In arch/x86/kernel/topology.c (ffffffff820ac686)
Location: include/linux/node.h:48
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff8122d162)
Location: include/linux/node.h:48
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/kernel/topology.c (ffffffff826b2ea8)
Location: include/linux/node.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff81248a1b)
Location: include/linux/node.h:49
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/kernel/topology.c (ffffffff826dc671)
Location: include/linux/node.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff8126c44b)
Location: include/linux/node.h:51
Inline: True
Inline callers:
  - mm/memory_hotplug.c:try_online_node
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
In arch/x86/kernel/topology.c (ffffffff82892a4b)
Location: include/linux/node.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff81280361)
Location: include/linux/node.h:51
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff828a9f93)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff8129c6a3)
Location: include/linux/node.h:118
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff828acff6)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812ac343)
Location: include/linux/node.h:118
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff82cd23a1)
Location: include/linux/node.h:120
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812e0cd1)
Location: include/linux/node.h:120
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff82fbe1e8)
Location: include/linux/node.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812ebad1)
Location: include/linux/node.h:119
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff831c88f0)
Location: include/linux/node.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812c62bb)
Location: include/linux/node.h:119
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff832a9b2e)
Location: include/linux/node.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff8130b0ab)
Location: include/linux/node.h:119
Inline: True
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
In mm/memory_hotplug.c (ffffffff81373a51)
Location: include/linux/node.h:120
Inline: True
```
```
In drivers/base/node.c (ffffffff834baa72)
Location: include/linux/node.h:120
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
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
In mm/memory_hotplug.c (ffffffff813f160d)
Location: include/linux/node.h:114
Inline: True
```
```
In drivers/base/node.c (ffffffff83ef8397)
Location: include/linux/node.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
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
In mm/memory_hotplug.c (ffffffff8142514f)
Location: include/linux/node.h:114
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__try_online_node
```
```
In drivers/base/node.c (ffffffff8371df37)
Location: include/linux/node.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
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
In mm/memory_hotplug.c (ffffffff8145238f)
Location: include/linux/node.h:114
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__try_online_node
```
```
In drivers/base/node.c (ffffffff83951907)
Location: include/linux/node.h:114
Inline: True
Inline callers:
  - drivers/base/node.c:node_dev_init
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
In arch/arm64/kernel/setup.c (ffff800011433e44)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/arm64/kernel/setup.c:topology_init
```
```
In mm/memory_hotplug.c (ffff80001034dbf0)
Location: include/linux/node.h:118
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/sysfs.c (c000000001348844)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/powerpc/kernel/sysfs.c:topology_init
```
```
In mm/memory_hotplug.c (c00000000042dd24)
Location: include/linux/node.h:118
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/topology.c (ffffffff8289b008)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812a4923)
Location: include/linux/node.h:118
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff828932c6)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812963f3)
Location: include/linux/node.h:118
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff828adfe8)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812a2733)
Location: include/linux/node.h:118
Inline: True
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
In arch/x86/kernel/topology.c (ffffffff828ae006)
Location: include/linux/node.h:118
Inline: True
Inline callers:
  - arch/x86/kernel/topology.c:topology_init
```
```
In mm/memory_hotplug.c (ffffffff812b2a93)
Location: include/linux/node.h:118
Inline: True
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
</ul>
