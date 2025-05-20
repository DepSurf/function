# Function: <code>devres_release_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154fef0)
Location: drivers/base/devres.c:649
Inline: False
Direct callers:
  - drivers/base/component.c:take_down_master
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_init_one
```
**Symbols:**

```
ffffffff8154fef0-ffffffff8154ffb2: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1ce0)
Location: drivers/base/devres.c:649
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff815a1ce0-ffffffff815a1da7: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d0400)
Location: drivers/base/devres.c:650
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff815d0400-ffffffff815d04c7: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e5130)
Location: drivers/base/devres.c:650
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:take_down_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff815e5130-ffffffff815e51df: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164c420)
Location: drivers/base/devres.c:650
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:take_down_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff8164c420-ffffffff8164c4cf: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687a10)
Location: drivers/base/devres.c:654
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff81687a10-ffffffff81687abd: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a7430)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
```
**Symbols:**

```
ffffffff816a7430-ffffffff816a74dd: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816e0510)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816e0510-ffffffff816e05ca: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704740)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81704740-ffffffff817047ec: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817beb10)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817beb10-ffffffff817bebbf: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3630)
Location: drivers/base/devres.c:678
Inline: False
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817d3630-ffffffff817d36df: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7040)
Location: drivers/base/devres.c:678
Inline: False
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff817b7040-ffffffff817b70ec: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff818400d0)
Location: drivers/base/devres.c:663
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff818400d0-ffffffff818401e3: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff819833e0)
Location: drivers/base/devres.c:663
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff819833e0-ffffffff819834f5: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af13d0)
Location: drivers/base/devres.c:668
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81af13d0-ffffffff81af14e5: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f520)
Location: drivers/base/devres.c:668
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81b3f520-ffffffff81b3f652: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b973a0)
Location: drivers/base/devres.c:668
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_bind
  - drivers/base/component.c:component_unbind
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/i2c/i2c-core-base.c:i2c_device_remove
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81b973a0-ffffffff81b974d2: devres_release_group (STB_GLOBAL)
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
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f01e8)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
  - drivers/edac/altera_edac.c:altr_edac_a10_device_add
  - drivers/edac/altera_edac.c:altr_edac_device_probe
  - drivers/edac/altera_edac.c:altr_sdram_probe
```
**Symbols:**

```
ffff8000108f01e8-ffff8000108f0324: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddfa8)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/ata/libahci_platform.c:ahci_platform_get_resources
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c09ddfa8-c09de08c: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c00000000098a1a0)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
c00000000098a1a0-c00000000098a2d0: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582ac6)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffe000582ac6-ffffffe000582b70: devres_release_group (STB_GLOBAL)
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
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c9e90)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816c9e90-ffffffff816c9f3c: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a51c0)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816a51c0-ffffffff816a526c: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8400)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff816f8400-ffffffff816f84ac: devres_release_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devres_release_group(struct device *dev, void *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712ca0)
Location: drivers/base/devres.c:662
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/ata/libata-core.c:ata_host_alloc
  - drivers/ata/libata-sff.c:ata_pci_init_one
  - drivers/ata/libata-sff.c:ata_pci_sff_activate_host
  - drivers/ata/libata-sff.c:ata_pci_sff_prepare_host
  - drivers/power/supply/power_supply_hwmon.c:power_supply_remove_hwmon_sysfs
  - drivers/power/supply/power_supply_hwmon.c:power_supply_add_hwmon_sysfs
```
**Symbols:**

```
ffffffff81712ca0-ffffffff81712d4c: devres_release_group (STB_GLOBAL)
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
