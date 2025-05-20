# Function: <code>unmask_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ddd38)
Location: kernel/irq/chip.c:301
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff810de370-ffffffff810de39e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e3986)
Location: kernel/irq/chip.c:301
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff810e3cc0-ffffffff810e3cee: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff810ea1dc)
Location: kernel/irq/chip.c:300
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff810ea7f0-ffffffff810ea81e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810e97f0)
Location: kernel/irq/chip.c:402
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff810e9390-ffffffff810e93bf: unmask_irq.part.33 (STB_LOCAL)
ffffffff810e9ed0-ffffffff810e9eef: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f1c8c)
Location: kernel/irq/chip.c:425
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff810f1800-ffffffff810f1832: unmask_irq.part.34 (STB_LOCAL)
ffffffff810f2420-ffffffff810f243f: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff810f9e73)
Location: kernel/irq/chip.c:423
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff810f9af0-ffffffff810f9b21: unmask_irq.part.35 (STB_LOCAL)
ffffffff810fa870-ffffffff810fa88e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff81105633)
Location: kernel/irq/chip.c:423
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff811052b0-ffffffff811052e1: unmask_irq.part.37 (STB_LOCAL)
ffffffff81106030-ffffffff8110604e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110eaed)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff8110e600-ffffffff8110e631: unmask_irq.part.0 (STB_LOCAL)
ffffffff8110f4d0-ffffffff8110f4ee: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111adad)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff8111a8c0-ffffffff8111a8f1: unmask_irq.part.0 (STB_LOCAL)
ffffffff8111b790-ffffffff8111b7ae: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8112705e)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff81127a70-ffffffff81127ab1: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122c5e)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff81123670-ffffffff811236b1: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81122d9e)
Location: kernel/irq/chip.c:432
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff811239d0-ffffffff81123a11: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8114336e)
Location: kernel/irq/chip.c:432
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff81143fa0-ffffffff81143fe1: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff81167291)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff81167a70-ffffffff81167ac1: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff8119b5e1)
Location: kernel/irq/chip.c:431
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff8119bea0-ffffffff8119bef1: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811ad421)
Location: kernel/irq/chip.c:432
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff811add00-ffffffff811add51: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/chip.c (ffffffff811bd021)
Location: kernel/irq/chip.c:432
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:unmask_threaded_irq
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
  - kernel/irq/chip.c:irq_enable
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
```
**Symbols:**

```
ffffffff811bd900-ffffffff811bd951: unmask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffff80001017e600)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffff80001017e030-ffff80001017e078: unmask_irq.part.0 (STB_LOCAL)
ffff80001017f898-ffff80001017f8d0: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c03cf104)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
c03ce8f8-c03ce93c: unmask_irq.part.0 (STB_LOCAL)
c03cfa0c-c03cfa38: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (c0000000001d97ac)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
c0000000001d8c20-c0000000001d8c8c: unmask_irq.part.0 (STB_LOCAL)
c0000000001da390-c0000000001da3b4: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffe000117246)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffe000116b08-ffffffe000116b40: unmask_irq.part.0 (STB_LOCAL)
ffffffe000117c9e-ffffffe000117cd4: unmask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111338d)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff81112ea0-ffffffff81112ed1: unmask_irq.part.0 (STB_LOCAL)
ffffffff81113d70-ffffffff81113d8e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8110409d)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff81103bc0-ffffffff81103bf1: unmask_irq.part.0 (STB_LOCAL)
ffffffff81104a80-ffffffff81104a9e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111127d)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff81110d90-ffffffff81110dc1: unmask_irq.part.0 (STB_LOCAL)
ffffffff81111c60-ffffffff81111c7e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unmask_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/chip.c (ffffffff8111ca4a)
Location: kernel/irq/chip.c:429
Inline: True
Inline callers:
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
Direct callers:
  - kernel/irq/manage.c:__irq_set_trigger
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:unmask_threaded_irq
```
**Symbols:**

```
ffffffff8111c560-ffffffff8111c591: unmask_irq.part.0 (STB_LOCAL)
ffffffff8111d220-ffffffff8111d23e: unmask_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
