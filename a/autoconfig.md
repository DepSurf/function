# Function: <code>autoconfig</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff8150713c)
Location: drivers/tty/serial/8250/8250_port.c:1067
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8155893f)
Location: drivers/tty/serial/8250/8250_port.c:1163
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8158514f)
Location: drivers/tty/serial/8250/8250_port.c:1166
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81599c92)
Location: drivers/tty/serial/8250/8250_port.c:1182
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815feb82)
Location: drivers/tty/serial/8250/8250_port.c:1201
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81638dd7)
Location: drivers/tty/serial/8250/8250_port.c:1202
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816570d5)
Location: drivers/tty/serial/8250/8250_port.c:1202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1210
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff8168ce20-ffffffff8168d3ad: autoconfig (STB_LOCAL)
ffffffff8168dc8f-ffffffff8168dcaa: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff816af370-ffffffff816af8fd: autoconfig (STB_LOCAL)
ffffffff816b01df-ffffffff816b01fa: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1197
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81762be0-ffffffff817630f9: autoconfig (STB_LOCAL)
ffffffff817635ea-ffffffff81763606: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1198
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff8177dc40-ffffffff8177e159: autoconfig (STB_LOCAL)
ffffffff81c07ece-ffffffff81c07eea: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1202
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81761130-ffffffff81761697: autoconfig (STB_LOCAL)
ffffffff81bf9a8f-ffffffff81bf9aaa: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1203
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff817e50e0-ffffffff817e56b3: autoconfig (STB_LOCAL)
ffffffff81cf9f7e-ffffffff81cf9f99: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1190
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff819246d0-ffffffff81924cb1: autoconfig (STB_LOCAL)
ffffffff81ec2230-ffffffff81ec224d: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81040)
Location: drivers/tty/serial/8250/8250_port.c:1193
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81a81040-ffffffff81a815f4: autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acc660)
Location: drivers/tty/serial/8250/8250_port.c:1147
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81acc660-ffffffff81accc17: autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1ee00)
Location: drivers/tty/serial/8250/8250_port.c:1147
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81b1ee00-ffffffff81b1f3b7: autoconfig (STB_LOCAL)
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
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff80001088a7b8)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffff80001088a7b8-ffff80001088ad5c: autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0988428)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
c0988428-c0988914: autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c000000000932c50)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
c000000000932c50-c0000000009333c4: autoconfig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000554800)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffe000554800-ffffffe000554c10: autoconfig (STB_LOCAL)
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
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81674de0-ffffffff8167536d: autoconfig (STB_LOCAL)
ffffffff81675c4f-ffffffff81675c6a: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff81653ec0-ffffffff8165444d: autoconfig (STB_LOCAL)
ffffffff81654d2f-ffffffff81654d4a: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff816a31b0-ffffffff816a373d: autoconfig (STB_LOCAL)
ffffffff816a401f-ffffffff816a403a: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void autoconfig(struct uart_8250_port *up);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (0)
Location: drivers/tty/serial/8250/8250_port.c:1159
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
```
**Symbols:**

```
ffffffff816bd640-ffffffff816bdbcd: autoconfig (STB_LOCAL)
ffffffff816be4af-ffffffff816be4ca: autoconfig.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
