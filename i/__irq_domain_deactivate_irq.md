# Function: <code>__irq_domain_deactivate_irq</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec360)
Location: kernel/irq/irqdomain.c:1386
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_deactivate_irq
```
**Symbols:**

```
ffffffff810ec360-ffffffff810ec3a2: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ebcd0)
Location: kernel/irq/irqdomain.c:1526
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_deactivate_irq
```
**Symbols:**

```
ffffffff810ebcd0-ffffffff810ebd16: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4810)
Location: kernel/irq/irqdomain.c:1684
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff810f4810-ffffffff810f4859: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fcc10)
Location: kernel/irq/irqdomain.c:1568
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff810fcc10-ffffffff810fcc55: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811084c0)
Location: kernel/irq/irqdomain.c:1568
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff811084c0-ffffffff81108505: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81111ac0)
Location: kernel/irq/irqdomain.c:1605
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81111ac0-ffffffff81111b02: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111dd30)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff8111dd30-ffffffff8111dd72: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a010)
Location: kernel/irq/irqdomain.c:1610
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff8112a010-ffffffff8112a055: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811259f0)
Location: kernel/irq/irqdomain.c:1732
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff811259f0-ffffffff81125a35: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81125ce0)
Location: kernel/irq/irqdomain.c:1695
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81125ce0-ffffffff81125d25: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146480)
Location: kernel/irq/irqdomain.c:1740
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81146480-ffffffff811464c5: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116a750)
Location: kernel/irq/irqdomain.c:1744
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff8116a750-ffffffff8116a7a9: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119f310)
Location: kernel/irq/irqdomain.c:1812
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff8119f310-ffffffff8119f369: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b11f0)
Location: kernel/irq/irqdomain.c:1793
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff811b11f0-ffffffff811b1249: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c0fa0)
Location: kernel/irq/irqdomain.c:1793
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff811c0fa0-ffffffff811c0ff9: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183380)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffff800010183380-ffff8000101833d0: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2668)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
c03d2668-c03d26bc: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011a736)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffe00011a736-ffffffe00011a772: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116310)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81116310-ffffffff81116352: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107000)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81107000-ffffffff81107042: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114200)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff81114200-ffffffff81114242: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data *irq_data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111f830)
Location: kernel/irq/irqdomain.c:1608
Inline: True
Direct callers:
  - kernel/irq/irqdomain.c:irq_domain_deactivate_irq
  - kernel/irq/irqdomain.c:__irq_domain_activate_irq
```
**Symbols:**

```
ffffffff8111f830-ffffffff8111f872: __irq_domain_deactivate_irq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
