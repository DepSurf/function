# Function: <code>iowrite32be</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402b20)
Location: lib/iomap.c:128
Inline: True
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
```
**Symbols:**

```
ffffffff81402b20-ffffffff81402b55: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a5b0)
Location: lib/iomap.c:128
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff8144a5b0-ffffffff8144a5e5: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468f70)
Location: lib/iomap.c:128
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81468f70-ffffffff81468fa5: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e650)
Location: lib/iomap.c:128
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff8146e650-ffffffff8146e685: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a980)
Location: lib/iomap.c:129
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff8149a980-ffffffff8149a9b7: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfc30)
Location: lib/iomap.c:129
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff814cfc30-ffffffff814cfc67: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4540)
Location: lib/iomap.c:129
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff814e4540-ffffffff814e4577: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510dd0)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81510dd0-ffffffff81510e05: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531840)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81531840-ffffffff81531875: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81595cb0)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81595cb0-ffffffff81595cff: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1740)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff815b1740-ffffffff815b178f: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc550)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff815bc550-ffffffff815bc59f: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816233a0)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff816233a0-ffffffff816233ef: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f3310)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff816f3310-ffffffff816f338e: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e5250)
Location: lib/iomap.c:227
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be
```
**Symbols:**

```
ffffffff817e5250-ffffffff817e52ce: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81825290)
Location: lib/iomap.c:227
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be
```
**Symbols:**

```
ffffffff81825290-ffffffff8182530e: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876ca0)
Location: lib/iomap.c:227
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be
```
**Symbols:**

```
ffffffff81876ca0-ffffffff81876d1e: iowrite32be (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5240)
Location: lib/iomap.c:205
Inline: True
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
**Symbols:**

```
c0000000007e5240-c0000000007e5304: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffe000118cbe)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_writel_be
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004adf7c)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
```
```
In drivers/clk/clk-divider.c (ffffffe000511880)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512b46)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512ef0)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
```
```
In drivers/clk/clk-mux.c (ffffffe000513282)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000514002)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551654)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555aec)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005598bc)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059c0bc)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061be70)
Location: include/asm-generic/io.h:788
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
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
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529e20)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/gpio/gpio-mmio.c:bgpio_write32be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81529e20-ffffffff81529e55: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a100)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff8151a100-ffffffff8151a135: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525eb0)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff81525eb0-ffffffff81525ee5: iowrite32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iowrite32be(u32 val, void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f830)
Location: lib/iomap.c:205
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_writel_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_out
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_out
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be
```
**Symbols:**

```
ffffffff8153f830-ffffffff8153f865: iowrite32be (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
