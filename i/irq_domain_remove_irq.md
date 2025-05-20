# Function: <code>irq_domain_remove_irq</code>

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
In kernel/irq/irqdomain.c (ffffffff810e16ea)
Location: kernel/irq/irqdomain.c:918
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff810e6e64)
Location: kernel/irq/irqdomain.c:966
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff810ed854)
Location: kernel/irq/irqdomain.c:992
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff810ed221)
Location: kernel/irq/irqdomain.c:1160
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff810f5c52)
Location: kernel/irq/irqdomain.c:1166
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff810fe003)
Location: kernel/irq/irqdomain.c:1050
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff811097d3)
Location: kernel/irq/irqdomain.c:1050
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff81112dc2)
Location: kernel/irq/irqdomain.c:1087
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111f052)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_remove_irq(int virq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a0f0)
Location: kernel/irq/irqdomain.c:1103
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
**Symbols:**

```
ffffffff8112a0f0-ffffffff8112a19c: irq_domain_remove_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_remove_irq(int virq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125ad0)
Location: kernel/irq/irqdomain.c:1127
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
**Symbols:**

```
ffffffff81125ad0-ffffffff81125b7c: irq_domain_remove_irq (STB_LOCAL)
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
In kernel/irq/irqdomain.c (ffffffff811271cb)
Location: kernel/irq/irqdomain.c:1094
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff8114772b)
Location: kernel/irq/irqdomain.c:1133
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff8116bb6b)
Location: kernel/irq/irqdomain.c:1135
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff811a0d5b)
Location: kernel/irq/irqdomain.c:1195
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff811b2be6)
Location: kernel/irq/irqdomain.c:1174
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff811c2a06)
Location: kernel/irq/irqdomain.c:1174
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffff800010184b78)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (c03d3c20)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011ba2e)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff81117632)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff81108322)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff81115522)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
In kernel/irq/irqdomain.c (ffffffff81120b52)
Location: kernel/irq/irqdomain.c:1089
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_irqs
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
