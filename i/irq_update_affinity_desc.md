# Function: <code>irq_update_affinity_desc</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fb30)
Location: kernel/irq/manage.c:395
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8111fb30-ffffffff8111fb40: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111fde0)
Location: kernel/irq/manage.c:395
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff8111fde0-ffffffff8111fdf0: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81140360)
Location: kernel/irq/manage.c:388
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81140360-ffffffff81140370: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81163cb0)
Location: kernel/irq/manage.c:403
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff81163cb0-ffffffff81163cc4: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811979c0)
Location: kernel/irq/manage.c:395
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811979c0-ffffffff811979d4: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a9680)
Location: kernel/irq/manage.c:398
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811a9680-ffffffff811a9694: irq_update_affinity_desc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int irq_update_affinity_desc(unsigned int irq, struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b91e0)
Location: kernel/irq/manage.c:400
Inline: False
Direct callers:
  - drivers/base/platform.c:devm_platform_get_irqs_affinity
```
**Symbols:**

```
ffffffff811b91e0-ffffffff811b91f4: irq_update_affinity_desc (STB_GLOBAL)
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
