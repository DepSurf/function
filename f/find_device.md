# Function: <code>find_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a557b)
Location: drivers/md/dm-table.c:263
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff816a86e0)
Location: drivers/md/dm-ioctl.c:812
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:dev_wait
```
```
In arch/x86/pci/xen.c (ffffffff816f7419)
Location: arch/x86/pci/xen.c:518
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
```
**Symbols:**

```
ffffffff816a86e0-ffffffff816a8720: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8170570a)
Location: drivers/md/dm-table.c:266
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81708b70)
Location: drivers/md/dm-ioctl.c:812
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff8175cd82)
Location: arch/x86/pci/xen.c:524
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff81708b70-ffffffff81708bb0: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817375ba)
Location: drivers/md/dm-table.c:266
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8173aa40)
Location: drivers/md/dm-ioctl.c:812
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff817892b2)
Location: arch/x86/pci/xen.c:515
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff8173aa40-ffffffff8173aa80: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81750ada)
Location: drivers/md/dm-table.c:268
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81754440)
Location: drivers/md/dm-ioctl.c:817
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff817a8392)
Location: arch/x86/pci/xen.c:515
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff81754440-ffffffff81754480: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c2caa)
Location: drivers/md/dm-table.c:268
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff817c65f0)
Location: drivers/md/dm-ioctl.c:824
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff8181ea79)
Location: arch/x86/pci/xen.c:515
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff817c65f0-ffffffff817c6630: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180b569)
Location: drivers/md/dm-table.c:268
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8180fea0)
Location: drivers/md/dm-ioctl.c:824
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff818696a9)
Location: arch/x86/pci/xen.c:513
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff8180fea0-ffffffff8180fee0: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81837569)
Location: drivers/md/dm-table.c:267
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8183bea0)
Location: drivers/md/dm-ioctl.c:824
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81889729)
Location: arch/x86/pci/xen.c:513
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff8183bea0-ffffffff8183bedf: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187a179)
Location: drivers/md/dm-table.c:267
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8187df40)
Location: drivers/md/dm-ioctl.c:824
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff818d3f09)
Location: arch/x86/pci/xen.c:514
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff8187df40-ffffffff8187df81: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818abf59)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff818aff30)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81906289)
Location: arch/x86/pci/xen.c:514
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff818aff30-ffffffff818aff71: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197c7d1)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff819805d5)
Location: drivers/md/dm-ioctl.c:849
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81bb68d9)
Location: arch/x86/pci/xen.c:511
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81980deb)
Location: drivers/md/dm-table.c:224
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81984bf5)
Location: drivers/md/dm-ioctl.c:849
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81bcbaf9)
Location: arch/x86/pci/xen.c:596
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81964ffb)
Location: drivers/md/dm-table.c:210
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8196a335)
Location: drivers/md/dm-ioctl.c:926
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81bbf479)
Location: arch/x86/pci/xen.c:596
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0cf7b)
Location: drivers/md/dm-table.c:210
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81a127d5)
Location: drivers/md/dm-ioctl.c:931
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff81c8f3e9)
Location: arch/x86/pci/xen.c:599
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_initdom_setup_msi_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff818da77b)
Location: drivers/xen/pci.c:269
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_unregister_device_domain_owner
  - drivers/xen/pci.c:xen_register_device_domain_owner
  - drivers/xen/pci.c:xen_find_device_domain_owner
```
```
In drivers/md/dm-table.c (ffffffff81b758bd)
Location: drivers/md/dm-table.c:211
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81b7afdb)
Location: drivers/md/dm-ioctl.c:938
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81a2d71b)
Location: drivers/xen/pci.c:269
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_unregister_device_domain_owner
  - drivers/xen/pci.c:xen_register_device_domain_owner
  - drivers/xen/pci.c:xen_find_device_domain_owner
```
```
In drivers/md/dm-table.c (ffffffff81d12bed)
Location: drivers/md/dm-table.c:210
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81d1765f)
Location: drivers/md/dm-ioctl.c:938
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81a76ebb)
Location: drivers/xen/pci.c:269
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_unregister_device_domain_owner
  - drivers/xen/pci.c:xen_register_device_domain_owner
  - drivers/xen/pci.c:xen_find_device_domain_owner
```
```
In drivers/md/dm-table.c (ffffffff821487cc)
Location: drivers/md/dm-table.c:211
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81d808ef)
Location: drivers/md/dm-ioctl.c:963
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/pci.c (ffffffff81ac90ab)
Location: drivers/xen/pci.c:269
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_unregister_device_domain_owner
  - drivers/xen/pci.c:xen_register_device_domain_owner
  - drivers/xen/pci.c:xen_find_device_domain_owner
```
```
In drivers/md/dm-table.c (ffffffff8222b19e)
Location: drivers/md/dm-table.c:217
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81e37f4f)
Location: drivers/md/dm-ioctl.c:963
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b02918)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffff800010b06f80)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffff800010b06f80-ffff800010b06fd4: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be139c)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (c0be5a68)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
c0be5a68-c0be5ab0: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf1aac)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (c000000000bf7d30)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
c000000000bf7d30-c000000000bf7da8: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f2104)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f58bc)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffe0006f58bc-ffffffe0006f590e: find_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81851dd9)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff81855db0)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff818a5649)
Location: arch/x86/pci/xen.c:514
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff81855db0-ffffffff81855df1: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818193e9)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff8181d3c0)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff8181d3c0-ffffffff8181d401: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a1409)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff818a53e0)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff818f6ca9)
Location: arch/x86/pci/xen.c:514
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff818a53e0-ffffffff818a5421: find_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
struct dm_dev_internal *find_device(struct list_head *l, dev_t dev);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bd649)
Location: drivers/md/dm-table.c:265
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_get_device
```
```
In drivers/md/dm-ioctl.c (ffffffff818c1620)
Location: drivers/md/dm-ioctl.c:849
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:target_message
  - drivers/md/dm-ioctl.c:table_status
  - drivers/md/dm-ioctl.c:table_deps
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dev_wait
  - drivers/md/dm-ioctl.c:dev_status
  - drivers/md/dm-ioctl.c:dev_suspend
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
```
In arch/x86/pci/xen.c (ffffffff8191750b)
Location: arch/x86/pci/xen.c:514
Inline: True
Inline callers:
  - arch/x86/pci/xen.c:xen_unregister_device_domain_owner
  - arch/x86/pci/xen.c:xen_register_device_domain_owner
  - arch/x86/pci/xen.c:xen_find_device_domain_owner
```
**Symbols:**

```
ffffffff818c1620-ffffffff818c1661: find_device (STB_LOCAL)
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
