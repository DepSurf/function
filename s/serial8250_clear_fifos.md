# Function: <code>serial8250_clear_fifos</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81506d20)
Location: drivers/tty/serial/8250/8250_port.c:497
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
```
**Symbols:**

```
ffffffff81506d20-ffffffff81506d5a: serial8250_clear_fifos.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558b23)
Location: drivers/tty/serial/8250/8250_port.c:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff815584f0-ffffffff8155852a: serial8250_clear_fifos.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81585332)
Location: drivers/tty/serial/8250/8250_port.c:519
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff81584d00-ffffffff81584d3a: serial8250_clear_fifos.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void serial8250_clear_fifos(struct uart_8250_port *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598180)
Location: drivers/tty/serial/8250/8250_port.c:535
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
**Symbols:**

```
ffffffff81598180-ffffffff815981c5: serial8250_clear_fifos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serial8250_clear_fifos(struct uart_8250_port *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fcdf0)
Location: drivers/tty/serial/8250/8250_port.c:552
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
**Symbols:**

```
ffffffff815fcdf0-ffffffff815fce47: serial8250_clear_fifos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81639018)
Location: drivers/tty/serial/8250/8250_port.c:553
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff816371a0-ffffffff816371ec: serial8250_clear_fifos.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81657316)
Location: drivers/tty/serial/8250/8250_port.c:553
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff816556c0-ffffffff8165570c: serial8250_clear_fifos.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816899cf)
Location: drivers/tty/serial/8250/8250_port.c:561
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff81689870-ffffffff816898c0: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac03f)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff816abee0-ffffffff816abf30: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f0de)
Location: drivers/tty/serial/8250/8250_port.c:550
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff8175eb00-ffffffff8175eb52: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779f5e)
Location: drivers/tty/serial/8250/8250_port.c:551
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:do_set_rxtrig
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff81779980-ffffffff817799d2: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175da2f)
Location: drivers/tty/serial/8250/8250_port.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff8175d2b0-ffffffff8175d302: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e195d)
Location: drivers/tty/serial/8250/8250_port.c:556
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff817e1130-ffffffff817e1182: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81920915)
Location: drivers/tty/serial/8250/8250_port.c:543
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff8191feb0-ffffffff8191ff0b: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7d025)
Location: drivers/tty/serial/8250/8250_port.c:543
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff81a7c4d0-ffffffff81a7c52b: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac8624)
Location: drivers/tty/serial/8250/8250_port.c:483
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff81ac7be0-ffffffff81ac7c3b: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b704)
Location: drivers/tty/serial/8250/8250_port.c:484
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff81b1ac90-ffffffff81b1aceb: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886ce8)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffff800010886b70-ffff800010886bd0: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c09852ac)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
c0985148-c098519c: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092dccc)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
c00000000092dae0-c00000000092db6c: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551d26)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffe000551c02-ffffffe000551c40: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671aaf)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff81671950-ffffffff816719a0: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650baf)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff81650a50-ffffffff81650aa0: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169fe7f)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff8169fd20-ffffffff8169fd70: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba33f)
Location: drivers/tty/serial/8250/8250_port.c:554
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_shutdown
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:serial8250_clear_and_reinit_fifos
```
**Symbols:**

```
ffffffff816ba1e0-ffffffff816ba230: serial8250_clear_fifos.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
