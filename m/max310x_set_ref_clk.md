# Function: <code>max310x_set_ref_clk</code>

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
In drivers/tty/serial/max310x.c (ffffffff8150e128)
Location: drivers/tty/serial/max310x.c:529
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff81560596)
Location: drivers/tty/serial/max310x.c:537
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff8158cd05)
Location: drivers/tty/serial/max310x.c:537
Inline: True
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
In drivers/tty/serial/max310x.c (ffffffff815a0d79)
Location: drivers/tty/serial/max310x.c:537
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
In drivers/tty/serial/max310x.c (ffffffff816064af)
Location: drivers/tty/serial/max310x.c:533
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
In drivers/tty/serial/max310x.c (ffffffff8163f0cd)
Location: drivers/tty/serial/max310x.c:534
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff8165d2cd)
Location: drivers/tty/serial/max310x.c:534
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff816931e3)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff816b5d83)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int max310x_set_ref_clk(struct device *dev, struct max310x_port *s, long unsigned int freq, bool xtal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:555
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81767f20-ffffffff81768197: max310x_set_ref_clk (STB_LOCAL)
ffffffff81769ee7-ffffffff81769efc: max310x_set_ref_clk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int max310x_set_ref_clk(struct device *dev, struct max310x_port *s, long unsigned int freq, bool xtal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:555
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81782c80-ffffffff81782ef9: max310x_set_ref_clk (STB_LOCAL)
ffffffff81c08167-ffffffff81c0817c: max310x_set_ref_clk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int max310x_set_ref_clk(struct device *dev, struct max310x_port *s, long unsigned int freq, bool xtal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:555
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81766560-ffffffff817667d9: max310x_set_ref_clk (STB_LOCAL)
ffffffff81bf9d2b-ffffffff81bf9d40: max310x_set_ref_clk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 max310x_set_ref_clk(struct device *dev, struct max310x_port *s, long unsigned int freq, bool xtal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:555
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff817eaf30-ffffffff817eb1a9: max310x_set_ref_clk (STB_LOCAL)
ffffffff81cfa3ca-ffffffff81cfa3df: max310x_set_ref_clk.cold (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (ffffffff8192b0c9)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff81a89825)
Location: drivers/tty/serial/max310x.c:581
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff81ad4ff4)
Location: drivers/tty/serial/max310x.c:586
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s32 max310x_set_ref_clk(struct device *dev, struct max310x_port *s, long unsigned int freq, bool xtal);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81b27740)
Location: drivers/tty/serial/max310x.c:594
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_probe
```
**Symbols:**

```
ffffffff81b27740-ffffffff81b27a06: max310x_set_ref_clk (STB_LOCAL)
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
In drivers/tty/serial/max310x.c (ffff8000108996c4)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (c0993a08)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:555
Inline: False
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
In drivers/tty/serial/max310x.c (ffffffe00055b09e)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff8167b7e3)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff8165a8d3)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff816a9bc3)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
In drivers/tty/serial/max310x.c (ffffffff816c4023)
Location: drivers/tty/serial/max310x.c:555
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_probe
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
</ul>
