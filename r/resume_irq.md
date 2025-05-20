# Function: <code>resume_irq</code>

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
In kernel/irq/pm.c (ffffffff810e2867)
Location: kernel/irq/pm.c:139
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff810e82f7)
Location: kernel/irq/pm.c:139
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff810eed31)
Location: kernel/irq/pm.c:139
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff810eeb95)
Location: kernel/irq/pm.c:139
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff810f763e)
Location: kernel/irq/pm.c:139
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff810ff9a5)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff8110b185)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff81114858)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff811209b8)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff8112cf78)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void resume_irq(struct irq_desc *desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/pm.c (ffffffff81128800)
Location: kernel/irq/pm.c:152
Inline: False
Direct callers:
  - kernel/irq/pm.c:resume_irqs
```
**Symbols:**

```
ffffffff81128800-ffffffff8112887a: resume_irq (STB_LOCAL)
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
In kernel/irq/pm.c (ffffffff81128b00)
Location: kernel/irq/pm.c:152
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff811490e0)
Location: kernel/irq/pm.c:152
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff8116dc6f)
Location: kernel/irq/pm.c:152
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff811a2eaf)
Location: kernel/irq/pm.c:151
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff811b4daf)
Location: kernel/irq/pm.c:151
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff811c4c2f)
Location: kernel/irq/pm.c:151
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffff800010186770)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (c03d55ac)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (c0000000001e1134)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/irq/pm.c (ffffffff81118f98)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff8110a008)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff81116e88)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
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
In kernel/irq/pm.c (ffffffff81122518)
Location: kernel/irq/pm.c:138
Inline: True
Inline callers:
  - kernel/irq/pm.c:resume_irqs
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
