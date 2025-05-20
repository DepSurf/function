# Function: <code>acpi_dev_get_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81481dba)
Location: drivers/acpi/resource.c:546
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_default_enumeration
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/spi/spi.c:acpi_spi_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
  - drivers/i2c/i2c-core.c:acpi_i2c_add_device
```
**Symbols:**

```
ffffffff81481dba-ffffffff81481e8a: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814d08ac)
Location: drivers/acpi/resource.c:584
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
  - drivers/i2c/i2c-core.c:acpi_i2c_get_info
```
**Symbols:**

```
ffffffff814d08ac-ffffffff814d0983: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f2816)
Location: drivers/acpi/resource.c:600
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_tis.c:tpm_tis_acpi_init
  - drivers/i2c/i2c-core.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff814f2816-ffffffff814f28ed: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81500410)
Location: drivers/acpi/resource.c:600
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81500410-ffffffff815004ed: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81542740)
Location: drivers/acpi/resource.c:630
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815426a0-ffffffff815426b7: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815786ba)
Location: drivers/acpi/resource.c:630
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81578600-ffffffff81578617: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8159030a)
Location: drivers/acpi/resource.c:630
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_acpi_add
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff81590270-ffffffff81590287: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c10ea)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815c1050-ffffffff815c1067: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e23aa)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815e2310-ffffffff815e2327: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168cda1)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
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
ffffffff8168d4b0-ffffffff8168d590: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aaaa1)
Location: drivers/acpi/resource.c:615
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_dev_consumes_res
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_device_enumeration_by_parent
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff816ab1b0-ffffffff816ab290: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d3ca)
Location: drivers/acpi/resource.c:660
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff8168da10-ffffffff8168daf0: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81702bfa)
Location: drivers/acpi/resource.c:667
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff81703320-ffffffff81703400: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81830ba7)
Location: drivers/acpi/resource.c:667
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:fch_misc_setup
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff81831200-ffffffff81831308: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81963d37)
Location: drivers/acpi/resource.c:784
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff819649f0-ffffffff81964af8: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aa1d7)
Location: drivers/acpi/resource.c:825
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff819aac70-ffffffff819aad78: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f4467)
Location: drivers/acpi/resource.c:888
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
  - drivers/acpi/resource.c:acpi_dev_get_memory_resources
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_platform.c:acpi_create_platform_device
  - drivers/dma/acpi-dma.c:acpi_dma_request_slave_chan_by_index
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
ffffffff819f4f40-ffffffff819f5048: acpi_dev_get_resources (STB_GLOBAL)
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
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076ed74)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/bus/hisi_lpc.c:hisi_lpc_acpi_probe
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/pci/pci-acpi.c:acpi_get_rc_resources
  - drivers/pci/controller/pci-xgene.c:xgene_pcie_ecam_init
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
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
ffff80001076ec80-ffff80001076ecd4: acpi_dev_get_resources (STB_GLOBAL)
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
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d466a)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815d45d0-ffffffff815d45e7: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815be22a)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815be190-ffffffff815be1a7: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d668a)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815d65f0-ffffffff815d6607: acpi_dev_get_resources (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int acpi_dev_get_resources(struct acpi_device *adev, struct list_head *list, int (*preproc)(struct acpi_resource *, void *), void *preproc_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815f054a)
Location: drivers/acpi/resource.c:622
Inline: True
Inline callers:
  - drivers/acpi/resource.c:acpi_res_consumer_cb
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/acpi/scan.c:acpi_init_device_object
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_apd.c:st_misc_setup
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
  - drivers/char/tpm/tpm_crb.c:crb_map_io
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_new_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_irq
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_do_lookup
```
**Symbols:**

```
ffffffff815f04b0-ffffffff815f04c7: acpi_dev_get_resources (STB_GLOBAL)
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
