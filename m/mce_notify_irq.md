# Function: <code>mce_notify_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044b00)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1334
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81044b00-ffffffff81044b83: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81044b70)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1389
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81044b70-ffffffff81044bf8: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810467f0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1457
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_irq_work_cb
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff810467f0-ffffffff81046878: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810464b0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1431
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff810464b0-ffffffff81046501: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81049ce0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1440
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81049ce0-ffffffff81049d31: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1418
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_timer_fn
  - arch/x86/kernel/cpu/mcheck/mce.c:do_machine_check
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104e6ee-ffffffff8104e704: mce_notify_irq.cold.43 (STB_LOCAL)
ffffffff8104c2b0-ffffffff8104c2f3: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810499bc)
Location: arch/x86/kernel/cpu/mce/core.c:1434
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104bdc5-ffffffff8104bddb: mce_notify_irq.cold.43 (STB_LOCAL)
ffffffff810499a0-ffffffff810499e3: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c8f7)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104ebbd-ffffffff8104ebd3: mce_notify_irq.cold (STB_LOCAL)
ffffffff8104c8e0-ffffffff8104c922: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d2b7)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104f54a-ffffffff8104f560: mce_notify_irq.cold (STB_LOCAL)
ffffffff8104d2a0-ffffffff8104d2e2: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051fc7)
Location: arch/x86/kernel/cpu/mce/core.c:1470
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81053b79-ffffffff81053b8f: mce_notify_irq.cold (STB_LOCAL)
ffffffff81051fb0-ffffffff81051ff2: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810510e7)
Location: arch/x86/kernel/cpu/mce/core.c:1545
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81bd56fd-ffffffff81bd5713: mce_notify_irq.cold (STB_LOCAL)
ffffffff810510d0-ffffffff81051112: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810528b7)
Location: arch/x86/kernel/cpu/mce/core.c:1557
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81bc7b37-ffffffff81bc7b4d: mce_notify_irq.cold (STB_LOCAL)
ffffffff810528a0-ffffffff810528e2: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8105ae77)
Location: arch/x86/kernel/cpu/mce/core.c:1618
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81c9b630-ffffffff81c9b646: mce_notify_irq.cold (STB_LOCAL)
ffffffff8105ae60-ffffffff8105aea2: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8106788c)
Location: arch/x86/kernel/cpu/mce/core.c:1681
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81e4ac6a-ffffffff81e4ac7b: mce_notify_irq.cold (STB_LOCAL)
ffffffff81067870-ffffffff810678bf: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81076d90)
Location: arch/x86/kernel/cpu/mce/core.c:1681
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81076d90-ffffffff81076de9: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078f90)
Location: arch/x86/kernel/cpu/mce/core.c:1694
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff81078f90-ffffffff81078fe9: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81080660)
Location: arch/x86/kernel/cpu/mce/core.c:1725
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
```
**Symbols:**

```
ffffffff81080660-ffffffff810806b9: mce_notify_irq (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d427)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104f6aa-ffffffff8104f6c0: mce_notify_irq.cold (STB_LOCAL)
ffffffff8104d410-ffffffff8104d452: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103ca87)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8103ecd7-ffffffff8103eced: mce_notify_irq.cold (STB_LOCAL)
ffffffff8103ca70-ffffffff8103cab2: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d267)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8104f4fa-ffffffff8104f510: mce_notify_irq.cold (STB_LOCAL)
ffffffff8104d250-ffffffff8104d292: mce_notify_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mce_notify_irq();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e677)
Location: arch/x86/kernel/cpu/mce/core.c:1467
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_timer_fn
  - arch/x86/kernel/cpu/mce/intel.c:cmci_intel_adjust_timer
```
**Symbols:**

```
ffffffff8105093a-ffffffff81050950: mce_notify_irq.cold (STB_LOCAL)
ffffffff8104e660-ffffffff8104e6a2: mce_notify_irq (STB_GLOBAL)
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
