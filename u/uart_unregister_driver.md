# Function: <code>uart_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815006a0)
Location: drivers/tty/serial/serial_core.c:2462
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/max310x.c:max310x_spi_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff815006a0-ffffffff8150070d: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81551130)
Location: drivers/tty/serial/serial_core.c:2555
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81551130-ffffffff8155119c: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157da10)
Location: drivers/tty/serial/serial_core.c:2520
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8157da10-ffffffff8157da81: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81591c30)
Location: drivers/tty/serial/serial_core.c:2517
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81591c30-ffffffff81591ca1: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f6660)
Location: drivers/tty/serial/serial_core.c:2520
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff815f6660-ffffffff815f66d1: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162f830)
Location: drivers/tty/serial/serial_core.c:2517
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8162f830-ffffffff8162f8a1: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d9e0)
Location: drivers/tty/serial/serial_core.c:2578
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8164d9e0-ffffffff8164da51: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81682560)
Location: drivers/tty/serial/serial_core.c:2585
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81682560-ffffffff816825d5: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a4bf0)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff816a4bf0-ffffffff816a4c65: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81757220)
Location: drivers/tty/serial/serial_core.c:2597
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81757220-ffffffff81757295: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817723a0)
Location: drivers/tty/serial/serial_core.c:2604
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff817723a0-ffffffff81772415: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81755e30)
Location: drivers/tty/serial/serial_core.c:2601
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81755e30-ffffffff81755ea5: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d9560)
Location: drivers/tty/serial/serial_core.c:2616
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff817d9560-ffffffff817d95d5: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917df0)
Location: drivers/tty/serial/serial_core.c:2662
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81917df0-ffffffff81917e64: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a73730)
Location: drivers/tty/serial/serial_core.c:2796
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81a73730-ffffffff81a737a4: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abddc0)
Location: drivers/tty/serial/serial_core.c:2828
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81abddc0-ffffffff81abde33: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b10c20)
Location: drivers/tty/serial/serial_core.c:2864
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81b10c20-ffffffff81b10c93: uart_unregister_driver (STB_GLOBAL)
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
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087d078)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/amba-pl011.c:pl011_unregister_port
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/imx.c:imx_uart_exit
  - drivers/tty/serial/imx.c:imx_uart_init
  - drivers/tty/serial/meson_uart.c:meson_uart_exit
  - drivers/tty/serial/meson_uart.c:meson_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_exit
  - drivers/tty/serial/msm_serial.c:msm_serial_init
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_init
  - drivers/tty/serial/owl-uart.c:owl_uart_exit
  - drivers/tty/serial/owl-uart.c:owl_uart_init
```
**Symbols:**

```
ffff80001087d078-ffff80001087d0f0: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097ea98)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/amba-pl011.c:pl011_unregister_port
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/imx.c:imx_uart_exit
  - drivers/tty/serial/imx.c:imx_uart_init
  - drivers/tty/serial/meson_uart.c:meson_uart_exit
  - drivers/tty/serial/meson_uart.c:meson_uart_init
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_exit
  - drivers/tty/serial/msm_serial.c:msm_serial_init
  - drivers/tty/serial/omap-serial.c:serial_omap_exit
  - drivers/tty/serial/omap-serial.c:serial_omap_init
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_init
  - drivers/tty/serial/owl-uart.c:owl_uart_exit
  - drivers/tty/serial/owl-uart.c:owl_uart_init
  - drivers/tty/serial/rda-uart.c:rda_uart_exit
  - drivers/tty/serial/rda-uart.c:rda_uart_init
```
**Symbols:**

```
c097ea98-c097eb10: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000923bd0)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
c000000000923bd0-c000000000923c88: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054bb9c)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_exit
  - drivers/tty/serial/sifive.c:sifive_serial_init
```
**Symbols:**

```
ffffffe00054bb9c-ffffffe00054bc1e: uart_unregister_driver (STB_GLOBAL)
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
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166a650)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8166a650-ffffffff8166a6c5: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816497c0)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff816497c0-ffffffff81649835: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81698a30)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81698a30-ffffffff81698aa5: uart_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_unregister_driver(struct uart_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b30f0)
Location: drivers/tty/serial/serial_core.c:2586
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_exit
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/sccnxp.c:sccnxp_remove
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff816b30f0-ffffffff816b3165: uart_unregister_driver (STB_GLOBAL)
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
