# Function: <code>pci_bridge_distribute_available_resources</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f82ff)
Location: drivers/pci/setup-bus.c:2005
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff81528e5f)
Location: drivers/pci/setup-bus.c:2000
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff8153ecff)
Location: drivers/pci/setup-bus.c:2002
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff8156e15f)
Location: drivers/pci/setup-bus.c:1968
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff8158f13f)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81635220)
Location: drivers/pci/setup-bus.c:2030
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff81635220-ffffffff8163526b: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8165a2e0)
Location: drivers/pci/setup-bus.c:2031
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8165a2e0-ffffffff8165a32b: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163c720)
Location: drivers/pci/setup-bus.c:2031
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff8163c720-ffffffff8163c76b: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816ad180)
Location: drivers/pci/setup-bus.c:2031
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff816ad180-ffffffff816ad1cb: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817d05d0)
Location: drivers/pci/setup-bus.c:2031
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
**Symbols:**

```
ffffffff817d05d0-ffffffff817d0643: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818f0700)
Location: drivers/pci/setup-bus.c:1970
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff818f0700-ffffffff818f08fc: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81933b20)
Location: drivers/pci/setup-bus.c:1961
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff81933b20-ffffffff81933d1c: pci_bridge_distribute_available_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_bridge_distribute_available_resources(struct pci_dev *bridge, struct list_head *add_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197c8a0)
Location: drivers/pci/setup-bus.c:1971
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
  - drivers/pci/setup-bus.c:pci_root_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8197c8a0-ffffffff8197ca9c: pci_bridge_distribute_available_resources (STB_LOCAL)
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
In drivers/pci/setup-bus.c (ffff8000106f4480)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (c088ef04)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (c000000000872b94)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffe0004c75c2)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff81582fbf)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff81571d9f)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff81582e8f)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
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
In drivers/pci/setup-bus.c (ffffffff8159d33f)
Location: drivers/pci/setup-bus.c:1974
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:pci_assign_unassigned_bridge_resources
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
