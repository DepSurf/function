# Function: <code>lp_irq_unmask</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:265
Inline: False
```
**Symbols:**

```
ffffffff81475820-ffffffff8147582b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (0)
Location: drivers/gpio/gpio-lynxpoint.c:265
Inline: False
```
**Symbols:**

```
ffffffff81497df0-ffffffff81497dfb: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814a11a0)
Location: drivers/gpio/gpio-lynxpoint.c:265
Inline: True
```
**Symbols:**

```
ffffffff814a11a0-ffffffff814a11ab: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff814dfb60)
Location: drivers/gpio/gpio-lynxpoint.c:265
Inline: True
```
**Symbols:**

```
ffffffff814dfb60-ffffffff814dfb6b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8150ef20)
Location: drivers/gpio/gpio-lynxpoint.c:265
Inline: True
```
**Symbols:**

```
ffffffff8150ef20-ffffffff8150ef2b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81524590)
Location: drivers/gpio/gpio-lynxpoint.c:253
Inline: True
```
**Symbols:**

```
ffffffff81524590-ffffffff8152459b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81552c40)
Location: drivers/gpio/gpio-lynxpoint.c:253
Inline: False
```
**Symbols:**

```
ffffffff81552c40-ffffffff81552c4b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81574230)
Location: drivers/gpio/gpio-lynxpoint.c:259
Inline: False
```
**Symbols:**

```
ffffffff81574230-ffffffff8157423b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff8155a840)
Location: drivers/gpio/gpio-lynxpoint.c:259
Inline: False
```
**Symbols:**

```
ffffffff8155a840-ffffffff8155a84b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81568560)
Location: drivers/gpio/gpio-lynxpoint.c:259
Inline: False
```
**Symbols:**

```
ffffffff81568560-ffffffff8156856b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void lp_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-lynxpoint.c (ffffffff81582480)
Location: drivers/gpio/gpio-lynxpoint.c:259
Inline: False
```
**Symbols:**

```
ffffffff81582480-ffffffff8158248b: lp_irq_unmask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
