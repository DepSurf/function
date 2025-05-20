# Function: <code>pci_bus_distribute_available_resources</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f65a0)
Location: drivers/pci/setup-bus.c:1881
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff814f65a0-ffffffff814f6c79: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815272a0)
Location: drivers/pci/setup-bus.c:1876
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff815272a0-ffffffff815277f3: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153d140)
Location: drivers/pci/setup-bus.c:1878
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8153d140-ffffffff8153d688: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156c770)
Location: drivers/pci/setup-bus.c:1842
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8156c770-ffffffff8156cd2f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8158d750)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8158d750-ffffffff8158dd0f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81634ad0)
Location: drivers/pci/setup-bus.c:1886
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
```
**Symbols:**

```
ffffffff81634ad0-ffffffff81635216: pci_bus_distribute_available_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81659b80)
Location: drivers/pci/setup-bus.c:1887
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
```
**Symbols:**

```
ffffffff81659b80-ffffffff8165a2da: pci_bus_distribute_available_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163bfd0)
Location: drivers/pci/setup-bus.c:1887
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
```
**Symbols:**

```
ffffffff8163bfd0-ffffffff8163c71e: pci_bus_distribute_available_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816aca20)
Location: drivers/pci/setup-bus.c:1887
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
```
**Symbols:**

```
ffffffff816aca20-ffffffff816ad178: pci_bus_distribute_available_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817cfea0)
Location: drivers/pci/setup-bus.c:1887
Inline: True
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
```
**Symbols:**

```
ffffffff817cfea0-ffffffff817d05ca: pci_bus_distribute_available_resources.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, struct resource io, struct resource mmio, struct resource mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818efed0)
Location: drivers/pci/setup-bus.c:1832
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff818efed0-ffffffff818f06e7: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, struct resource io, struct resource mmio, struct resource mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81933400)
Location: drivers/pci/setup-bus.c:1823
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff81933400-ffffffff81933b0e: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, struct resource io, struct resource mmio, struct resource mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197c150)
Location: drivers/pci/setup-bus.c:1833
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bridge_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8197c150-ffffffff8197c883: pci_bus_distribute_available_resources (STB_LOCAL)
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
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f2a50)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffff8000106f2a50-ffff8000106f2fec: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088d544)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
c088d544-c088da84: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c000000000870c10)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
c000000000870c10-c0000000008711e0: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5f9c)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffe0004c5f9c-ffffffe0004c63d4: pci_bus_distribute_available_resources (STB_LOCAL)
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
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815815d0)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff815815d0-ffffffff81581b8f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815703b0)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff815703b0-ffffffff8157096f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815814a0)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff815814a0-ffffffff81581a5f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_bus_distribute_available_resources(struct pci_bus *bus, struct list_head *add_list, resource_size_t available_io, resource_size_t available_mmio, resource_size_t available_mmio_pref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8159b950)
Location: drivers/pci/setup-bus.c:1848
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8159b950-ffffffff8159bf0f: pci_bus_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
