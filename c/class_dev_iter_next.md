# Function: <code>class_dev_iter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154cd30)
Location: drivers/base/class.c:318
Inline: False
Direct callers:
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_unregister
  - drivers/extcon/extcon.c:extcon_register_interest
```
**Symbols:**

```
ffffffff8154cd30-ffffffff8154cd70: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159eb20)
Location: drivers/base/class.c:318
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff8159eb20-ffffffff8159eb5d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd0e0)
Location: drivers/base/class.c:333
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff815cd0e0-ffffffff815cd11d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1bc0)
Location: drivers/base/class.c:300
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff815e1bc0-ffffffff815e1bfd: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648d30)
Location: drivers/base/class.c:300
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff81648d30-ffffffff81648d6d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81684310)
Location: drivers/base/class.c:298
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff81684310-ffffffff8168434d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a3fd0)
Location: drivers/base/class.c:298
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff816a3fd0-ffffffff816a400d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dcf00)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff816dcf00-ffffffff816dcf32: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81700fb0)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff81700fb0-ffffffff81700fe2: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb6d9)
Location: drivers/base/class.c:305
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817baf20-ffffffff817baf55: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817d02c9)
Location: drivers/base/class.c:305
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817cfb20-ffffffff817cfb55: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3cee)
Location: drivers/base/class.c:305
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817b3530-ffffffff817b3565: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183d1ce)
Location: drivers/base/class.c:305
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8183ca10-ffffffff8183ca45: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197fde4)
Location: drivers/base/class.c:305
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8197f4e0-ffffffff8197f51d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed714)
Location: drivers/base/class.c:310
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81aecd60-ffffffff81aecd9d: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3baa7)
Location: drivers/base/class.c:339
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b3ad70-ffffffff81b3adad: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b935f7)
Location: drivers/base/class.c:338
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b92830-ffffffff81b9286d: class_dev_iter_next (STB_GLOBAL)
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
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec7d0)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffff8000108ec7d0-ffff8000108ec81c: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da66c)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
c09da66c-c09da6b4: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000984100)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
c000000000984100-c000000000984174: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fafc)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffe00057fafc-ffffffe00057fb36: class_dev_iter_next (STB_GLOBAL)
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
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c67a0)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff816c67a0-ffffffff816c67d2: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1a00)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff816a1a00-ffffffff816a1a32: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4c70)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff816f4c70-ffffffff816f4ca2: class_dev_iter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct device *class_dev_iter_next(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f500)
Location: drivers/base/class.c:304
Inline: False
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_next
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
```
**Symbols:**

```
ffffffff8170f500-ffffffff8170f532: class_dev_iter_next (STB_GLOBAL)
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
