# Function: <code>print_irq_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810da5c6)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810debb0)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810dfb86)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810e4530)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e6516)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810eadd0)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e5b66)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810ea490)
Location: kernel/irq/debug.h:12
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810eddb6)
Location: kernel/irq/debug.h:13
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810f2996)
Location: kernel/irq/debug.h:13
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810f622a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff810fadf0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110199a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811065b0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110a1aa)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff8110fb70)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8111657a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff8111bdf0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff81128120)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81122170-ffffffff8112219d: print_irq_desc (STB_LOCAL)
ffffffff811224e1-ffffffff8112266e: print_irq_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff81123c00)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8111e150-ffffffff8111e17d: print_irq_desc (STB_LOCAL)
ffffffff81be1591-ffffffff81be171e: print_irq_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff81123f50)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8111e460-ffffffff8111e48d: print_irq_desc (STB_LOCAL)
ffffffff81bd364c-ffffffff81bd37d9: print_irq_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff81144530)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8113e900-ffffffff8113e92d: print_irq_desc (STB_LOCAL)
ffffffff81cad4ba-ffffffff81cad647: print_irq_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff81168400)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81161f00-ffffffff81161f40: print_irq_desc (STB_LOCAL)
ffffffff81e5d9b7-ffffffff81e5db5f: print_irq_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81195760)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff8119c910)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81195760-ffffffff8119597d: print_irq_desc (STB_LOCAL)
ffffffff8119c910-ffffffff8119cb2d: print_irq_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811a7130)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811ae790)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff811a7130-ffffffff811a734d: print_irq_desc (STB_LOCAL)
ffffffff811ae790-ffffffff811ae9ad: print_irq_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
void print_irq_desc(unsigned int irq, struct irq_desc *desc);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff811b6c90)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811be390)
Location: kernel/irq/debug.h:11
Inline: False
Direct callers:
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff811b6c90-ffffffff811b6ead: print_irq_desc (STB_LOCAL)
ffffffff811be390-ffffffff811be5ad: print_irq_desc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff8000101783fc)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffff8000101803c0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c03c9b8c)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (c03d0254)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c0000000001d223c)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (c0000000001dadf4)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe000112e4a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffe000118420)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110eb5a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811143d0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ff8aa)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811050e0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff8110ca4a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff811122c0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff81117f7a)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffff8111d8e0)
Location: kernel/irq/debug.h:11
Inline: True
Inline callers:
  - kernel/irq/dummychip.c:ack_bad
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
