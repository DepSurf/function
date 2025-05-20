# Function: <code>add_to_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8143e850)
Location: drivers/pci/setup-bus.c:63
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff8143e850-ffffffff8143e8e6: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8148a6c0)
Location: drivers/pci/setup-bus.c:62
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8148a6c0-ffffffff8148a756: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814abeb0)
Location: drivers/pci/setup-bus.c:63
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff814abeb0-ffffffff814abf46: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814b61e0)
Location: drivers/pci/setup-bus.c:63
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff814b61e0-ffffffff814b6276: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff814f5c50)
Location: drivers/pci/setup-bus.c:63
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff814f5c50-ffffffff814f5ce6: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81526950)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff81526950-ffffffff815269da: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8153c3b0)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8153c3b0-ffffffff8153c43a: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156bb40)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8156bb40-ffffffff8156bbc8: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8158cb20)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8158cb20-ffffffff8158cba8: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81634000)
Location: drivers/pci/setup-bus.c:59
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff81634000-ffffffff81634088: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816590b0)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff816590b0-ffffffff81659138: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8163b520)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8163b520-ffffffff8163b5a8: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff816abf50)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff816abf50-ffffffff816abfd8: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff817cf360)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff817cf360-ffffffff817cf3f7: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff818ef230)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff818ef230-ffffffff818ef2c7: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81932700)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff81932700-ffffffff81932797: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197b550)
Location: drivers/pci/setup-bus.c:60
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8197b550-ffffffff8197b616: add_to_list (STB_LOCAL)
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
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffff8000106f1c78)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffff8000106f1c78-ffff8000106f1d0c: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c088c6ec)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
c088c6ec-c088c77c: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (c00000000086ff70)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
c00000000086ff70-c000000000870044: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffe0004c5412)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffe0004c5412-ffffffe0004c5496: add_to_list (STB_LOCAL)
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
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff815809a0)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff815809a0-ffffffff81580a28: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8156f780)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8156f780-ffffffff8156f808: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff81580870)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff81580870-ffffffff815808f8: add_to_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_to_list(struct list_head *head, struct pci_dev *dev, struct resource *res, resource_size_t add_size, resource_size_t min_align);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8159ad20)
Location: drivers/pci/setup-bus.c:58
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:assign_requested_resources_sorted
```
**Symbols:**

```
ffffffff8159ad20-ffffffff8159ada8: add_to_list (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
