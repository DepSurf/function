# Function: <code>handle_bad_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810da5c0)
Location: kernel/irq/handle.c:29
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff810da5c0-ffffffff810da811: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810dfb80)
Location: kernel/irq/handle.c:29
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff810dfb80-ffffffff810dfdd1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e6510)
Location: kernel/irq/handle.c:29
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_handler
```
**Symbols:**

```
ffffffff810e6510-ffffffff810e6737: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e5b60)
Location: kernel/irq/handle.c:29
Inline: False
```
**Symbols:**

```
ffffffff810e5b60-ffffffff810e5d8a: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810eddb0)
Location: kernel/irq/handle.c:29
Inline: False
```
**Symbols:**

```
ffffffff810eddb0-ffffffff810edff5: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff810f650a-ffffffff810f6697: handle_bad_irq.cold.8 (STB_LOCAL)
ffffffff810f6210-ffffffff810f625a: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff81101c7a-ffffffff81101e07: handle_bad_irq.cold.9 (STB_LOCAL)
ffffffff81101980-ffffffff811019ca: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8110a48a-ffffffff8110a617: handle_bad_irq.cold (STB_LOCAL)
ffffffff8110a190-ffffffff8110a1e1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8111685a-ffffffff811169e7: handle_bad_irq.cold (STB_LOCAL)
ffffffff81116560-ffffffff811165b1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811221a0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff811221a0-ffffffff811221e1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e180)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8111e180-ffffffff8111e1c1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111e490)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8111e490-ffffffff8111e4d1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8113e930)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8113e930-ffffffff8113e971: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81161f40)
Location: kernel/irq/handle.c:33
Inline: False
```
**Symbols:**

```
ffffffff81161f40-ffffffff81161f8b: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81195990)
Location: kernel/irq/handle.c:33
Inline: False
```
**Symbols:**

```
ffffffff81195990-ffffffff811959db: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811a7360)
Location: kernel/irq/handle.c:33
Inline: False
```
**Symbols:**

```
ffffffff811a7360-ffffffff811a73ab: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811b6ec0)
Location: kernel/irq/handle.c:33
Inline: False
```
**Symbols:**

```
ffffffff811b6ec0-ffffffff811b6f0b: handle_bad_irq (STB_GLOBAL)
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
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff8000101783d8)
Location: kernel/irq/handle.c:31
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/irqchip/irq-brcmstb-l2.c:brcmstb_l2_intc_irq_handle
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
```
**Symbols:**

```
ffff8000101783d8-ffff8000101785f4: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c03c9b5c)
Location: kernel/irq/handle.c:31
Inline: False
Direct callers:
  - drivers/irqchip/exynos-combiner.c:combiner_handle_cascade_irq
  - drivers/irqchip/irq-gic.c:gic_handle_cascade_irq
  - drivers/irqchip/irq-partition-percpu.c:partition_handle_irq
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_handler
  - drivers/soc/dove/pmu.c:pmu_irq_handler
```
**Symbols:**

```
c03c9b5c-c03c9dc4: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c0000000001d2200)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
c0000000001d2200-c0000000001d24a8: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe000112e32)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffe000112e32-ffffffe000113084: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8110ee3a-ffffffff8110efc7: handle_bad_irq.cold (STB_LOCAL)
ffffffff8110eb40-ffffffff8110eb91: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff810ffb7a-ffffffff810ffd07: handle_bad_irq.cold (STB_LOCAL)
ffffffff810ff890-ffffffff810ff8e1: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff8110cd2a-ffffffff8110ceb7: handle_bad_irq.cold (STB_LOCAL)
ffffffff8110ca30-ffffffff8110ca81: handle_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void handle_bad_irq(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:31
Inline: False
```
**Symbols:**

```
ffffffff81118288-ffffffff81118415: handle_bad_irq.cold (STB_LOCAL)
ffffffff81117f60-ffffffff81117fb1: handle_bad_irq (STB_GLOBAL)
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
