# Function: <code>sccnxp_handle_rx</code>

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
In drivers/tty/serial/sccnxp.c (ffffffff8150fbd8)
Location: drivers/tty/serial/sccnxp.c:353
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
In drivers/tty/serial/sccnxp.c (ffffffff81562118)
Location: drivers/tty/serial/sccnxp.c:353
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
In drivers/tty/serial/sccnxp.c (ffffffff8158e888)
Location: drivers/tty/serial/sccnxp.c:353
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
In drivers/tty/serial/sccnxp.c (ffffffff815a2b58)
Location: drivers/tty/serial/sccnxp.c:353
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
In drivers/tty/serial/sccnxp.c (ffffffff81607d08)
Location: drivers/tty/serial/sccnxp.c:349
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
In drivers/tty/serial/sccnxp.c (ffffffff816412ef)
Location: drivers/tty/serial/sccnxp.c:349
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
In drivers/tty/serial/sccnxp.c (ffffffff8165f52c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff81694b4c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff816b76ec)
Location: drivers/tty/serial/sccnxp.c:388
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
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176b630)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8176b630-ffffffff8176b978: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81786210)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81786210-ffffffff81786558: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81769b80)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81769b80-ffffffff81769eb8: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff817edaa0)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff817edaa0-ffffffff817edd4f: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8192da50)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8192da50-ffffffff8192dd2b: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81a8bcc0)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81a8bcc0-ffffffff81a8bf9b: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7490)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81ad7490-ffffffff81ad7776: sccnxp_handle_rx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sccnxp_handle_rx(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81b2a730)
Location: drivers/tty/serial/sccnxp.c:384
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81b2a730-ffffffff81b2aa32: sccnxp_handle_rx (STB_LOCAL)
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
In drivers/tty/serial/sccnxp.c (ffff80001089fd9c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (c099aab0)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (c00000000093cff8)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffe00055c6e8)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff8167d14c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff8165c23c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff816ab52c)
Location: drivers/tty/serial/sccnxp.c:388
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
In drivers/tty/serial/sccnxp.c (ffffffff816c598c)
Location: drivers/tty/serial/sccnxp.c:388
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
