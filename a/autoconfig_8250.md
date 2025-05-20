# Function: <code>autoconfig_8250</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff8150742e)
Location: drivers/tty/serial/8250/8250_port.c:835
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81558c2f)
Location: drivers/tty/serial/8250/8250_port.c:931
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8158543d)
Location: drivers/tty/serial/8250/8250_port.c:934
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8159a289)
Location: drivers/tty/serial/8250/8250_port.c:950
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815ff273)
Location: drivers/tty/serial/8250/8250_port.c:969
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81639330)
Location: drivers/tty/serial/8250/8250_port.c:970
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81657629)
Location: drivers/tty/serial/8250/8250_port.c:970
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8168d2dc)
Location: drivers/tty/serial/8250/8250_port.c:978
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816af82c)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void autoconfig_8250(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e280)
Location: drivers/tty/serial/8250/8250_port.c:995
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff8175e280-ffffffff8175e336: autoconfig_8250 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void autoconfig_8250(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779100)
Location: drivers/tty/serial/8250/8250_port.c:996
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
**Symbols:**

```
ffffffff81779100-ffffffff817791b6: autoconfig_8250 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8176132e)
Location: drivers/tty/serial/8250/8250_port.c:1000
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e52df)
Location: drivers/tty/serial/8250/8250_port.c:1001
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff819248cf)
Location: drivers/tty/serial/8250/8250_port.c:988
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a8123f)
Location: drivers/tty/serial/8250/8250_port.c:990
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acc866)
Location: drivers/tty/serial/8250/8250_port.c:937
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1f006)
Location: drivers/tty/serial/8250/8250_port.c:938
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffff80001088ac60)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (c0988840)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (c000000000933260)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000554b94)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8167529c)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8165437c)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a366c)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816bdafc)
Location: drivers/tty/serial/8250/8250_port.c:960
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:autoconfig
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
</ul>
