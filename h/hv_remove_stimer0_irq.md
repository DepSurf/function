# Function: <code>hv_remove_stimer0_irq</code>

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
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81058130)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
```
**Symbols:**

```
ffffffff81058130-ffffffff81058146: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff8105ddd0)
Location: arch/x86/kernel/cpu/mshyperv.c:102
Inline: False
```
**Symbols:**

```
ffffffff8105ddd0-ffffffff8105dde6: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810611d0)
Location: arch/x86/kernel/cpu/mshyperv.c:100
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810611d0-ffffffff810611e6: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81061a40)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff81061a40-ffffffff81061a56: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81067920)
Location: arch/x86/kernel/cpu/mshyperv.c:97
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff81067920-ffffffff81067936: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810696d0)
Location: arch/x86/kernel/cpu/mshyperv.c:102
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810696d0-ffffffff810696e6: hv_remove_stimer0_irq (STB_GLOBAL)
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
In drivers/clocksource/hyperv_timer.c (ffffffff819a7cc8)
Location: drivers/clocksource/hyperv_timer.c:222
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In drivers/clocksource/hyperv_timer.c (ffffffff81a55293)
Location: drivers/clocksource/hyperv_timer.c:222
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In drivers/clocksource/hyperv_timer.c (ffffffff81bc49ff)
Location: drivers/clocksource/hyperv_timer.c:222
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a2a1)
Location: drivers/clocksource/hyperv_timer.c:223
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In drivers/clocksource/hyperv_timer.c (ffffffff81dd5661)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d7b1)
Location: drivers/clocksource/hyperv_timer.c:224
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
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
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810615c0)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810615c0-ffffffff810615d6: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81051a20)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff81051a20-ffffffff81051a36: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff810619f0)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff810619f0-ffffffff81061a06: hv_remove_stimer0_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hv_remove_stimer0_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mshyperv.c (ffffffff81062fa0)
Location: arch/x86/kernel/cpu/mshyperv.c:101
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_free
```
**Symbols:**

```
ffffffff81062fa0-ffffffff81062fb6: hv_remove_stimer0_irq (STB_GLOBAL)
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
