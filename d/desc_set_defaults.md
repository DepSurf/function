# Function: <code>desc_set_defaults</code>

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
In kernel/irq/irqdesc.c (ffffffff810da12f)
Location: kernel/irq/irqdesc.c:71
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810df626)
Location: kernel/irq/irqdesc.c:93
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810e5d9a)
Location: kernel/irq/irqdesc.c:94
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810e53f8)
Location: kernel/irq/irqdesc.c:105
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810ed654)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810f5a24)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff811011b4)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff811099b4)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff81115d84)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void desc_set_defaults(unsigned int irq, struct irq_desc *desc, int node, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81121590)
Location: kernel/irq/irqdesc.c:103
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
**Symbols:**

```
ffffffff81121590-ffffffff81121698: desc_set_defaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void desc_set_defaults(unsigned int irq, struct irq_desc *desc, int node, const struct cpumask *affinity, struct module *owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111d6c0)
Location: kernel/irq/irqdesc.c:103
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
**Symbols:**

```
ffffffff8111d6c0-ffffffff8111d7c8: desc_set_defaults (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8111db74)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff8113df84)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff8116159e)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff81194c1e)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff811a639e)
Location: kernel/irq/irqdesc.c:102
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff811b5ebd)
Location: kernel/irq/irqdesc.c:102
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffff800010177510)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (c03c93e4)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (c0000000001d10c4)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffe000112514)
Location: kernel/irq/irqdesc.c:103
Inline: True
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
In kernel/irq/irqdesc.c (ffffffff8110e364)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff810ff0c4)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff8110c254)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
In kernel/irq/irqdesc.c (ffffffff81117984)
Location: kernel/irq/irqdesc.c:103
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:alloc_desc
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
</ul>
