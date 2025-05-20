# Function: <code>xen_call_function_interrupt</code>

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
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:711
Inline: False
```
**Symbols:**

```
ffffffff8102a8a0-ffffffff8102a8c6: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (0)
Location: arch/x86/xen/smp.c:705
Inline: False
```
**Symbols:**

```
ffffffff8102aa40-ffffffff8102aa66: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028a50)
Location: arch/x86/xen/smp.c:263
Inline: True
```
**Symbols:**

```
ffffffff81028a50-ffffffff81028a76: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028c60)
Location: arch/x86/xen/smp.c:266
Inline: True
```
**Symbols:**

```
ffffffff81028c60-ffffffff81028c86: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810296b0)
Location: arch/x86/xen/smp.c:266
Inline: True
```
**Symbols:**

```
ffffffff810296b0-ffffffff810296d6: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029c90)
Location: arch/x86/xen/smp.c:266
Inline: True
```
**Symbols:**

```
ffffffff81029c90-ffffffff81029cb6: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102ba50)
Location: arch/x86/xen/smp.c:266
Inline: False
```
**Symbols:**

```
ffffffff8102ba50-ffffffff8102ba76: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c350)
Location: arch/x86/xen/smp.c:266
Inline: False
```
**Symbols:**

```
ffffffff8102c350-ffffffff8102c376: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102e310)
Location: arch/x86/xen/smp.c:266
Inline: True
```
**Symbols:**

```
ffffffff8102e310-ffffffff8102e336: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102f170)
Location: arch/x86/xen/smp.c:269
Inline: True
```
**Symbols:**

```
ffffffff8102f170-ffffffff8102f196: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102fc80)
Location: arch/x86/xen/smp.c:269
Inline: True
```
**Symbols:**

```
ffffffff8102fc80-ffffffff8102fca6: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81034670)
Location: arch/x86/xen/smp.c:269
Inline: True
```
**Symbols:**

```
ffffffff81034670-ffffffff81034696: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8103a3e0)
Location: arch/x86/xen/smp.c:245
Inline: True
```
**Symbols:**

```
ffffffff8103a3e0-ffffffff8103a400: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810429c0)
Location: arch/x86/xen/smp.c:245
Inline: True
```
**Symbols:**

```
ffffffff810429c0-ffffffff810429e0: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042c10)
Location: arch/x86/xen/smp.c:245
Inline: True
```
**Symbols:**

```
ffffffff81042c10-ffffffff81042c30: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810490e0)
Location: arch/x86/xen/smp.c:257
Inline: True
```
**Symbols:**

```
ffffffff810490e0-ffffffff81049100: xen_call_function_interrupt (STB_LOCAL)
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
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c4b0)
Location: arch/x86/xen/smp.c:266
Inline: False
```
**Symbols:**

```
ffffffff8102c4b0-ffffffff8102c4d6: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c310)
Location: arch/x86/xen/smp.c:266
Inline: False
```
**Symbols:**

```
ffffffff8102c310-ffffffff8102c336: xen_call_function_interrupt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
irqreturn_t xen_call_function_interrupt(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102d100)
Location: arch/x86/xen/smp.c:266
Inline: False
```
**Symbols:**

```
ffffffff8102d100-ffffffff8102d126: xen_call_function_interrupt (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
