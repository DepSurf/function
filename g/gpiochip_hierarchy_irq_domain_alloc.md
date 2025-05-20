# Function: <code>gpiochip_hierarchy_irq_domain_alloc</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffff8156a9e0-ffffffff8156aa62: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81570222-ffffffff81570376: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2174
Inline: False
```
**Symbols:**

```
ffffffff8160d120-ffffffff8160d310: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81614235-ffffffff81614281: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1060
Inline: False
```
**Symbols:**

```
ffffffff81633ef0-ffffffff816340d8: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81bf5a58-ffffffff81bf5aa4: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1049
Inline: False
```
**Symbols:**

```
ffffffff81617a40-ffffffff81617c28: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81be795c-ffffffff81be79a6: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1071
Inline: False
```
**Symbols:**

```
ffffffff81686cc0-ffffffff81686ea8: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81ce1428-ffffffff81ce1472: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1101
Inline: False
```
**Symbols:**

```
ffffffff817a3be0-ffffffff817a3dea: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81ea7bf6-ffffffff81ea7c3f: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bb4b0)
Location: drivers/gpio/gpiolib.c:1174
Inline: False
```
**Symbols:**

```
ffffffff818bb4b0-ffffffff818bb712: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fe5b0)
Location: drivers/gpio/gpiolib.c:1198
Inline: False
```
**Symbols:**

```
ffffffff818fe5b0-ffffffff818fe82a: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81945be0)
Location: drivers/gpio/gpiolib.c:1364
Inline: False
```
**Symbols:**

```
ffffffff81945be0-ffffffff81945e5a: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
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
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106be1d8)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffff8000106be1d8-ffff8000106be3a8: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085df3c)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
c085df3c-c085e138: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a50ee)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffe0004a50ee-ffffffe0004a5276: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
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
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffff815601a0-ffffffff81560222: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff815659e2-ffffffff81565b36: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81550ff0-ffffffff81551072: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81556832-ffffffff81556986: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffff8155ed10-ffffffff8155ed92: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff81564552-ffffffff815646a6: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_hierarchy_irq_domain_alloc(struct irq_domain *d, unsigned int irq, unsigned int nr_irqs, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81578ba0-ffffffff81578c22: gpiochip_hierarchy_irq_domain_alloc (STB_LOCAL)
ffffffff8157e472-ffffffff8157e5c6: gpiochip_hierarchy_irq_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
