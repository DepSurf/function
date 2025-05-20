# Function: <code>kset_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eba40)
Location: lib/kobject.c:829
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_remove
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff813eba40-ffffffff813eba62: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431e10)
Location: lib/kobject.c:829
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_remove
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81431e10-ffffffff81431e32: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e080)
Location: lib/kobject.c:829
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_remove
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8144e080-ffffffff8144e0a2: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee2e0)
Location: lib/kobject.c:832
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff818ee2e0-ffffffff818ee303: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974570)
Location: lib/kobject.c:832
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - fs/ext4/sysfs.c:ext4_exit_sysfs
  - fs/ext4/sysfs.c:ext4_init_sysfs
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81974570-ffffffff81974593: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0ae0)
Location: lib/kobject.c:845
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff819d0ae0-ffffffff819d0b02: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a100)
Location: lib/kobject.c:845
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81a0a100-ffffffff81a0a122: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79950)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81a79950-ffffffff81a79974: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0cb0)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81ab0cb0-ffffffff81ab0cd4: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaef0)
Location: lib/kobject.c:893
Inline: False
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815eaef0-ffffffff815eaf29: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f810)
Location: lib/kobject.c:890
Inline: False
Direct callers:
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8160f810-ffffffff8160f849: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2f50)
Location: lib/kobject.c:890
Inline: False
Direct callers:
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff815f2f50-ffffffff815f2f89: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660120)
Location: lib/kobject.c:890
Inline: False
Direct callers:
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81660120-ffffffff81660159: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779c60)
Location: lib/kobject.c:858
Inline: False
Direct callers:
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/firmware/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81779c60-ffffffff81779ca3: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022c70)
Location: lib/kobject.c:873
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff82022c70-ffffffff82022cb3: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2ce0)
Location: lib/kobject.c:874
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff820a2ce0-ffffffff820a2d23: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ad60)
Location: lib/kobject.c:886
Inline: False
Direct callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff8217ad60-ffffffff8217ada3: kset_unregister (STB_GLOBAL)
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
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8ad48)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffff800010d8ad48-ffff800010d8ad7c: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e85390)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
c0e85390-c0e853bc: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecbf80)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
c000000000ecbf80-c000000000ecbfbc: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b4298)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffe0008b4298-ffffffe0008b42c8: kset_unregister (STB_GLOBAL)
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
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4fb00)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81a4fb00-ffffffff81a4fb24: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0cc00)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/hv/vmbus_drv.c:vmbus_device_unregister
  - drivers/hv/vmbus_drv.c:vmbus_device_register
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81a0cc00-ffffffff81a0cc24: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbef0)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81abbef0-ffffffff81abbf14: kset_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void kset_unregister(struct kset *k);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8330)
Location: lib/kobject.c:876
Inline: True
Direct callers:
  - mm/slub.c:sysfs_slab_remove_workfn
  - drivers/base/core.c:devices_init
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_unregister
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_register
  - drivers/base/class.c:class_unregister
  - drivers/base/swnode.c:software_node_exit
  - drivers/firmware/edd.c:edd_exit
  - drivers/firmware/edd.c:edd_init
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - drivers/firmware/efi/runtime-map.c:efi_runtime_map_init
  - net/core/net-sysfs.c:netdev_register_kobject
  - net/core/net-sysfs.c:netdev_unregister_kobject
```
**Symbols:**

```
ffffffff81ac8330-ffffffff81ac8354: kset_unregister (STB_GLOBAL)
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
