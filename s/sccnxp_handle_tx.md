# Function: <code>sccnxp_handle_tx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8150fd1e)
Location: drivers/tty/serial/sccnxp.c:409
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8156226a)
Location: drivers/tty/serial/sccnxp.c:409
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8158e9da)
Location: drivers/tty/serial/sccnxp.c:409
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff815a2937)
Location: drivers/tty/serial/sccnxp.c:409
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81607ae7)
Location: drivers/tty/serial/sccnxp.c:405
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816411bd)
Location: drivers/tty/serial/sccnxp.c:405
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165f435)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81694a5c)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816b75fc)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176b370)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8176b370-ffffffff8176b62d: sccnxp_handle_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81785f50)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81785f50-ffffffff81786207: sccnxp_handle_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff817698c0)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff817698c0-ffffffff81769b73: sccnxp_handle_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff817ef0e0-ffffffff817ef292: sccnxp_handle_tx (STB_LOCAL)
ffffffff81cfa684-ffffffff81cfa699: sccnxp_handle_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8192f220-ffffffff8192f404: sccnxp_handle_tx (STB_LOCAL)
ffffffff81ec28c0-ffffffff81ec28d5: sccnxp_handle_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81a8d5b0-ffffffff81a8d79b: sccnxp_handle_tx (STB_LOCAL)
ffffffff82096313-ffffffff82096328: sccnxp_handle_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:440
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81ad8d30-ffffffff81ad8f22: sccnxp_handle_tx (STB_LOCAL)
ffffffff8211723a-ffffffff82117264: sccnxp_handle_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sccnxp_handle_tx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:439
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81b2c020-ffffffff81b2c212: sccnxp_handle_tx (STB_LOCAL)
ffffffff821f4f93-ffffffff821f4fbd: sccnxp_handle_tx.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffff80001089fcd4)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c099a9e8)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c00000000093cf00)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffe00055c6e2)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8167d05c)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165c14c)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816ab43c)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816c589c)
Location: drivers/tty/serial/sccnxp.c:444
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
