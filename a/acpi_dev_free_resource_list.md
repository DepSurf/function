# Function: <code>acpi_dev_free_resource_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8148192f)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_default_enumeration
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
**Symbols:**

```
ffffffff8148192f-ffffffff8148193f: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814d0425)
Location: drivers/acpi/resource.c:490
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
```
**Symbols:**

```
ffffffff814d0425-ffffffff814d0435: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f29a5)
Location: drivers/acpi/resource.c:506
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff814f238f-ffffffff814f239f: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815005bf)
Location: drivers/acpi/resource.c:506
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff814ffcf0-ffffffff814ffd00: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815427b6)
Location: drivers/acpi/resource.c:507
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81541ea0-ffffffff81541eb0: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81578716)
Location: drivers/acpi/resource.c:507
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81577df0-ffffffff81577e00: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81590366)
Location: drivers/acpi/resource.c:507
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8158fa50-ffffffff8158fa60: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c1146)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815c08a0-ffffffff815c08b0: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e2406)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815e1b60-ffffffff815e1b70: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168ce03)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8168cab0-ffffffff8168cac0: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aab03)
Location: drivers/acpi/resource.c:492
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_check_resources
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff816aa7b0-ffffffff816aa7c0: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d41e)
Location: drivers/acpi/resource.c:537
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff8168d030-ffffffff8168d040: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81702c4e)
Location: drivers/acpi/resource.c:544
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count
```
**Symbols:**

```
ffffffff81702860-ffffffff81702870: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81830c01)
Location: drivers/acpi/resource.c:544
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_count_resources
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count
```
**Symbols:**

```
ffffffff81830960-ffffffff81830976: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81963d91)
Location: drivers/acpi/resource.c:661
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_count_resources
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count
```
**Symbols:**

```
ffffffff81963ac0-ffffffff81963ad6: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aa231)
Location: drivers/acpi/resource.c:702
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_count_resources
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count
```
**Symbols:**

```
ffffffff819a9f60-ffffffff819a9f76: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f44c1)
Location: drivers/acpi/resource.c:765
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
  - drivers/acpi/resource.c:acpi_dev_get_dma_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/dma/acpi-dma.c:acpi_dma_parse_resource_group
  - drivers/tty/serdev/core.c:acpi_serdev_add_device
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_spi_device_alloc
  - drivers/spi/spi.c:acpi_spi_count_resources
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device_by_fwnode
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_client_count
```
**Symbols:**

```
ffffffff819f41f0-ffffffff819f4206: acpi_dev_free_resource_list (STB_GLOBAL)
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
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076eddc)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_get_rc_resources
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add
```
**Symbols:**

```
ffff80001076e370-ffff80001076e39c: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d46c6)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815d3e20-ffffffff815d3e30: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815be286)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815bd9e0-ffffffff815bd9f0: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d66e6)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815d5e40-ffffffff815d5e50: acpi_dev_free_resource_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_free_resource_list(struct list_head *list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815f05a6)
Location: drivers/acpi/resource.c:499
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/scan.c:acpi_dma_get_range
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815efd00-ffffffff815efd10: acpi_dev_free_resource_list (STB_GLOBAL)
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
