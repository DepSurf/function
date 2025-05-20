# Function: <code>uart_add_one_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81501260)
Location: drivers/tty/serial/serial_core.c:2663
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81501260-ffffffff815016de: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81551d80)
Location: drivers/tty/serial/serial_core.c:2756
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81551d80-ffffffff8155222f: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157e920)
Location: drivers/tty/serial/serial_core.c:2721
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8157e920-ffffffff8157ee24: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81593060)
Location: drivers/tty/serial/serial_core.c:2718
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81593060-ffffffff815935ee: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f7b90)
Location: drivers/tty/serial/serial_core.c:2721
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff815f7b90-ffffffff815f80f3: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2718
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81634261-ffffffff816343fb: uart_add_one_port.cold.29 (STB_LOCAL)
ffffffff81630ba0-ffffffff81630f5e: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2779
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81652491-ffffffff8165262b: uart_add_one_port.cold.29 (STB_LOCAL)
ffffffff8164ed50-ffffffff8164f112: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2786
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81686e3c-ffffffff81686ff4: uart_add_one_port.cold (STB_LOCAL)
ffffffff81683900-ffffffff81683ca9: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff816a9524-ffffffff816a96e2: uart_add_one_port.cold (STB_LOCAL)
ffffffff816a5fa0-ffffffff816a6357: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2852
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8175c266-ffffffff8175c284: uart_add_one_port.cold (STB_LOCAL)
ffffffff8175b040-ffffffff8175b283: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2859
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81c07de7-ffffffff81c07e05: uart_add_one_port.cold (STB_LOCAL)
ffffffff81776120-ffffffff81776363: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2858
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81bf9987-ffffffff81bf99a5: uart_add_one_port.cold (STB_LOCAL)
ffffffff817598c0-ffffffff81759aef: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2873
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81cf9b99-ffffffff81cf9bb7: uart_add_one_port.cold (STB_LOCAL)
ffffffff817dd9e0-ffffffff817ddd98: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2920
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81ec1e50-ffffffff81ec1e71: uart_add_one_port.cold (STB_LOCAL)
ffffffff8191c550-ffffffff8191c92c: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a78500)
Location: drivers/tty/serial/serial_core.c:3053
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81a78500-ffffffff81a78946: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_port.c (ffffffff81ac45d0)
Location: drivers/tty/serial/serial_port.c:73
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81ac45d0-ffffffff81ac45e8: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_port.c (ffffffff81b174d0)
Location: drivers/tty/serial/serial_port.c:96
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff81b174d0-ffffffff81b174e8: uart_add_one_port (STB_GLOBAL)
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
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff800010882298)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
```
**Symbols:**

```
ffff800010882298-ffff8000108827cc: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f7ec)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/amba-pl011.c:pl011_register_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/meson_uart.c:meson_uart_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/msm_serial.c:msm_serial_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_probe
  - drivers/tty/serial/owl-uart.c:owl_uart_probe
  - drivers/tty/serial/rda-uart.c:rda_uart_probe
```
**Symbols:**

```
c097f7ec-c097fd28: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000925590)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
c000000000925590-c000000000925c30: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054c90c)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sifive.c:sifive_serial_probe
```
**Symbols:**

```
ffffffe00054c90c-ffffffe00054cd34: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8166ef84-ffffffff8166f142: uart_add_one_port.cold (STB_LOCAL)
ffffffff8166ba00-ffffffff8166bdb7: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8164e0b4-ffffffff8164e272: uart_add_one_port.cold (STB_LOCAL)
ffffffff8164ab60-ffffffff8164af17: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff8169d364-ffffffff8169d522: uart_add_one_port.cold (STB_LOCAL)
ffffffff81699de0-ffffffff8169a197: uart_add_one_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int uart_add_one_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2787
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_init
  - drivers/tty/serial/8250/8250_core.c:serial8250_unregister_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/max310x.c:max310x_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
```
**Symbols:**

```
ffffffff816b7853-ffffffff816b7a11: uart_add_one_port.cold (STB_LOCAL)
ffffffff816b49e0-ffffffff816b4d97: uart_add_one_port (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct uart_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct uart_port *uport</code>
</li>
</ul>
</details>
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
