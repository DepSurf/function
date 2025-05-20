# Function: <code>note_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810dd4f0)
Location: kernel/irq/spurious.c:273
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810dd4f0-ffffffff810dd778: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e2cb0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810e2cb0-ffffffff810e2f34: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e95b0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810e95b0-ffffffff810e981f: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810e8a70)
Location: kernel/irq/spurious.c:273
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810e8a70-ffffffff810e8d01: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff810f0e40)
Location: kernel/irq/spurious.c:274
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810f0e40-ffffffff810f10d1: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff810f94c3-ffffffff810f951f: note_interrupt.cold.9 (STB_LOCAL)
ffffffff810f91c0-ffffffff810f93ea: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81104c73-ffffffff81104ccf: note_interrupt.cold.9 (STB_LOCAL)
ffffffff81104970-ffffffff81104b9a: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8110de8f-ffffffff8110deef: note_interrupt.cold (STB_LOCAL)
ffffffff8110db80-ffffffff8110ddbd: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8111a14f-ffffffff8111a1af: note_interrupt.cold (STB_LOCAL)
ffffffff81119e40-ffffffff8111a07d: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81126070-ffffffff811260cd: note_interrupt.cold (STB_LOCAL)
ffffffff81125e10-ffffffff81125f9e: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81be1956-ffffffff81be19b3: note_interrupt.cold (STB_LOCAL)
ffffffff81121b20-ffffffff81121cae: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81bd3a11-ffffffff81bd3a71: note_interrupt.cold (STB_LOCAL)
ffffffff81121d60-ffffffff81122024: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81cad983-ffffffff81cad9e3: note_interrupt.cold (STB_LOCAL)
ffffffff81142310-ffffffff811425d4: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81e5de66-ffffffff81e5dec2: note_interrupt.cold (STB_LOCAL)
ffffffff81165e60-ffffffff81166128: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff81199f50)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff81199f50-ffffffff8119a26f: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff811abb80)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff811abb80-ffffffff811abe75: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffff811bb780)
Location: kernel/irq/spurious.c:272
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff811bb780-ffffffff811bba75: note_interrupt (STB_GLOBAL)
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
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffff80001017cf88)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffff80001017cf88-ffff80001017d2a0: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (c03cdab0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
c03cdab0-c03cdd70: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (c0000000001d7a60)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
c0000000001d7a60-c0000000001d7e64: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/spurious.c (ffffffe0001160d6)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffe0001160d6-ffffffe000116324: note_interrupt (STB_GLOBAL)
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
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8111272f-ffffffff8111278f: note_interrupt.cold (STB_LOCAL)
ffffffff81112420-ffffffff8111265d: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8110344f-ffffffff811034af: note_interrupt.cold (STB_LOCAL)
ffffffff81103140-ffffffff8110337d: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8111061f-ffffffff8111067f: note_interrupt.cold (STB_LOCAL)
ffffffff81110310-ffffffff8111054d: note_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void note_interrupt(struct irq_desc *desc, irqreturn_t action_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/spurious.c (0)
Location: kernel/irq/spurious.c:271
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_irq_event_percpu
  - kernel/irq/chip.c:handle_nested_irq
```
**Symbols:**

```
ffffffff8111bb9f-ffffffff8111bbff: note_interrupt.cold (STB_LOCAL)
ffffffff8111b890-ffffffff8111bacd: note_interrupt (STB_GLOBAL)
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
