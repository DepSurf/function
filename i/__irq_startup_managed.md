# Function: <code>__irq_startup_managed</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e9a96)
Location: kernel/irq/chip.c:196
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff810f1f76)
Location: kernel/irq/chip.c:196
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff810fa3ae)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff81105b6e)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff8110f02c)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff8111b2ec)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __irq_startup_managed(struct irq_desc *desc, struct cpumask *aff, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811267a0)
Location: kernel/irq/chip.c:194
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811267a0-ffffffff81126818: __irq_startup_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __irq_startup_managed(struct irq_desc *desc, struct cpumask *aff, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811223d0)
Location: kernel/irq/chip.c:194
Inline: False
Direct callers:
  - kernel/irq/chip.c:irq_startup
```
**Symbols:**

```
ffffffff811223d0-ffffffff81122448: __irq_startup_managed (STB_LOCAL)
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
In kernel/irq/chip.c (ffffffff811233b8)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff81143988)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff8116776b)
Location: kernel/irq/chip.c:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff8119bb3b)
Location: kernel/irq/chip.c:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff811ad98b)
Location: kernel/irq/chip.c:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff811bd58b)
Location: kernel/irq/chip.c:191
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffff80001017f2a0)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (c03cf490)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (c0000000001d9c30)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffe000117826)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff811138cc)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff811045dc)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff811117bc)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
In kernel/irq/chip.c (ffffffff8111cd7c)
Location: kernel/irq/chip.c:194
Inline: True
Inline callers:
  - kernel/irq/chip.c:irq_startup
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
