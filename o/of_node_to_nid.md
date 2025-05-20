# Function: <code>of_node_to_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:682
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:734
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:854
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:880
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:933
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:956
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1008
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1025
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1040
Inline: True
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1045
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:867
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:866
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:899
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:898
Inline: True
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
int of_node_to_nid(struct device_node *np);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6a660)
Location: drivers/of/base.c:120
Inline: False
Direct callers:
  - arch/arm64/kernel/smp.c:smp_init_cpus
  - arch/arm64/kernel/smp.c:smp_init_cpus
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/irqchip/irq-gic-v3-its.c:its_init
  - drivers/irqchip/irq-gic-v3-its.c:its_cpu_init_collection
```
**Symbols:**

```
ffff800010b78ad8-ffff800010b78bdc: of_node_to_nid (STB_GLOBAL)
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (0)
Location: include/linux/of.h:1000
Inline: True
```
```
In drivers/of/device.c (0)
Location: include/linux/of.h:1000
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_node_to_nid(struct device_node *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/numa.c (c0000000000a1960)
Location: arch/powerpc/mm/numa.c:268
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_alloc_controller
  - arch/powerpc/platforms/pseries/vio.c:vio_register_device_node
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_mapping
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:__irq_domain_add
  - drivers/of/device.c:of_device_add
```
**Symbols:**

```
c0000000000a1960-c0000000000a1a20: of_node_to_nid (STB_GLOBAL)
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
Inline: True
```
```
In drivers/of/device.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
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
In kernel/irq/irqdomain.c (0)
Location: include/linux/of.h:1000
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
