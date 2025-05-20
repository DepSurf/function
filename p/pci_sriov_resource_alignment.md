# Function: <code>pci_sriov_resource_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81457250)
Location: drivers/pci/iov.c:591
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
```
**Symbols:**

```
ffffffff81457250-ffffffff81457260: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814a3e50)
Location: drivers/pci/iov.c:587
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff814a3e50-ffffffff814a3e60: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814c5be0)
Location: drivers/pci/iov.c:630
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff814c5be0-ffffffff814c5bf0: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814cfc70)
Location: drivers/pci/iov.c:621
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff814cfc70-ffffffff814cfc80: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8150fe90)
Location: drivers/pci/iov.c:623
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff8150fe90-ffffffff8150fea0: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81544f60)
Location: drivers/pci/iov.c:667
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff81544f60-ffffffff81544f70: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155c330)
Location: drivers/pci/iov.c:692
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff8155c330-ffffffff8155c340: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158c540)
Location: drivers/pci/iov.c:690
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff8158c540-ffffffff8158c550: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815ae100)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff815ae100-ffffffff815ae110: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816574b0)
Location: drivers/pci/iov.c:872
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
```
**Symbols:**

```
ffffffff816574b0-ffffffff816574c0: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81677a70)
Location: drivers/pci/iov.c:873
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:pdev_sort_resources
  - drivers/pci/setup-bus.c:pdev_sort_resources
```
**Symbols:**

```
ffffffff81677a70-ffffffff81677a80: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8165a020)
Location: drivers/pci/iov.c:963
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff8165a020-ffffffff8165a030: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cc370)
Location: drivers/pci/iov.c:970
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff816cc370-ffffffff816cc380: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f2ae0)
Location: drivers/pci/iov.c:1011
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff817f2ae0-ffffffff817f2af8: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191b1b0)
Location: drivers/pci/iov.c:1011
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:pci_bus_distribute_available_resources
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff8191b1b0-ffffffff8191b1c8: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195e7c0)
Location: drivers/pci/iov.c:1011
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff8195e7c0-ffffffff8195e7d8: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a7e20)
Location: drivers/pci/iov.c:1013
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-bus.c:remove_dev_resource
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pbus_size_io
  - drivers/pci/setup-bus.c:__assign_resources_sorted
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:__dev_sort_resources
```
**Symbols:**

```
ffffffff819a7e20-ffffffff819a7e38: pci_sriov_resource_alignment (STB_GLOBAL)
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
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff8000107180e0)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffff8000107180e0-ffff800010718114: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a27d4)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
c08a27d4-c08a27f0: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c000000000888b70)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
c000000000888b70-c000000000888ba4: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e1272)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffe0004e1272-ffffffe0004e12a4: pci_sriov_resource_alignment (STB_GLOBAL)
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
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a18c0)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff815a18c0-ffffffff815a18d0: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81590a60)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff81590a60-ffffffff81590a70: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a1e50)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff815a1e50-ffffffff815a1e60: pci_sriov_resource_alignment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
resource_size_t pci_sriov_resource_alignment(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bc250)
Location: drivers/pci/iov.c:856
Inline: False
Direct callers:
  - drivers/pci/setup-res.c:pci_assign_resource
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
**Symbols:**

```
ffffffff815bc250-ffffffff815bc260: pci_sriov_resource_alignment (STB_GLOBAL)
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
