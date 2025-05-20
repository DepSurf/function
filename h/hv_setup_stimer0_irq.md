# Function: <code>hv_setup_stimer0_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81058110)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
```
**Symbols:**

```
ffffffff81058110-ffffffff81058130: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105ddb0)
Location: arch/x86/kernel/cpu/mshyperv.c:93
Inline: False
```
**Symbols:**

```
ffffffff8105ddb0-ffffffff8105ddd0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810611b0)
Location: arch/x86/kernel/cpu/mshyperv.c:91
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810611b0-ffffffff810611d0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061a20)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81061a20-ffffffff81061a40: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067900)
Location: arch/x86/kernel/cpu/mshyperv.c:88
Inline: False
```
**Symbols:**

```
ffffffff81067900-ffffffff81067920: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810696b0)
Location: arch/x86/kernel/cpu/mshyperv.c:93
Inline: False
```
**Symbols:**

```
ffffffff810696b0-ffffffff810696d0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7b55)
Location: drivers/clocksource/hyperv_timer.c:199
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a5510b)
Location: drivers/clocksource/hyperv_timer.c:199
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc483c)
Location: drivers/clocksource/hyperv_timer.c:199
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a08c)
Location: drivers/clocksource/hyperv_timer.c:200
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd544c)
Location: drivers/clocksource/hyperv_timer.c:201
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d59c)
Location: drivers/clocksource/hyperv_timer.c:201
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
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
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810615a0)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810615a0-ffffffff810615c0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051a00)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81051a00-ffffffff81051a20: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810619d0)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff810619d0-ffffffff810619f0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hv_setup_stimer0_irq(int *irq, int *vector, void (*handler)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81062f80)
Location: arch/x86/kernel/cpu/mshyperv.c:92
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_alloc
```
**Symbols:**

```
ffffffff81062f80-ffffffff81062fa0: hv_setup_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
