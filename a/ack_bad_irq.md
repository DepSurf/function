# Function: <code>ack_bad_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff81030070)
Location: arch/x86/kernel/irq.c:40
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81030070-ffffffff810300b3: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102f0e0)
Location: arch/x86/kernel/irq.c:40
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8102f0e0-ffffffff8102f123: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102f0a0)
Location: arch/x86/kernel/irq.c:39
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8102f0a0-ffffffff8102f0e3: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102d510)
Location: arch/x86/kernel/irq.c:39
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8102d510-ffffffff8102d553: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8102f690)
Location: arch/x86/kernel/irq.c:36
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8102f690-ffffffff8102f6d5: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:37
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff810314fe-ffffffff81031511: ack_bad_irq.cold.11 (STB_LOCAL)
ffffffff810307d0-ffffffff81030809: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:37
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8103279e-ffffffff810327b1: ack_bad_irq.cold.12 (STB_LOCAL)
ffffffff81031a60-ffffffff81031a99: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff810344b0-ffffffff810344c4: ack_bad_irq.cold (STB_LOCAL)
ffffffff810337c0-ffffffff810337fc: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81034d70-ffffffff81034d84: ack_bad_irq.cold (STB_LOCAL)
ffffffff81034080-ffffffff810340bc: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:37
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81036b70-ffffffff81036b84: ack_bad_irq.cold (STB_LOCAL)
ffffffff81035fa0-ffffffff81035fde: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:37
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81bd337d-ffffffff81bd3391: ack_bad_irq.cold (STB_LOCAL)
ffffffff81037190-ffffffff810371ce: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81bc57ef-ffffffff81bc5803: ack_bad_irq.cold (STB_LOCAL)
ffffffff81038d30-ffffffff81038d6e: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81c984cc-ffffffff81c984e0: ack_bad_irq.cold (STB_LOCAL)
ffffffff8103e0c0-ffffffff8103e0fe: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81e479d1-ffffffff81e479e4: ack_bad_irq.cold (STB_LOCAL)
ffffffff81045690-ffffffff810456d6: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff8104f600)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff8104f600-ffffffff8104f652: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810502b0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff810502b0-ffffffff81050302: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/irq.c (ffffffff810574e0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff810574e0-ffffffff81057534: ack_bad_irq (STB_GLOBAL)
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
In kernel/irq/irqdesc.c (ffff800010177c78)
Location: arch/arm64/include/asm/hardirq.h:60
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
```
In kernel/irq/handle.c (ffff800010178450)
Location: arch/arm64/include/asm/hardirq.h:60
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffff8000101803c8)
Location: arch/arm64/include/asm/hardirq.h:60
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
In kernel/irq/irqdesc.c (c03c9634)
Location: arch/arm/include/asm/hw_irq.h:8
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:__handle_domain_irq
```
```
In kernel/irq/handle.c (c03c9bec)
Location: arch/arm/include/asm/hw_irq.h:8
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (c03d0260)
Location: arch/arm/include/asm/hw_irq.h:8
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
In kernel/irq/handle.c (c0000000001d2290)
Location: arch/powerpc/include/asm/hardirq.h:31
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (c0000000001dae04)
Location: arch/powerpc/include/asm/hardirq.h:31
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
In kernel/irq/handle.c (ffffffe000112e74)
Location: include/asm-generic/hardirq.h:16
Inline: True
Inline callers:
  - kernel/irq/handle.c:handle_bad_irq
```
```
In kernel/irq/dummychip.c (ffffffe000118442)
Location: include/asm-generic/hardirq.h:16
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81034ed0-ffffffff81034ee4: ack_bad_irq.cold (STB_LOCAL)
ffffffff810341e0-ffffffff8103421c: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81024810-ffffffff81024824: ack_bad_irq.cold (STB_LOCAL)
ffffffff81023b20-ffffffff81023b5c: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81034d30-ffffffff81034d44: ack_bad_irq.cold (STB_LOCAL)
ffffffff81034040-ffffffff8103407c: ack_bad_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ack_bad_irq(unsigned int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/irq.c (0)
Location: arch/x86/kernel/irq.c:38
Inline: False
Direct callers:
  - kernel/irq/handle.c:handle_bad_irq
  - kernel/irq/dummychip.c:ack_bad
```
**Symbols:**

```
ffffffff81035c7a-ffffffff81035c8e: ack_bad_irq.cold (STB_LOCAL)
ffffffff81034fa0-ffffffff81034fdc: ack_bad_irq (STB_GLOBAL)
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
