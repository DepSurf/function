# Function: <code>adjust_bridge_window</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81634730)
Location: drivers/pci/setup-bus.c:1860
Inline: False
```
**Symbols:**

```
ffffffff81634730-ffffffff8163486a: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816597e0)
Location: drivers/pci/setup-bus.c:1861
Inline: False
```
**Symbols:**

```
ffffffff816597e0-ffffffff8165991a: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163bc50)
Location: drivers/pci/setup-bus.c:1861
Inline: False
```
**Symbols:**

```
ffffffff8163bc50-ffffffff8163bd8a: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816ac680)
Location: drivers/pci/setup-bus.c:1861
Inline: False
```
**Symbols:**

```
ffffffff816ac680-ffffffff816ac7b7: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817cfad0)
Location: drivers/pci/setup-bus.c:1861
Inline: False
```
**Symbols:**

```
ffffffff817cfad0-ffffffff817cfc23: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818efd70)
Location: drivers/pci/setup-bus.c:1748
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff818efd70-ffffffff818efebf: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff819332a0)
Location: drivers/pci/setup-bus.c:1741
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff819332a0-ffffffff819333ef: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void adjust_bridge_window(struct pci_dev *bridge, struct resource *res, struct list_head *add_list, resource_size_t new_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197b1e0)
Location: drivers/pci/setup-bus.c:1751
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
```
**Symbols:**

```
ffffffff8197b1e0-ffffffff8197b32f: adjust_bridge_window (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
