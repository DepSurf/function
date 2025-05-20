# Function: <code>handle_irq_event_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810da860)
Location: kernel/irq/handle.c:135
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810da860-ffffffff810daa27: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810dffc0)
Location: kernel/irq/handle.c:180
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810dffc0-ffffffff810e0034: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e6910)
Location: kernel/irq/handle.c:180
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810e6910-ffffffff810e6984: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e5f60)
Location: kernel/irq/handle.c:182
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810e5f60-ffffffff810e5fd4: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ee1e0)
Location: kernel/irq/handle.c:182
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810ee1e0-ffffffff810ee254: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810f6430)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810f6430-ffffffff810f64a6: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81101ba0)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff81101ba0-ffffffff81101c16: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110a3b0)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8110a3b0-ffffffff8110a42a: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81116780)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff81116780-ffffffff811167fa: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81122476)
Location: kernel/irq/handle.c:191
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff811223b0-ffffffff8112242a: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e446)
Location: kernel/irq/handle.c:191
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8111e380-ffffffff8111e3fa: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e756)
Location: kernel/irq/handle.c:191
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8111e690-ffffffff8111e70a: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8113ebf6)
Location: kernel/irq/handle.c:191
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8113eb30-ffffffff8113eba9: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81162211)
Location: kernel/irq/handle.c:189
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff81162190-ffffffff811621e0: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81195cb1)
Location: kernel/irq/handle.c:189
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff81195c20-ffffffff81195c70: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811a7671)
Location: kernel/irq/handle.c:189
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff811a75e0-ffffffff811a7630: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811b71d1)
Location: kernel/irq/handle.c:189
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_irq_event
Direct callers:
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff811b7140-ffffffff811b7190: handle_irq_event_percpu (STB_GLOBAL)
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
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff800010178918)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffff800010178918-ffff8000101789ac: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c03ca098)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
c03ca098-c03ca134: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c0000000001d2820)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
c0000000001d2820-c0000000001d28dc: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe0001132c6)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffe0001132c6-ffffffe000113334: handle_irq_event_percpu (STB_GLOBAL)
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
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110ed60)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8110ed60-ffffffff8110edda: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ffaa0)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff810ffaa0-ffffffff810ffb1a: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110cc50)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff8110cc50-ffffffff8110ccca: handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811181b0)
Location: kernel/irq/handle.c:184
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_percpu_irq
```
**Symbols:**

```
ffffffff811181b0-ffffffff8111822a: handle_irq_event_percpu (STB_GLOBAL)
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
