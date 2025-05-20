# Function: <code>ioread32be</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81402880)
Location: lib/iomap.c:91
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
```
**Symbols:**

```
ffffffff81402880-ffffffff814028b5: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8144a570)
Location: lib/iomap.c:91
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff8144a570-ffffffff8144a5a5: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81468f30)
Location: lib/iomap.c:91
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81468f30-ffffffff81468f65: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8146e610)
Location: lib/iomap.c:91
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff8146e610-ffffffff8146e645: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8149a940)
Location: lib/iomap.c:92
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff8149a940-ffffffff8149a977: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814cfbf0)
Location: lib/iomap.c:92
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff814cfbf0-ffffffff814cfc27: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff814e4500)
Location: lib/iomap.c:92
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff814e4500-ffffffff814e4537: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81510d90)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81510d90-ffffffff81510dc5: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81531800)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81531800-ffffffff81531835: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815958a0)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff815958a0-ffffffff815958ff: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815b1330)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff815b1330-ffffffff815b138f: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff815bc140)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff815bc140-ffffffff815bc19f: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81622f90)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81622f90-ffffffff81622fef: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff816f2e70)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff816f2e70-ffffffff816f2ef1: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff817e4d30)
Location: lib/iomap.c:103
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_get_div
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32be
```
**Symbols:**

```
ffffffff817e4d30-ffffffff817e4db1: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81824d70)
Location: lib/iomap.c:103
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_get_div
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32be
```
**Symbols:**

```
ffffffff81824d70-ffffffff81824df1: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ioread32be(const void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81876780)
Location: lib/iomap.c:103
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/pci/quirks.c:reset_hinic_vf_dev
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_get_div
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_ioread32be
```
**Symbols:**

```
ffffffff81876780-ffffffff81876801: ioread32be (STB_GLOBAL)
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
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/iomap.c (c0000000007e5710)
Location: lib/iomap.c:93
Inline: True
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/soc/fsl/guts.c:fsl_guts_probe
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
  - drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode
```
**Symbols:**

```
c0000000007e5710-c0000000007e587c: ioread32be (STB_GLOBAL)
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
In kernel/irq/generic-chip.c (ffffffe000118a9a)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_readl_be
```
```
In drivers/gpio/gpio-mmio.c (ffffffe0004ad3e0)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
```
```
In drivers/pci/quirks.c (ffffffe0004cdc86)
Location: include/asm-generic/io.h:762
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffe0005118ac)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
```
```
In drivers/clk/clk-gate.c (ffffffe000512c64)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
```
```
In drivers/clk/clk-multiplier.c (ffffffe000512ebe)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
```
```
In drivers/clk/clk-mux.c (ffffffe0005132c0)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
```
```
In drivers/clk/clk-fractional-divider.c (ffffffe000513fd0)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffe000550fa4)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
```
```
In drivers/tty/serial/8250/8250_dwlib.c (ffffffe000555cfc)
Location: include/asm-generic/io.h:762
Inline: True
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffe0005597dc)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_early.c:serial8250_early_in
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffe00059bfa8)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
```
In drivers/spi/spi-fsl-spi.c (ffffffe00061c008)
Location: include/asm-generic/io.h:762
Inline: True
Inline callers:
  - drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe
  - drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_irq
  - drivers/spi/spi-fsl-spi.c:fsl_spi_setup
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
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81529de0)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/gpio/gpio-mmio.c:bgpio_read32be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81529de0-ffffffff81529e15: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8151a0c0)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff8151a0c0-ffffffff8151a0f5: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff81525e70)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff81525e70-ffffffff81525ea5: ioread32be (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ioread32be(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iomap.c (ffffffff8153f7f0)
Location: lib/iomap.c:93
Inline: False
Direct callers:
  - kernel/irq/generic-chip.c:irq_readl_be
  - drivers/clk/clk-divider.c:clk_divider_set_rate
  - drivers/clk/clk-divider.c:clk_divider_round_rate
  - drivers/clk/clk-divider.c:clk_divider_recalc_rate
  - drivers/clk/clk-gate.c:clk_gate_is_enabled
  - drivers/clk/clk-gate.c:clk_gate_endisable
  - drivers/clk/clk-multiplier.c:clk_multiplier_set_rate
  - drivers/clk/clk-multiplier.c:clk_multiplier_recalc_rate
  - drivers/clk/clk-mux.c:clk_mux_set_parent
  - drivers/clk/clk-mux.c:clk_mux_get_parent
  - drivers/clk/clk-fractional-divider.c:clk_fd_set_rate
  - drivers/clk/clk-fractional-divider.c:clk_fd_recalc_rate
  - drivers/tty/serial/8250/8250_port.c:mem32be_serial_in
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_read32be
```
**Symbols:**

```
ffffffff8153f7f0-ffffffff8153f825: ioread32be (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void *addr</code> ➡️ <code>const void *addr</code>
</li>
</ul>
</details>
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
