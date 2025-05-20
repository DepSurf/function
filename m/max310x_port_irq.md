# Function: <code>max310x_port_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8150d4f0)
Location: drivers/tty/serial/max310x.c:686
Inline: False
```
**Symbols:**

```
ffffffff8150d4f0-ffffffff8150d843: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8155f770)
Location: drivers/tty/serial/max310x.c:692
Inline: False
```
**Symbols:**

```
ffffffff8155f770-ffffffff8155faa8: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8158bec0)
Location: drivers/tty/serial/max310x.c:692
Inline: False
```
**Symbols:**

```
ffffffff8158bec0-ffffffff8158c1ff: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff815a0000)
Location: drivers/tty/serial/max310x.c:692
Inline: False
```
**Symbols:**

```
ffffffff815a0000-ffffffff815a0339: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81605730)
Location: drivers/tty/serial/max310x.c:688
Inline: False
```
**Symbols:**

```
ffffffff81605730-ffffffff81605a6c: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163ffe0)
Location: drivers/tty/serial/max310x.c:764
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff8163ffe0-ffffffff81640150: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165e1f0)
Location: drivers/tty/serial/max310x.c:770
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff8165e1f0-ffffffff8165e371: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff81692b20-ffffffff81692f5a: max310x_port_irq (STB_LOCAL)
ffffffff816939a9-ffffffff816939e1: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff816b56c0-ffffffff816b5afd: max310x_port_irq (STB_LOCAL)
ffffffff816b6549-ffffffff816b6581: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81768a40)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff81768a40-ffffffff81768b7d: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817837e0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff817837e0-ffffffff8178391d: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817670d0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff817670d0-ffffffff8176720d: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817ebaa0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff817ebaa0-ffffffff817ebbdd: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8192c920)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff8192c920-ffffffff8192ca64: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81a8a2e0)
Location: drivers/tty/serial/max310x.c:804
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff81a8a2e0-ffffffff81a8a41e: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81ad5ab0)
Location: drivers/tty/serial/max310x.c:809
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff81ad5ab0-ffffffff81ad5bef: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81b28d60)
Location: drivers/tty/serial/max310x.c:826
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff81b28d60-ffffffff81b28e9e: max310x_port_irq (STB_LOCAL)
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
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898ee0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffff800010898ee0-ffff8000108992cc: max310x_port_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c099448c)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
c099448c-c09948c0: max310x_port_irq (STB_LOCAL)
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
Location: drivers/tty/serial/max310x.c:797
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffe00055b8f2)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffe00055b8f2-ffffffe00055bc6c: max310x_port_irq (STB_LOCAL)
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
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff8167b120-ffffffff8167b55d: max310x_port_irq (STB_LOCAL)
ffffffff8167bfa9-ffffffff8167bfe1: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff8165a210-ffffffff8165a64d: max310x_port_irq (STB_LOCAL)
ffffffff8165b099-ffffffff8165b0d1: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff816a9500-ffffffff816a993d: max310x_port_irq (STB_LOCAL)
ffffffff816aa389-ffffffff816aa3c1: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t max310x_port_irq(struct max310x_port *s, int portno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: drivers/tty/serial/max310x.c:797
Inline: False
Direct callers:
  - drivers/tty/serial/max310x.c:max310x_ist
  - drivers/tty/serial/max310x.c:max310x_ist
```
**Symbols:**

```
ffffffff816c3960-ffffffff816c3d9d: max310x_port_irq (STB_LOCAL)
ffffffff816c47e9-ffffffff816c4821: max310x_port_irq.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>irqreturn_t</code>
</li>
</ul>
</details>
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
