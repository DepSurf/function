# Function: <code>autoconfig_has_efr</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff815063df)
Location: drivers/tty/serial/8250/8250_port.c:747
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81557baf)
Location: drivers/tty/serial/8250/8250_port.c:843
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815843b1)
Location: drivers/tty/serial/8250/8250_port.c:846
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8159a6cd)
Location: drivers/tty/serial/8250/8250_port.c:862
Inline: True
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815ff777)
Location: drivers/tty/serial/8250/8250_port.c:881
Inline: True
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81636c1c)
Location: drivers/tty/serial/8250/8250_port.c:882
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8165512c)
Location: drivers/tty/serial/8250/8250_port.c:882
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8168cb49)
Location: drivers/tty/serial/8250/8250_port.c:890
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816aef78)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81762100)
Location: drivers/tty/serial/8250/8250_port.c:907
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff81762100-ffffffff81762243: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177c8b0)
Location: drivers/tty/serial/8250/8250_port.c:908
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff8177c8b0-ffffffff8177c9f3: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175fce0)
Location: drivers/tty/serial/8250/8250_port.c:912
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff8175fce0-ffffffff8175fe23: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e3c30)
Location: drivers/tty/serial/8250/8250_port.c:913
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff817e3c30-ffffffff817e3d73: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81922870)
Location: drivers/tty/serial/8250/8250_port.c:900
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff81922870-ffffffff819229db: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7f140)
Location: drivers/tty/serial/8250/8250_port.c:902
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff81a7f140-ffffffff81a7f2ab: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81aca6f0)
Location: drivers/tty/serial/8250/8250_port.c:849
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff81aca6f0-ffffffff81aca859: autoconfig_has_efr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void autoconfig_has_efr(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1d7d0)
Location: drivers/tty/serial/8250/8250_port.c:850
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
```
**Symbols:**

```
ffffffff81b1d7d0-ffffffff81b1d939: autoconfig_has_efr (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_port.c (ffff800010889b80)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (c09881a4)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (c0000000009327e4)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000554572)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816749e8)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81653ac8)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a2db8)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816bd248)
Location: drivers/tty/serial/8250/8250_port.c:872
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
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
