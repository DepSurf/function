# Function: <code>pciserial_detach_ports</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158b280)
Location: drivers/tty/serial/8250/8250_pci.c:3920
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff8158b280-ffffffff8158b2ce: pciserial_detach_ports (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159dcb0)
Location: drivers/tty/serial/8250/8250_pci.c:3559
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff8159dcb0-ffffffff8159dcfe: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816031c0)
Location: drivers/tty/serial/8250/8250_pci.c:3572
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff816031c0-ffffffff81603211: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163c5c0)
Location: drivers/tty/serial/8250/8250_pci.c:3567
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff8163c5c0-ffffffff8163c611: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165a810)
Location: drivers/tty/serial/8250/8250_pci.c:3677
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff8165a810-ffffffff8165a861: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8168fe70)
Location: drivers/tty/serial/8250/8250_pci.c:3769
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff8168fe70-ffffffff8168febf: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b2840)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff816b2840-ffffffff816b288f: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817665d0)
Location: drivers/tty/serial/8250/8250_pci.c:3949
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff817665d0-ffffffff81766621: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81781510)
Location: drivers/tty/serial/8250/8250_pci.c:3992
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81781510-ffffffff81781561: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81764e80)
Location: drivers/tty/serial/8250/8250_pci.c:4018
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81764e80-ffffffff81764ed1: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e95c0)
Location: drivers/tty/serial/8250/8250_pci.c:4061
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff817e95c0-ffffffff817e9611: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81928f10)
Location: drivers/tty/serial/8250/8250_pci.c:3945
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81928f10-ffffffff81928f69: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85880)
Location: drivers/tty/serial/8250/8250_pci.c:3933
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81a85880-ffffffff81a858d9: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad0fe0)
Location: drivers/tty/serial/8250/8250_pci.c:3896
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81ad0fe0-ffffffff81ad1039: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b24e40)
Location: drivers/tty/serial/8250/8250_pci.c:4152
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81b24e40-ffffffff81b24e99: pciserial_detach_ports (STB_LOCAL)
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
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088de78)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffff80001088de78-ffff80001088dee4: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c098c16c)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
c098c16c-c098c1d4: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (c000000000936510)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
c000000000936510-c0000000009365b8: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000557dc0)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffe000557dc0-ffffffe000557e1e: pciserial_detach_ports (STB_LOCAL)
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
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816782b0)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff816782b0-ffffffff816782ff: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81657390)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff81657390-ffffffff816573df: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a6680)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff816a6680-ffffffff816a66cf: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pciserial_detach_ports(struct serial_private *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c0ae0)
Location: drivers/tty/serial/8250/8250_pci.c:3957
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_error_detected
  - drivers/tty/serial/8250/8250_pci.c:pciserial_remove_one
```
**Symbols:**

```
ffffffff816c0ae0-ffffffff816c0b2f: pciserial_detach_ports (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
