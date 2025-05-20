# Function: <code>irq_domain_insert_irq</code>

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
In kernel/irq/irqdomain.c (ffffffff810e128c)
Location: kernel/irq/irqdomain.c:894
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810e6c3c)
Location: kernel/irq/irqdomain.c:942
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810ed62c)
Location: kernel/irq/irqdomain.c:968
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810ecfe8)
Location: kernel/irq/irqdomain.c:1135
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810f5a1f)
Location: kernel/irq/irqdomain.c:1148
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff810fdde7)
Location: kernel/irq/irqdomain.c:1032
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811095b7)
Location: kernel/irq/irqdomain.c:1032
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff81112b7b)
Location: kernel/irq/irqdomain.c:1069
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8111ee0b)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_domain_insert_irq(int virq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a1a0)
Location: kernel/irq/irqdomain.c:1085
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
**Symbols:**

```
ffffffff8112a1a0-ffffffff8112a25e: irq_domain_insert_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_domain_insert_irq(int virq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125b80)
Location: kernel/irq/irqdomain.c:1109
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
```
**Symbols:**

```
ffffffff81125b80-ffffffff81125c3e: irq_domain_insert_irq (STB_LOCAL)
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
In kernel/irq/irqdomain.c (ffffffff8112708f)
Location: kernel/irq/irqdomain.c:1076
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811475e8)
Location: kernel/irq/irqdomain.c:1115
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8116b6f3)
Location: kernel/irq/irqdomain.c:1117
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811a0505)
Location: kernel/irq/irqdomain.c:1177
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
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
In kernel/irq/irqdomain.c (ffffffff811b23d0)
Location: kernel/irq/irqdomain.c:1160
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
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
In kernel/irq/irqdomain.c (ffffffff811c21b1)
Location: kernel/irq/irqdomain.c:1160
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
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
In kernel/irq/irqdomain.c (ffff8000101848d0)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (c03d3988)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffe00011b818)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811173eb)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811080db)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff811152db)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
In kernel/irq/irqdomain.c (ffffffff8112090b)
Location: kernel/irq/irqdomain.c:1071
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
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
