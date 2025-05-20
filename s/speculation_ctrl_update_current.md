# Function: <code>speculation_ctrl_update_current</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103a8e0)
Location: arch/x86/kernel/process.c:475
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103a8e0-ffffffff8103a901: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103cee0)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103cee0-ffffffff8103cf01: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d6a0)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103d6a0-ffffffff8103d6c1: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040810)
Location: arch/x86/kernel/process.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81040810-ffffffff81040831: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040760)
Location: arch/x86/kernel/process.c:589
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:arch_prctl_spec_ctrl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81040760-ffffffff81040781: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81042150)
Location: arch/x86/kernel/process.c:601
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81042150-ffffffff81042171: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810484a0)
Location: arch/x86/kernel/process.c:618
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:arch_seccomp_spec_mitigate
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810484a0-ffffffff810484c1: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810517c0)
Location: arch/x86/kernel/process.c:634
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810517c0-ffffffff81051808: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105ee30)
Location: arch/x86/kernel/process.c:634
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff8105ee30-ffffffff8105ee78: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81060530)
Location: arch/x86/kernel/process.c:662
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff81060530-ffffffff81060578: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff810675b0)
Location: arch/x86/kernel/process.c:674
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ib_prctl_set
  - arch/x86/kernel/cpu/bugs.c:ssb_prctl_set
```
**Symbols:**

```
ffffffff810675b0-ffffffff810675f8: speculation_ctrl_update_current (STB_GLOBAL)
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
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d820)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103d820-ffffffff8103d841: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102cf10)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8102cf10-ffffffff8102cf31: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d660)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103d660-ffffffff8103d681: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void speculation_ctrl_update_current();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103e750)
Location: arch/x86/kernel/process.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:task_update_spec_tif
```
**Symbols:**

```
ffffffff8103e750-ffffffff8103e788: speculation_ctrl_update_current (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
