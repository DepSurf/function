# Function: <code>__handle_irq_event_percpu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810dfe20)
Location: kernel/irq/handle.c:135
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810dfe20-ffffffff810dffb3: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e6780)
Location: kernel/irq/handle.c:135
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810e6780-ffffffff810e6910: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810e5dd0)
Location: kernel/irq/handle.c:135
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810e5dd0-ffffffff810e5f5b: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffff810ee040)
Location: kernel/irq/handle.c:135
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810ee040-ffffffff810ee1d9: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810f6697-ffffffff810f66ae: __handle_irq_event_percpu.cold.9 (STB_LOCAL)
ffffffff810f62a0-ffffffff810f6427: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81101e07-ffffffff81101e1e: __handle_irq_event_percpu.cold.10 (STB_LOCAL)
ffffffff81101a10-ffffffff81101b97: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff8110a617-ffffffff8110a62f: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8110a230-ffffffff8110a3a9: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff811169e7-ffffffff811169ff: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff81116600-ffffffff81116779: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff8112266e-ffffffff81122686: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff81122230-ffffffff811223a3: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81be171e-ffffffff81be1736: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8111e210-ffffffff8111e372: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81bd37d9-ffffffff81bd37f1: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8111e520-ffffffff8111e682: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81cad647-ffffffff81cad67a: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8113e9c0-ffffffff8113eb29: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:139
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81e5db5f-ffffffff81e5db9a: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff81161fe0-ffffffff81162182: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:139
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff82059933-ffffffff82059956: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff81195a50-ffffffff81195c05: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:139
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff820d7f88-ffffffff820d7fa3: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff811a7420-ffffffff811a75d0: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:139
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff821b3209-ffffffff821b3224: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff811b6f80-ffffffff811b7130: __handle_irq_event_percpu (STB_GLOBAL)
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffff8000101786c8)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffff8000101786c8-ffff800010178914: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c03c9e38)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
c03c9e38-c03ca098: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (c0000000001d2550)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
c0000000001d2550-c0000000001d281c: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/handle.c (ffffffe0001130ec)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffe0001130ec-ffffffe0001132c6: __handle_irq_event_percpu (STB_GLOBAL)
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
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff8110efc7-ffffffff8110efdf: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8110ebe0-ffffffff8110ed59: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff810ffd07-ffffffff810ffd1f: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff810ff930-ffffffff810ffa9e: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff8110ceb7-ffffffff8110cecf: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff8110cad0-ffffffff8110cc49: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t __handle_irq_event_percpu(struct irq_desc *desc, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/handle.c (0)
Location: kernel/irq/handle.c:137
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_untracked_irq
```
**Symbols:**

```
ffffffff81118415-ffffffff8111842d: __handle_irq_event_percpu.cold (STB_LOCAL)
ffffffff81118000-ffffffff811181ab: __handle_irq_event_percpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int *flags</code>
</li>
</ul>
</details>
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
