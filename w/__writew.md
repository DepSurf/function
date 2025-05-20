# Function: <code>__writew</code>

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
In lib/iomap.c (ffffffff81402a58)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/gpio/gpio-zx.c (ffffffff8142bdf2)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_direction_input
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_set_value
  - drivers/gpio/gpio-zx.c:zx_set_value
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
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
In lib/iomap.c (ffffffff8144a567)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/gpio/gpio-zx.c (ffffffff81477351)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_unmask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_mask
  - drivers/gpio/gpio-zx.c:zx_irq_handler
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_irq_type
  - drivers/gpio/gpio-zx.c:zx_set_value
  - drivers/gpio/gpio-zx.c:zx_set_value
  - drivers/gpio/gpio-zx.c:zx_direction_output
  - drivers/gpio/gpio-zx.c:zx_direction_output
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
In lib/iomap.c (ffffffff81468f27)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815264b3)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In lib/iomap.c (ffffffff8146e5f2)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81539454)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8172613d)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff8149a927)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8159adc6)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8179778d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff814cfbc1)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815d28cd)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff817da388)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff814e44d1)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - lib/iomap.c:iowrite16be
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815ec07d)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818017a8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff8151115b)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8161dd57)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81842a58)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff81531bcb)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8163f807)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff818743d8)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff81595f2b)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eaedf)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81947ef0)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff815b19bb)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8170863f)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817f82fb)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff8194dd00)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff815bc7cb)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff816eb595)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff817dca8b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81931870)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff8162361b)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81765620)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff8186848b)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff819d4b50)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff816f356e)
Location: arch/x86/include/asm/io.h:72
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81899881)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff819b0ecb)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81b37480)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff817e54ee)
Location: arch/x86/include/asm/io.h:72
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff819e1c31)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b25858)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81ccc8f0)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff8182552e)
Location: arch/x86/include/asm/io.h:72
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a29c03)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81b75968)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81d34650)
Location: arch/x86/include/asm/io.h:72
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
  - drivers/i2c/busses/i2c-designware-common.c:dw_reg_write_word
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
In lib/iomap.c (ffffffff81876f3e)
Location: arch/x86/include/asm/io.h:69
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a74dd3)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cpc_write
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc97c4)
Location: arch/x86/include/asm/io.h:69
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_noinc_write
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write16le_relaxed
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
In lib/iomap.c (ffffffff8152a1ab)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8160b237)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In lib/iomap.c (ffffffff8151a48b)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff815fce77)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
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
In lib/iomap.c (ffffffff8152623b)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81633647)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81869888)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
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
In lib/iomap.c (ffffffff8153fbbb)
Location: arch/x86/include/asm/io.h:70
Inline: True
```
```
In drivers/acpi/cppc_acpi.c (ffffffff8164d977)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
```
In drivers/i2c/busses/i2c-designware-common.c (ffffffff81883818)
Location: arch/x86/include/asm/io.h:70
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
  - drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable
```
</details>
</li>
</ul>

## Differences
