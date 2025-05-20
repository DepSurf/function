# Function: <code>gpiochip_irq_unmask</code>

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
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e840)
Location: drivers/gpio/gpiolib.c:2516
Inline: False
```
**Symbols:**

```
ffffffff8160e840-ffffffff8160e877: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816350d0)
Location: drivers/gpio/gpiolib.c:1402
Inline: False
```
**Symbols:**

```
ffffffff816350d0-ffffffff81635107: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81618b40)
Location: drivers/gpio/gpiolib.c:1391
Inline: False
```
**Symbols:**

```
ffffffff81618b40-ffffffff81618b77: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687cc0)
Location: drivers/gpio/gpiolib.c:1413
Inline: False
```
**Symbols:**

```
ffffffff81687cc0-ffffffff81687cf7: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a3220)
Location: drivers/gpio/gpiolib.c:1455
Inline: False
```
**Symbols:**

```
ffffffff817a3220-ffffffff817a3262: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba6d0)
Location: drivers/gpio/gpiolib.c:1525
Inline: False
```
**Symbols:**

```
ffffffff818ba6d0-ffffffff818ba712: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd7d0)
Location: drivers/gpio/gpiolib.c:1553
Inline: False
```
**Symbols:**

```
ffffffff818fd7d0-ffffffff818fd812: gpiochip_irq_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_irq_unmask(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944d80)
Location: drivers/gpio/gpiolib.c:1734
Inline: False
```
**Symbols:**

```
ffffffff81944d80-ffffffff81944dc2: gpiochip_irq_unmask (STB_LOCAL)
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
