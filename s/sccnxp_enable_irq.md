# Function: <code>sccnxp_enable_irq</code>

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
In drivers/tty/serial/sccnxp.c (ffffffff8150e84d)
Location: drivers/tty/serial/sccnxp.c:323
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
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
In drivers/tty/serial/sccnxp.c (ffffffff815611cd)
Location: drivers/tty/serial/sccnxp.c:323
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff8158d93d)
Location: drivers/tty/serial/sccnxp.c:323
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff815a19be)
Location: drivers/tty/serial/sccnxp.c:323
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81607117)
Location: drivers/tty/serial/sccnxp.c:319
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff816407d7)
Location: drivers/tty/serial/sccnxp.c:319
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165e980)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff8165e980-ffffffff8165e9c0: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81693f60)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff81693f60-ffffffff81693f9d: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816b6b00)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff816b6b00-ffffffff816b6b3d: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8176a881)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff817854d1)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81768e01)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff817ed89d)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff8192d80d)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81a8ba4d)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81ad721d)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81b2a4bd)
Location: drivers/tty/serial/sccnxp.c:354
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
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
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffff80001089fa20)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffff80001089fa20-ffff80001089fa78: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c0999a84)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
c0999a84-c0999ac8: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c00000000093c8e0)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
c00000000093c8e0-c00000000093c920: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffe00055c348)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffe00055c348-ffffffe00055c39a: sccnxp_enable_irq (STB_LOCAL)
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
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8167c560)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff8167c560-ffffffff8167c59d: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165b650)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff8165b650-ffffffff8165b68d: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816aa940)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff816aa940-ffffffff816aa97d: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sccnxp_enable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816c4da0)
Location: drivers/tty/serial/sccnxp.c:358
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_startup
  - drivers/tty/serial/sccnxp.c:sccnxp_start_tx
```
**Symbols:**

```
ffffffff816c4da0-ffffffff816c4ddd: sccnxp_enable_irq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
