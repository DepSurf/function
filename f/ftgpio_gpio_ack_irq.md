# Function: <code>ftgpio_gpio_ack_irq</code>

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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ftgpio_gpio_ack_irq(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (ffff8000106cecb0)
Location: drivers/gpio/gpio-ftgpio010.c:56
Inline: True
Inline callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
**Symbols:**

```
ffff8000106ce6b0-ffff8000106ce6f8: ftgpio_gpio_ack_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftgpio_gpio_ack_irq(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (c0868478)
Location: drivers/gpio/gpio-ftgpio010.c:56
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
**Symbols:**

```
c0868478-c08684bc: ftgpio_gpio_ack_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftgpio_gpio_ack_irq(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (c0000000008497c0)
Location: drivers/gpio/gpio-ftgpio010.c:56
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
**Symbols:**

```
c0000000008497c0-c000000000849828: ftgpio_gpio_ack_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftgpio_gpio_ack_irq(struct irq_data *d);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-ftgpio010.c (ffffffe0004ae49a)
Location: drivers/gpio/gpio-ftgpio010.c:56
Inline: False
Direct callers:
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_set_irq_type
```
**Symbols:**

```
ffffffe0004ae49a-ffffffe0004ae500: ftgpio_gpio_ack_irq (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
