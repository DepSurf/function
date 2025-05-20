# Function: <code>vendor_disable_error_reporting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043635)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2073
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81043795)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2154
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047e2f)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2219
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810476ef)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1951
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b1af)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1963
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104daef)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1959
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mcheck/mce.c:mce_syscore_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81048b80)
Location: arch/x86/kernel/cpu/mce/core.c:1980
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81048b80-ffffffff81048bf1: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104bc30)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104bc30-ffffffff8104bcae: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c5f0)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104c5f0-ffffffff8104c66e: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81052b10)
Location: arch/x86/kernel/cpu/mce/core.c:2139
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81052b10-ffffffff81052b92: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81051970)
Location: arch/x86/kernel/cpu/mce/core.c:2215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81051970-ffffffff810519f2: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053140)
Location: arch/x86/kernel/cpu/mce/core.c:2226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81053140-ffffffff810531c2: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8105baf0-ffffffff8105bb8b: vendor_disable_error_reporting (STB_LOCAL)
ffffffff81c9b758-ffffffff81c9b76d: vendor_disable_error_reporting.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81067fa0)
Location: arch/x86/kernel/cpu/mce/core.c:2303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81067fa0-ffffffff81068077: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81077680)
Location: arch/x86/kernel/cpu/mce/core.c:2303
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81077680-ffffffff81077756: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810798e0)
Location: arch/x86/kernel/cpu/mce/core.c:2319
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff810798e0-ffffffff810799b1: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81081530)
Location: arch/x86/kernel/cpu/mce/core.c:2348
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff81081530-ffffffff81081601: vendor_disable_error_reporting (STB_LOCAL)
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
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c760)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104c760-ffffffff8104c7de: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103cda0)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8103cda0-ffffffff8103ce2b: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104c5a0)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104c5a0-ffffffff8104c61e: vendor_disable_error_reporting (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vendor_disable_error_reporting();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104d9b0)
Location: arch/x86/kernel/cpu/mce/core.c:2014
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:mce_cpu_pre_down
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_shutdown
  - arch/x86/kernel/cpu/mce/core.c:mce_syscore_suspend
```
**Symbols:**

```
ffffffff8104d9b0-ffffffff8104da2e: vendor_disable_error_reporting (STB_LOCAL)
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
