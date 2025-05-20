# Function: <code>rdt_cpu_has</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820ae6f2)
Location: arch/x86/kernel/cpu/intel_rdt.c:699
Inline: False
```
**Symbols:**

```
ffffffff820ae6f2-ffffffff820ae73b: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b4f4a)
Location: arch/x86/kernel/cpu/intel_rdt.c:702
Inline: False
```
**Symbols:**

```
ffffffff826b4f4a-ffffffff826b4f96: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826debf6)
Location: arch/x86/kernel/cpu/intel_rdt.c:772
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
**Symbols:**

```
ffffffff826debf6-ffffffff826dec3a: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82897c6f)
Location: arch/x86/kernel/cpu/resctrl/core.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82897c6f-ffffffff82897cb4: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828af7c6)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828af7c6-ffffffff828af811: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b2aff)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b2aff-ffffffff828b2b4a: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82cd7bc2)
Location: arch/x86/kernel/cpu/resctrl/core.c:804
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff82cd7bc2-ffffffff82cd7c0d: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82fc3b95)
Location: arch/x86/kernel/cpu/resctrl/core.c:808
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff82fc3b95-ffffffff82fc3be0: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff831ce1d9)
Location: arch/x86/kernel/cpu/resctrl/core.c:808
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff831ce1d9-ffffffff831ce21c: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b043b)
Location: arch/x86/kernel/cpu/resctrl/core.c:749
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff832b043b-ffffffff832b04c0: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8346152a)
Location: arch/x86/kernel/cpu/resctrl/core.c:749
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
```
**Symbols:**

```
ffffffff8346152a-ffffffff834615b7: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83e835b0)
Location: arch/x86/kernel/cpu/resctrl/core.c:702
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
```
**Symbols:**

```
ffffffff83e835b0-ffffffff83e83668: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff836a68e0)
Location: arch/x86/kernel/cpu/resctrl/core.c:731
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff836a68e0-ffffffff836a6998: rdt_cpu_has (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff838d6ed0)
Location: arch/x86/kernel/cpu/resctrl/core.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_alloc_resources
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
  - arch/x86/kernel/cpu/resctrl/monitor.c:rdt_get_mon_l3_config
```
**Symbols:**

```
ffffffff838d6ed0-ffffffff838d6f88: rdt_cpu_has (STB_GLOBAL)
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
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a0b1e)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828a0b1e-ffffffff828a0b69: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898c92)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82898c92-ffffffff82898cdd: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3ae1)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b3ae1-ffffffff828b3b2c: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rdt_cpu_has(int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3b0f)
Location: arch/x86/kernel/cpu/resctrl/core.c:802
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff828b3b0f-ffffffff828b3b5a: rdt_cpu_has (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
