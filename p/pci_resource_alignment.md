# Function: <code>pci_resource_alignment</code>

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
In drivers/pci/setup-res.c (ffffffff8143d72a)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8143ee07)
Location: drivers/pci/pci.h:309
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
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
In drivers/pci/setup-res.c (ffffffff81489586)
Location: drivers/pci/pci.h:319
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8148b9d6)
Location: drivers/pci/pci.h:319
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff814aad76)
Location: drivers/pci/pci.h:314
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814ad1c6)
Location: drivers/pci/pci.h:314
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff814b5066)
Location: drivers/pci/pci.h:326
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814b758c)
Location: drivers/pci/pci.h:326
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff814f4a66)
Location: drivers/pci/pci.h:329
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff814f66ee)
Location: drivers/pci/pci.h:329
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff81524b23)
Location: drivers/pci/pci.h:355
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff815274cc)
Location: drivers/pci/pci.h:355
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8153a9a3)
Location: drivers/pci/pci.h:456
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8153d36c)
Location: drivers/pci/pci.h:456
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8156a312)
Location: drivers/pci/pci.h:461
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8156c99d)
Location: drivers/pci/pci.h:461
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8158b2e2)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8158d97d)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8163227a)
Location: drivers/pci/pci.h:521
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81635e6b)
Location: drivers/pci/pci.h:521
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8165789a)
Location: drivers/pci/pci.h:539
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8165af2b)
Location: drivers/pci/pci.h:539
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8163a202)
Location: drivers/pci/pci.h:537
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8163d473)
Location: drivers/pci/pci.h:537
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff816aaa12)
Location: drivers/pci/pci.h:558
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff816adf17)
Location: drivers/pci/pci.h:558
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff817cd975)
Location: drivers/pci/pci.h:519
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff817d13ba)
Location: drivers/pci/pci.h:519
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff818ecfe4)
Location: drivers/pci/pci.h:521
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff818f024c)
Location: drivers/pci/pci.h:521
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff819304c4)
Location: drivers/pci/pci.h:520
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff81933726)
Location: drivers/pci/pci.h:520
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff81978e6f)
Location: drivers/pci/pci.h:524
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8197c49b)
Location: drivers/pci/pci.h:524
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffff8000106f00d0)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffff8000106f2c68)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (c088ac3c)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (c088d7b0)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (c00000000086d5dc)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (c000000000870f38)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffe0004c3d64)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffe0004c60c4)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8157f162)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff815817fd)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8156df42)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff815705dd)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff8157f032)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff815816cd)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
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
In drivers/pci/setup-res.c (ffffffff815994e2)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_assign_resource
```
```
In drivers/pci/setup-bus.c (ffffffff8159bb7d)
Location: drivers/pci/pci.h:496
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
</details>
</li>
</ul>

## Differences
