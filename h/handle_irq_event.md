# Function: <code>handle_irq_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810daa30)
Location: kernel/irq/handle.c:186
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_simple_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_edge_irq
```
**Symbols:**

```
ffffffff810daa30-ffffffff810daa8d: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e0040)
Location: kernel/irq/handle.c:194
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810e0040-ffffffff810e009d: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e6990)
Location: kernel/irq/handle.c:194
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810e6990-ffffffff810e69ea: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e5fe0)
Location: kernel/irq/handle.c:196
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810e5fe0-ffffffff810e603a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ee260)
Location: kernel/irq/handle.c:196
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810ee260-ffffffff810ee2ba: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810f64b0)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810f64b0-ffffffff810f650a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81101c20)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81101c20-ffffffff81101c7a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110a430)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8110a430-ffffffff8110a48a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81116800)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81116800-ffffffff8111685a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81122430)
Location: kernel/irq/handle.c:205
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81122430-ffffffff811224e1: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e400)
Location: kernel/irq/handle.c:205
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8111e400-ffffffff8111e4b1: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e710)
Location: kernel/irq/handle.c:205
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8111e710-ffffffff8111e7c1: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8113ebb0)
Location: kernel/irq/handle.c:205
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8113ebb0-ffffffff8113ec5e: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811621e0)
Location: kernel/irq/handle.c:202
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff811621e0-ffffffff8116225b: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81195c80)
Location: kernel/irq/handle.c:202
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81195c80-ffffffff81195cfb: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811a7640)
Location: kernel/irq/handle.c:202
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff811a7640-ffffffff811a76bb: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811b71a0)
Location: kernel/irq/handle.c:202
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff811b71a0-ffffffff811b721b: handle_irq_event (STB_GLOBAL)
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
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff8000101789b0)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_fasteoi_mask_irq
  - kernel/irq/chip.c:handle_fasteoi_ack_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffff8000101789b0-ffff800010178a6c: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c03ca134)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
c03ca134-c03ca1ac: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c0000000001d28e0)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
c0000000001d28e0-c0000000001d29a0: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe000113334)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffe000113334-ffffffe0001133dc: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110ede0)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8110ede0-ffffffff8110ee3a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ffb20)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff810ffb20-ffffffff810ffb7a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110ccd0)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff8110ccd0-ffffffff8110cd2a: handle_irq_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t handle_irq_event(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81118230)
Location: kernel/irq/handle.c:198
Inline: False
Direct callers:
  - kernel/irq/spurious.c:try_one_irq
  - kernel/irq/chip.c:handle_edge_irq
  - kernel/irq/chip.c:handle_fasteoi_irq
  - kernel/irq/chip.c:handle_level_irq
  - kernel/irq/chip.c:handle_simple_irq
```
**Symbols:**

```
ffffffff81118230-ffffffff81118288: handle_irq_event (STB_GLOBAL)
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
