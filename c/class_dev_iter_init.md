# Function: <code>class_dev_iter_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8154cce0)
Location: drivers/base/class.c:294
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_interface_unregister
Direct callers:
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/extcon/extcon.c:extcon_register_interest
```
**Symbols:**

```
ffffffff8154cce0-ffffffff8154cd21: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8159ecce)
Location: drivers/base/class.c:294
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
```
**Symbols:**

```
ffffffff8159ead0-ffffffff8159eb11: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815cd28e)
Location: drivers/base/class.c:309
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
```
**Symbols:**

```
ffffffff815cd090-ffffffff815cd0d1: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff815e1d88)
Location: drivers/base/class.c:276
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff815e1b70-ffffffff815e1bb1: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81648ef8)
Location: drivers/base/class.c:276
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81648ce0-ffffffff81648d21: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816844be)
Location: drivers/base/class.c:274
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816842c0-ffffffff81684301: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a417e)
Location: drivers/base/class.c:274
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816a3f90-ffffffff816a3fcc: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816dd0ae)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816dcec0-ffffffff816dcefe: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170115e)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81700f70-ffffffff81700fae: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817bb649)
Location: drivers/base/class.c:281
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817baee0-ffffffff817baf1e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817d0239)
Location: drivers/base/class.c:281
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817cfae0-ffffffff817cfb1e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff817b3c5e)
Location: drivers/base/class.c:281
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff817b34f0-ffffffff817b352e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8183d13e)
Location: drivers/base/class.c:281
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8183c9d0-ffffffff8183ca0e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8197fd48)
Location: drivers/base/class.c:281
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_print_stat
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8197f490-ffffffff8197f4da: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81aed678)
Location: drivers/base/class.c:286
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81aecd00-ffffffff81aecd4a: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, const struct class *class, const struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b3b9e7)
Location: drivers/base/class.c:310
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_start
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b3b3e0-ffffffff81b3b44b: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, const struct class *class, const struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff81b93537)
Location: drivers/base/class.c:309
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
  - drivers/base/class.c:class_find_device
  - drivers/base/class.c:class_for_each_device
Direct callers:
  - block/genhd.c:disk_seqf_start
  - block/early-lookup.c:printk_all_partitions
  - block/early-lookup.c:blk_lookup_devt
  - block/blk-cgroup.c:blkcg_fill_root_iostats
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff81b92f30-ffffffff81b92f9b: class_dev_iter_init (STB_GLOBAL)
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
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffff8000108ec99c)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffff8000108ec770-ffff8000108ec7cc: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c09da83c)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
c09da62c-c09da66c: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (c000000000984398)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
c000000000984090-c0000000009840fc: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffe00057fc56)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffe00057faaa-ffffffe00057fafc: class_dev_iter_init (STB_GLOBAL)
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
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816c694e)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816c6760-ffffffff816c679e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816a1bae)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816a19c0-ffffffff816a19fe: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff816f4e1e)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff816f4c30-ffffffff816f4c6e: class_dev_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void class_dev_iter_init(struct class_dev_iter *iter, struct class *class, struct device *start, const struct device_type *type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/class.c (ffffffff8170f6ae)
Location: drivers/base/class.c:280
Inline: True
Inline callers:
  - drivers/base/class.c:class_interface_unregister
  - drivers/base/class.c:class_interface_register
Direct callers:
  - block/genhd.c:blk_lookup_devt
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:printk_all_partitions
  - drivers/phy/phy-core.c:of_phy_simple_xlate
  - drivers/pci/endpoint/pci-epc-core.c:pci_epc_get
```
**Symbols:**

```
ffffffff8170f4c0-ffffffff8170f4fe: class_dev_iter_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct class *class</code> ➡️ <code>const struct class *class</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct device *start</code> ➡️ <code>const struct device *start</code>
</li>
</ul>
</details>
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
