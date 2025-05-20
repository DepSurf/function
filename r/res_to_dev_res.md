# Function: <code>res_to_dev_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_dev_resource *res_to_dev_res(struct list_head *head, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e410)
Location: drivers/pci/setup-bus.c:102
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff8143e410-ffffffff8143e49b: res_to_dev_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_dev_resource *res_to_dev_res(struct list_head *head, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a280)
Location: drivers/pci/setup-bus.c:101
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8148a280-ffffffff8148a2f6: res_to_dev_res (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_dev_resource *res_to_dev_res(struct list_head *head, struct resource *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814aba70)
Location: drivers/pci/setup-bus.c:102
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff814aba70-ffffffff814abae6: res_to_dev_res (STB_LOCAL)
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
In drivers/pci/setup-bus.c (ffffffff814b7644)
Location: drivers/pci/setup-bus.c:102
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff814f7794)
Location: drivers/pci/setup-bus.c:102
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81528294)
Location: drivers/pci/setup-bus.c:97
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8153e136)
Location: drivers/pci/setup-bus.c:97
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8156d710)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8158e6f0)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81635d11)
Location: drivers/pci/setup-bus.c:95
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8165add1)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8163d31f)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff816addc3)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff817d1265)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff818f16bd)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81934ae2)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8197d83b)
Location: drivers/pci/setup-bus.c:96
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffff8000106f3a1c)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (c088e488)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (c000000000871ec0)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffe0004c6cd8)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81582570)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81571350)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81582440)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8159c8f0)
Location: drivers/pci/setup-bus.c:94
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
