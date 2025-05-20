# Function: <code>unmask_8259A_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81033380)
Location: arch/x86/kernel/i8259.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81033380-ffffffff810333df: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81032550)
Location: arch/x86/kernel/i8259.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81032550-ffffffff810325af: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810321c0)
Location: arch/x86/kernel/i8259.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff810321c0-ffffffff8103221f: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81030400)
Location: arch/x86/kernel/i8259.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81030400-ffffffff8103045a: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810327a0)
Location: arch/x86/kernel/i8259.c:76
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff810327a0-ffffffff810327fa: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81033ad0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81033ad0-ffffffff81033b2a: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81034e20)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81034e20-ffffffff81034e7a: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81036d80)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81036d80-ffffffff81036dda: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81037550)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81037550-ffffffff810375aa: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810398dd)
Location: arch/x86/kernel/i8259.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff810393d0-ffffffff81039420: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff8103a13d)
Location: arch/x86/kernel/i8259.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81039c30-ffffffff81039c80: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff8103bc0d)
Location: arch/x86/kernel/i8259.c:77
Inline: True
Inline callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff8103b700-ffffffff8103b750: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81041220-ffffffff81041279: unmask_8259A_irq (STB_LOCAL)
ffffffff81c98e98-ffffffff81c98eb0: unmask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81048e50-ffffffff81048eb7: unmask_8259A_irq (STB_LOCAL)
ffffffff81e48452-ffffffff81e4846a: unmask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81053da0-ffffffff81053e07: unmask_8259A_irq (STB_LOCAL)
ffffffff820522df-ffffffff820522f7: unmask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81054e10-ffffffff81054e77: unmask_8259A_irq (STB_LOCAL)
ffffffff820d07f9-ffffffff820d0811: unmask_8259A_irq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/i8259.c (0)
Location: arch/x86/kernel/i8259.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff8105c050-ffffffff8105c0b7: unmask_8259A_irq (STB_LOCAL)
ffffffff821ab30e-ffffffff821ab326: unmask_8259A_irq.cold (STB_LOCAL)
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
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff810376b0)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff810376b0-ffffffff8103770a: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81027090)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81027090-ffffffff810270ea: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81037510)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81037510-ffffffff8103756a: unmask_8259A_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unmask_8259A_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/i8259.c (ffffffff81038510)
Location: arch/x86/kernel/i8259.c:77
Inline: False
Direct callers:
  - arch/x86/kernel/i8259.c:enable_8259A_irq
```
**Symbols:**

```
ffffffff81038510-ffffffff8103856a: unmask_8259A_irq (STB_LOCAL)
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
