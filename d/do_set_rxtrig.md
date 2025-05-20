# Function: <code>do_set_rxtrig</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff81506dff)
Location: drivers/tty/serial/8250/8250_port.c:2599
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815585cf)
Location: drivers/tty/serial/8250/8250_port.c:2862
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81584ddf)
Location: drivers/tty/serial/8250/8250_port.c:2906
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81598b56)
Location: drivers/tty/serial/8250/8250_port.c:2941
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd946)
Location: drivers/tty/serial/8250/8250_port.c:2995
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81637296)
Location: drivers/tty/serial/8250/8250_port.c:2978
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816557b6)
Location: drivers/tty/serial/8250/8250_port.c:2996
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81689961)
Location: drivers/tty/serial/8250/8250_port.c:2988
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816abfd1)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_set_rxtrig(struct tty_port *port, unsigned char bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175f070)
Location: drivers/tty/serial/8250/8250_port.c:2995
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
```
**Symbols:**

```
ffffffff8175f070-ffffffff8175f131: do_set_rxtrig (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_set_rxtrig(struct tty_port *port, unsigned char bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779ef0)
Location: drivers/tty/serial/8250/8250_port.c:3039
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
```
**Symbols:**

```
ffffffff81779ef0-ffffffff81779fb1: do_set_rxtrig (STB_LOCAL)
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175d9c1)
Location: drivers/tty/serial/8250/8250_port.c:3065
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e18d3)
Location: drivers/tty/serial/8250/8250_port.c:3098
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81920887)
Location: drivers/tty/serial/8250/8250_port.c:3106
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7cf97)
Location: drivers/tty/serial/8250/8250_port.c:3110
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac85b7)
Location: drivers/tty/serial/8250/8250_port.c:3120
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b697)
Location: drivers/tty/serial/8250/8250_port.c:3122
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:rx_trig_bytes_store
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
In drivers/tty/serial/8250/8250_port.c (ffff800010886c7c)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (c098523c)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (c00000000092dc58)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000551cce)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81671a41)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81650b41)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8169fe11)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba2d1)
Location: drivers/tty/serial/8250/8250_port.c:2911
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_attr_rx_trig_bytes
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
