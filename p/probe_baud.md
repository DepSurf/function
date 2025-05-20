# Function: <code>probe_baud</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff815093ac)
Location: drivers/tty/serial/8250/8250_port.c:2899
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8155b25c)
Location: drivers/tty/serial/8250/8250_port.c:3160
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815879ec)
Location: drivers/tty/serial/8250/8250_port.c:3204
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8159be7c)
Location: drivers/tty/serial/8250/8250_port.c:3239
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8160114c)
Location: drivers/tty/serial/8250/8250_port.c:3293
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8163a39c)
Location: drivers/tty/serial/8250/8250_port.c:3271
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816586cc)
Location: drivers/tty/serial/8250/8250_port.c:3287
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8168db92)
Location: drivers/tty/serial/8250/8250_port.c:3279
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816b00e2)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int probe_baud(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e490)
Location: drivers/tty/serial/8250/8250_port.c:3302
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
```
**Symbols:**

```
ffffffff8175e490-ffffffff8175e52c: probe_baud (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int probe_baud(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779310)
Location: drivers/tty/serial/8250/8250_port.c:3346
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
```
**Symbols:**

```
ffffffff81779310-ffffffff817793ac: probe_baud (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81761e6f)
Location: drivers/tty/serial/8250/8250_port.c:3372
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5ecf)
Location: drivers/tty/serial/8250/8250_port.c:3405
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff819253f2)
Location: drivers/tty/serial/8250/8250_port.c:3465
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81d22)
Location: drivers/tty/serial/8250/8250_port.c:3467
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd322)
Location: drivers/tty/serial/8250/8250_port.c:3474
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b203f2)
Location: drivers/tty/serial/8250/8250_port.c:3476
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffff80001088b554)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (c0989080)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (c000000000933f40)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffe0005551d8)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81675b52)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81654c32)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816a3f22)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816be3b2)
Location: drivers/tty/serial/8250/8250_port.c:3202
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_setup
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
