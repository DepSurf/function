# Function: <code>sccnxp_set_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8150e740)
Location: drivers/tty/serial/sccnxp.c:339
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff8150e740-ffffffff8150e7b0: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81561df8)
Location: drivers/tty/serial/sccnxp.c:339
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff81560c30-ffffffff81560ca0: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8158e568)
Location: drivers/tty/serial/sccnxp.c:339
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff8158d3a0-ffffffff8158d410: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff815a25f7)
Location: drivers/tty/serial/sccnxp.c:339
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff815a1430-ffffffff815a14a2: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816083f7)
Location: drivers/tty/serial/sccnxp.c:335
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff81606b90-ffffffff81606c04: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81641a1f)
Location: drivers/tty/serial/sccnxp.c:335
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff81640250-ffffffff816402c3: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165eae0)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8165eae0-ffffffff8165eb49: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816940c0)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816940c0-ffffffff81694121: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816b6c60)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816b6c60-ffffffff816b6cc1: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176bed5)
Location: drivers/tty/serial/sccnxp.c:370
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff8176a5f0-ffffffff8176a67f: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81786ab5)
Location: drivers/tty/serial/sccnxp.c:370
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff81785240-ffffffff817852cf: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176a415)
Location: drivers/tty/serial/sccnxp.c:370
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
```
**Symbols:**

```
ffffffff81768b60-ffffffff81768bf4: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:370
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff817ed940-ffffffff817eda16: sccnxp_set_bit (STB_LOCAL)
ffffffff81cfa4eb-ffffffff81cfa50c: sccnxp_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:370
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff8192d8c0-ffffffff8192d9b5: sccnxp_set_bit (STB_LOCAL)
ffffffff81ec2724-ffffffff81ec2745: sccnxp_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:370
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81a8bb10-ffffffff81a8bc05: sccnxp_set_bit (STB_LOCAL)
ffffffff82096239-ffffffff8209625a: sccnxp_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:370
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81ad72e0-ffffffff81ad73d5: sccnxp_set_bit (STB_LOCAL)
ffffffff82117160-ffffffff82117181: sccnxp_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:370
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81b2a580-ffffffff81b2a675: sccnxp_set_bit (STB_LOCAL)
ffffffff821f4eba-ffffffff821f4edb: sccnxp_set_bit.cold (STB_LOCAL)
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
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffff80001089fa78)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffff80001089fa78-ffff80001089fb0c: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c0999bd8)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c0999bd8-c0999c38: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c00000000093ca80)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c00000000093ca80-c00000000093caf8: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffe00055c4a8)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffe00055c4a8-ffffffe00055c530: sccnxp_set_bit (STB_LOCAL)
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
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8167c6c0)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8167c6c0-ffffffff8167c721: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165b7b0)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8165b7b0-ffffffff8165b811: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816aaaa0)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816aaaa0-ffffffff816aab01: sccnxp_set_bit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sccnxp_set_bit(struct uart_port *port, int sig, int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816c4f00)
Location: drivers/tty/serial/sccnxp.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_probe
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_set_mctrl
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816c4f00-ffffffff816c4f61: sccnxp_set_bit (STB_LOCAL)
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
