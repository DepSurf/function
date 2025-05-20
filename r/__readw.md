# Function: <code>__readw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402866)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142bddf)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_direction_input
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_get_value
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a516)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/gpio/gpio-zx.c (ffffffff81476f38)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_get_value
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_direction_input
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468ed6)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81525e15)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e59f)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815389dc)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81725bf8)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a8d4)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159a283)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81797248)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
  - drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfb97)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d1b85)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817d9e08)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e44a7)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - lib/iomap.c:ioread16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815eb1a5)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81801018)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81511008)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161cec9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842328)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531a78)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163e979)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81873ca8)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815960d8)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eadd7)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81947ec0)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1b68)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81708537)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f83fb)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194dcd0)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc978)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816e9b36)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dcb8b)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931840)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816237c8)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81763392)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186858b)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4b20)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f392b)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff818972e6)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0fcb)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37440)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e58eb)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819df031)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b2557f)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccc8a0)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8182592b)
Location: arch/x86/include/asm/io.h:64
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a26d41)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75683)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d34600)
Location: arch/x86/include/asm/io.h:64
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_read_word
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8187733b)
Location: arch/x86/include/asm/io.h:61
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a71d51)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc95cd)
Location: arch/x86/include/asm/io.h:61
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_read
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read16le_relaxed
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8152a058)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160a3a9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a338)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fbfe9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815260e8)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816327b9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869158)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153fa68)
Location: arch/x86/include/asm/io.h:62
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164cae9)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_read
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
  - drivers/acpi/cppc_acpi.c:check_pcc_chan
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818830e8)
Location: arch/x86/include/asm/io.h:62
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access
```
</details>
</li>
</ul>

## Differences
