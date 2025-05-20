# Function: <code>amd_gpio_irq_set_wake</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int amd_gpio_irq_set_wake(struct irq_data *d, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:441
Inline: False
```
**Symbols:**

```
ffffffff8167dbe0-ffffffff8167dc7c: amd_gpio_irq_set_wake (STB_LOCAL)
ffffffff81ce0b33-ffffffff81ce0b5f: amd_gpio_irq_set_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int amd_gpio_irq_set_wake(struct irq_data *d, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (0)
Location: drivers/pinctrl/pinctrl-amd.c:445
Inline: False
```
**Symbols:**

```
ffffffff81799660-ffffffff81799714: amd_gpio_irq_set_wake (STB_LOCAL)
ffffffff81ea724e-ffffffff81ea727a: amd_gpio_irq_set_wake.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_gpio_irq_set_wake(struct irq_data *d, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818af7a0)
Location: drivers/pinctrl/pinctrl-amd.c:442
Inline: False
```
**Symbols:**

```
ffffffff818af7a0-ffffffff818af870: amd_gpio_irq_set_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_gpio_irq_set_wake(struct irq_data *d, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff818f25c0)
Location: drivers/pinctrl/pinctrl-amd.c:434
Inline: False
```
**Symbols:**

```
ffffffff818f25c0-ffffffff818f2690: amd_gpio_irq_set_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_gpio_irq_set_wake(struct irq_data *d, unsigned int on);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-amd.c (ffffffff81939df0)
Location: drivers/pinctrl/pinctrl-amd.c:434
Inline: False
```
**Symbols:**

```
ffffffff81939df0-ffffffff81939ec0: amd_gpio_irq_set_wake (STB_LOCAL)
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
