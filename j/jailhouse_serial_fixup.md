# Function: <code>jailhouse_serial_fixup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/kernel/jailhouse.c:156
Inline: False
```
**Symbols:**

```
ffffffff810806f0-ffffffff8108076d: jailhouse_serial_fixup (STB_LOCAL)
ffffffff810808f6-ffffffff81080912: jailhouse_serial_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff81080300-ffffffff8108037d: jailhouse_serial_fixup (STB_LOCAL)
ffffffff81bd81cf-ffffffff81bd81eb: jailhouse_serial_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff810811a0-ffffffff8108121d: jailhouse_serial_fixup (STB_LOCAL)
ffffffff81bca009-ffffffff81bca025: jailhouse_serial_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff81090140-ffffffff810901c1: jailhouse_serial_fixup (STB_LOCAL)
ffffffff81c9f318-ffffffff81c9f334: jailhouse_serial_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (0)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff810a11a0-ffffffff810a123d: jailhouse_serial_fixup (STB_LOCAL)
ffffffff81e4eb1a-ffffffff81e4eb36: jailhouse_serial_fixup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810b90c0)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff810b90c0-ffffffff810b91bf: jailhouse_serial_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810bc290)
Location: arch/x86/kernel/jailhouse.c:158
Inline: False
```
**Symbols:**

```
ffffffff810bc290-ffffffff810bc38f: jailhouse_serial_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void jailhouse_serial_fixup(int port, struct uart_port *up, u32 *capabilities);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810c3410)
Location: arch/x86/kernel/jailhouse.c:156
Inline: False
```
**Symbols:**

```
ffffffff810c3410-ffffffff810c350f: jailhouse_serial_fixup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
