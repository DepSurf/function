# Function: <code>sysrq_mask</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81743210)
Location: drivers/tty/sysrq.c:71
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81743210-ffffffff8174322e: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8175f090)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff8175f090-ffffffff8175f0ae: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81742f00)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81742f00-ffffffff81742f1e: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81cf8e1b-ffffffff81cf8e2f: sysrq_mask.cold (STB_LOCAL)
ffffffff817c3cb0-ffffffff817c3cdf: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81ec0f70-ffffffff81ec0f84: sysrq_mask.cold (STB_LOCAL)
ffffffff81900a40-ffffffff81900a77: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff820953aa-ffffffff820953be: sysrq_mask.cold (STB_LOCAL)
ffffffff81a5a660-ffffffff81a5a697: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff821161f9-ffffffff8211620d: sysrq_mask.cold (STB_LOCAL)
ffffffff81aa4c90-ffffffff81aa4cc7: sysrq_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sysrq_mask();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:72
Inline: False
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff821f3f0b-ffffffff821f3f1f: sysrq_mask.cold (STB_LOCAL)
ffffffff81af7690-ffffffff81af76c7: sysrq_mask (STB_GLOBAL)
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
