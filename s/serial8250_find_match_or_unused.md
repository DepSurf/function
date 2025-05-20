# Function: <code>serial8250_find_match_or_unused</code>

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
In drivers/tty/serial/8250/8250_core.c (ffffffff81504b7d)
Location: drivers/tty/serial/8250/8250_core.c:907
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81556143)
Location: drivers/tty/serial/8250/8250_core.c:915
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815828e3)
Location: drivers/tty/serial/8250/8250_core.c:916
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81596ced)
Location: drivers/tty/serial/8250/8250_core.c:916
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff815fb96d)
Location: drivers/tty/serial/8250/8250_core.c:912
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81634cad)
Location: drivers/tty/serial/8250/8250_core.c:912
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81652efd)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8168794d)
Location: drivers/tty/serial/8250/8250_core.c:909
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816a9ffd)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct uart_8250_port *serial8250_find_match_or_unused(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff8175c7f0)
Location: drivers/tty/serial/8250/8250_core.c:918
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8175c7f0-ffffffff8175c90d: serial8250_find_match_or_unused (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct uart_8250_port *serial8250_find_match_or_unused(struct uart_port *port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_core.c (ffffffff817776c0)
Location: drivers/tty/serial/8250/8250_core.c:918
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff817776c0-ffffffff817777dd: serial8250_find_match_or_unused (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8175b19d)
Location: drivers/tty/serial/8250/8250_core.c:918
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff817ded3f)
Location: drivers/tty/serial/8250/8250_core.c:909
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8191dbe2)
Location: drivers/tty/serial/8250/8250_core.c:910
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81a79b42)
Location: drivers/tty/serial/8250/8250_core.c:917
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81ac52ff)
Location: drivers/tty/serial/8250/8250_core.c:950
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff81b182ff)
Location: drivers/tty/serial/8250/8250_core.c:949
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffff800010884440)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (c0983808)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (c00000000092b45c)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffe00054ff9c)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8166fa6d)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8164eb8d)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff8169de3d)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
In drivers/tty/serial/8250/8250_core.c (ffffffff816b830d)
Location: drivers/tty/serial/8250/8250_core.c:908
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
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
