# Function: <code>sccnxp_disable_irq</code>

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
In drivers/tty/serial/sccnxp.c (ffffffff8150ed84)
Location: drivers/tty/serial/sccnxp.c:331
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
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
In drivers/tty/serial/sccnxp.c (ffffffff81561284)
Location: drivers/tty/serial/sccnxp.c:331
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
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
In drivers/tty/serial/sccnxp.c (ffffffff8158d9f4)
Location: drivers/tty/serial/sccnxp.c:331
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
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
In drivers/tty/serial/sccnxp.c (ffffffff815a1a74)
Location: drivers/tty/serial/sccnxp.c:331
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
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
In drivers/tty/serial/sccnxp.c (ffffffff816071cd)
Location: drivers/tty/serial/sccnxp.c:327
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
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
In drivers/tty/serial/sccnxp.c (ffffffff8164088d)
Location: drivers/tty/serial/sccnxp.c:327
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165e930)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8165e930-ffffffff8165e971: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff81693f20)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81693f20-ffffffff81693f5e: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816b6ac0)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816b6ac0-ffffffff816b6afe: sccnxp_disable_irq (STB_LOCAL)
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
In drivers/tty/serial/sccnxp.c (ffffffff8176b24f)
Location: drivers/tty/serial/sccnxp.c:362
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff81785e2f)
Location: drivers/tty/serial/sccnxp.c:362
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
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
In drivers/tty/serial/sccnxp.c (ffffffff8176979f)
Location: drivers/tty/serial/sccnxp.c:362
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:362
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff817eef80-ffffffff817ef012: sccnxp_disable_irq (STB_LOCAL)
ffffffff81cfa645-ffffffff81cfa684: sccnxp_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:362
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff8192f0b0-ffffffff8192f150: sccnxp_disable_irq (STB_LOCAL)
ffffffff81ec2881-ffffffff81ec28c0: sccnxp_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:362
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81a8d420-ffffffff81a8d4c0: sccnxp_disable_irq (STB_LOCAL)
ffffffff820962d4-ffffffff82096313: sccnxp_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:362
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81ad8ba0-ffffffff81ad8c40: sccnxp_disable_irq (STB_LOCAL)
ffffffff821171fb-ffffffff8211723a: sccnxp_disable_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/sccnxp.c (0)
Location: drivers/tty/serial/sccnxp.c:362
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81b2be90-ffffffff81b2bf30: sccnxp_disable_irq (STB_LOCAL)
ffffffff821f4f54-ffffffff821f4f93: sccnxp_disable_irq.cold (STB_LOCAL)
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
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffff80001089f9c8)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffff80001089f9c8-ffff80001089fa20: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c0999a44)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c0999a44-c0999a84: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (c00000000093c8a0)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c00000000093c8a0-c00000000093c8e0: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffe00055c2f6)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffe00055c2f6-ffffffe00055c348: sccnxp_disable_irq (STB_LOCAL)
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
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8167c520)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8167c520-ffffffff8167c55e: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff8165b610)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8165b610-ffffffff8165b64e: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816aa900)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816aa900-ffffffff816aa93e: sccnxp_disable_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sccnxp_disable_irq(struct uart_port *port, int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/sccnxp.c (ffffffff816c4d60)
Location: drivers/tty/serial/sccnxp.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_shutdown
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816c4d60-ffffffff816c4d9e: sccnxp_disable_irq (STB_LOCAL)
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
