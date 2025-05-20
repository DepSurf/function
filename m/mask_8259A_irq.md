# Function: <code>mask_8259A_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81033300)
Location: arch/x86/kernel/i8259.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81033300-ffffffff8103335f: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810324d0)
Location: arch/x86/kernel/i8259.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff810324d0-ffffffff8103252f: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81032140)
Location: arch/x86/kernel/i8259.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81032140-ffffffff8103219f: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81030380)
Location: arch/x86/kernel/i8259.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81030380-ffffffff810303da: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81032720)
Location: arch/x86/kernel/i8259.c:57
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81032720-ffffffff8103277a: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81033a50)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81033a50-ffffffff81033aaa: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81034da0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81034da0-ffffffff81034dfa: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81036d00)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81036d00-ffffffff81036d5a: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810374d0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff810374d0-ffffffff8103752a: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff8103987d)
Location: arch/x86/kernel/i8259.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81039380-ffffffff810393d0: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff8103a0dd)
Location: arch/x86/kernel/i8259.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81039be0-ffffffff81039c30: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff8103bbad)
Location: arch/x86/kernel/i8259.c:58
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff8103b6b0-ffffffff8103b700: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff810412a0-ffffffff810412f9: mask_8259A_irq (STB_LOCAL)
ffffffff81c98eb0-ffffffff81c98ec8: mask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81048ee0-ffffffff81048f47: mask_8259A_irq (STB_LOCAL)
ffffffff81e4846a-ffffffff81e48482: mask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81053e50-ffffffff81053eb7: mask_8259A_irq (STB_LOCAL)
ffffffff820522f7-ffffffff8205230f: mask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81054ec0-ffffffff81054f27: mask_8259A_irq (STB_LOCAL)
ffffffff820d0811-ffffffff820d0829: mask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff8105c100-ffffffff8105c167: mask_8259A_irq (STB_LOCAL)
ffffffff821ab326-ffffffff821ab33e: mask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81037630)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81037630-ffffffff8103768a: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81027010)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81027010-ffffffff8102706a: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81037490)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81037490-ffffffff810374ea: mask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81038490)
Location: arch/x86/kernel/i8259.c:58
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:disable_8259A_irq
```
**Symbols:**

```
ffffffff81038490-ffffffff810384ea: mask_8259A_irq (STB_LOCAL)
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
