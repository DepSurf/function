# Function: <code>class_dev_iter_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154cd70)
Location: drivers/base/class.c:341
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_unregister
Direct callers:
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/extcon/extcon.c:extcon_register_interest
```
**Symbols:**

```
ffffffff8154cd70-ffffffff8154cd80: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159ed05)
Location: drivers/base/class.c:341
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
```
**Symbols:**

```
ffffffff8159eb60-ffffffff8159eb70: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd2c5)
Location: drivers/base/class.c:356
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
```
**Symbols:**

```
ffffffff815cd120-ffffffff815cd130: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1dc0)
Location: drivers/base/class.c:323
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff815e1c00-ffffffff815e1c10: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648f36)
Location: drivers/base/class.c:323
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81648d70-ffffffff81648d80: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816844fb)
Location: drivers/base/class.c:321
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81684350-ffffffff81684360: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a41bb)
Location: drivers/base/class.c:321
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816a4010-ffffffff816a4020: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dd0eb)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816dcf40-ffffffff816dcf50: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170119b)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81700ff0-ffffffff81701000: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb68b)
Location: drivers/base/class.c:328
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817baf60-ffffffff817baf70: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817d027b)
Location: drivers/base/class.c:328
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817cfb60-ffffffff817cfb70: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3ca0)
Location: drivers/base/class.c:328
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817b3570-ffffffff817b3580: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183d180)
Location: drivers/base/class.c:328
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8183ca50-ffffffff8183ca60: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197fd8a)
Location: drivers/base/class.c:328
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8197f520-ffffffff8197f536: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed6ba)
Location: drivers/base/class.c:333
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81aecdb0-ffffffff81aecdc6: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3ba39)
Location: drivers/base/class.c:362
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_stop
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b3adc0-ffffffff81b3adf0: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b93589)
Location: drivers/base/class.c:361
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_stop
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b92880-ffffffff81b928b0: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec9d0)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffff8000108ec820-ffff8000108ec84c: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da878)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
c09da6b4-c09da6d0: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c0000000009843e4)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
c000000000984180-c0000000009841b4: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fc86)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffe00057fb36-ffffffe00057fb60: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c698b)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816c67e0-ffffffff816c67f0: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1beb)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816a1a40-ffffffff816a1a50: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4e5b)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816f4cb0-ffffffff816f4cc0: class_dev_iter_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_exit(struct class_dev_iter *iter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f6eb)
Location: drivers/base/class.c:327
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_stop
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8170f540-ffffffff8170f550: class_dev_iter_exit (STB_GLOBAL)
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
