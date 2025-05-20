# Function: <code>check_msr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8107c6a6)
Location: arch/x86/events/intel/core.c:3117
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8107c6a6-ffffffff8107c755: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8107e01c)
Location: arch/x86/events/intel/core.c:3405
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8107e01c-ffffffff8107e121: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810825bc)
Location: arch/x86/events/intel/core.c:3425
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff810825bc-ffffffff810826c1: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c9ca)
Location: arch/x86/events/intel/core.c:3589
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100c9ca-ffffffff8100cad0: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cf6a)
Location: arch/x86/events/intel/core.c:3607
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100cf6a-ffffffff8100d067: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d69a)
Location: arch/x86/events/intel/core.c:3632
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100d69a-ffffffff8100d797: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100db65)
Location: arch/x86/events/intel/core.c:3878
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100db65-ffffffff8100dc62: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8289ee3a)
Location: arch/x86/events/intel/core.c:4052
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100e432-ffffffff8100e52f: check_msr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a1eeb)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100ea72-ffffffff8100eb6f: check_msr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fe1a)
Location: arch/x86/events/intel/core.c:4108
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100fe1a-ffffffff8100ff08: check_msr.part.0 (STB_LOCAL)
ffffffff8100ff08-ffffffff8100ff28: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81bd217d)
Location: arch/x86/events/intel/core.c:4475
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81bd217d-ffffffff81bd2265: check_msr.part.0 (STB_LOCAL)
ffffffff81bd2265-ffffffff81bd2285: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81bc43c9)
Location: arch/x86/events/intel/core.c:4762
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81bc43c9-ffffffff81bc44e1: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81c95909)
Location: arch/x86/events/intel/core.c:4782
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81c95909-ffffffff81c95a21: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81e44b34)
Location: arch/x86/events/intel/core.c:4852
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81e44b34-ffffffff81e44c53: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014ea0)
Location: arch/x86/events/intel/core.c:4978
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81014ea0-ffffffff81014fdf: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014700)
Location: arch/x86/events/intel/core.c:5109
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81014700-ffffffff8101483f: check_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool check_msr(long unsigned int msr, u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101a1b0)
Location: arch/x86/events/intel/core.c:5273
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8101a1b0-ffffffff8101a2ef: check_msr (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8288feeb)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100ea72-ffffffff8100eb6f: check_msr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8288de27)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100d7e0-ffffffff8100d8ce: check_msr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a2eeb)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100ea32-ffffffff8100eb2f: check_msr.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff828a2eff)
Location: arch/x86/events/intel/core.c:4070
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff8100ec02-ffffffff8100ecff: check_msr.part.0 (STB_LOCAL)
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
