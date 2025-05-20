# Function: <code>devres_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f460)
Location: drivers/base/devres.c:259
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff8154f460-ffffffff8154f518: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1230)
Location: drivers/base/devres.c:259
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff815a1230-ffffffff815a12e8: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cf8a0)
Location: drivers/base/devres.c:260
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff815cf8a0-ffffffff815cf958: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4280)
Location: drivers/base/devres.c:260
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_class.c:assign_firmware_buf
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff815e4280-ffffffff815e4336: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164b550)
Location: drivers/base/devres.c:260
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_class.c:assign_firmware_buf
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff8164b550-ffffffff8164b608: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81686b50)
Location: drivers/base/devres.c:264
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff81686b50-ffffffff81686c0f: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a67f0)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff816a67f0-ffffffff816a68a1: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816df870)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff816df870-ffffffff816df92c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81703ac0)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff81703ac0-ffffffff81703b7c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be8d0)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff817be8d0-ffffffff817be98c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d37a0)
Location: drivers/base/devres.c:288
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff817d37a0-ffffffff817d385c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b71b0)
Location: drivers/base/devres.c:288
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff817b71b0-ffffffff817b726c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff818401f0)
Location: drivers/base/devres.c:281
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:firmware_request_cache
  - drivers/base/firmware_loader/main.c:assign_fw
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff818401f0-ffffffff818402ac: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81983230)
Location: drivers/base/devres.c:281
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81983230-ffffffff81983301: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af1200)
Location: drivers/base/devres.c:286
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81af1200-ffffffff81af12d1: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f340)
Location: drivers/base/devres.c:286
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81b3f340-ffffffff81b3f426: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b971c0)
Location: drivers/base/devres.c:286
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pci_intx
  - drivers/pci/pci.c:pcim_set_mwi
  - drivers/pci/pci.c:__pci_request_region
  - drivers/pci/pci.c:pci_release_region
  - drivers/pci/pci.c:pci_disable_device
  - drivers/pci/pci.c:pcim_pin_device
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:request_partial_firmware_into_buf
  - drivers/base/firmware_loader/main.c:request_firmware_into_buf
  - drivers/base/firmware_loader/main.c:fw_add_devm_name
  - drivers/base/regmap/regmap.c:dev_get_regmap
  - drivers/net/phy/mdio_devres.c:__devm_mdiobus_register
  - net/devres.c:devm_register_netdev
```
**Symbols:**

```
ffffffff81b971c0-ffffffff81b972a6: devres_find (STB_GLOBAL)
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
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0478)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - lib/genalloc.c:of_gen_pool_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffff8000108f0478-ffff8000108f0590: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dce58)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - lib/genalloc.c:of_gen_pool_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
c09dce58-c09dcf1c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000988960)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - lib/genalloc.c:of_gen_pool_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
c000000000988960-c000000000988acc: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000581f52)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - lib/genalloc.c:of_gen_pool_get
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffe000581f52-ffffffe000581fee: devres_find (STB_GLOBAL)
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
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c9210)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff816c9210-ffffffff816c92cc: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4540)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff816a4540-ffffffff816a45fc: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7780)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff816f7780-ffffffff816f783c: devres_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devres_find(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712020)
Location: drivers/base/devres.c:272
Inline: False
Direct callers:
  - lib/devres.c:pcim_iomap_table
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_index
  - drivers/pci/pci.c:pcim_enable_device
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/regmap/regmap.c:dev_get_regmap
```
**Symbols:**

```
ffffffff81712020-ffffffff817120dc: devres_find (STB_GLOBAL)
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
