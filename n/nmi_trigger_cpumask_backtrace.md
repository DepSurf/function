# Function: <code>nmi_trigger_cpumask_backtrace</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff81450020)
Location: lib/nmi_backtrace.c:34
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81450020-ffffffff8145012a: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff818efdc0)
Location: lib/nmi_backtrace.c:35
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff818efdc0-ffffffff818efede: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff81976200)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81976200-ffffffff81976321: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff819d2ab5-ffffffff819d2aee: nmi_trigger_cpumask_backtrace.cold.5 (STB_LOCAL)
ffffffff819d2970-ffffffff819d2a63: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a0c135-ffffffff81a0c16e: nmi_trigger_cpumask_backtrace.cold.6 (STB_LOCAL)
ffffffff81a0bff0-ffffffff81a0c0e3: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a7ba8d-ffffffff81a7bac6: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81a7b950-ffffffff81a7ba3a: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81ab2ded-ffffffff81ab2e26: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81ab2cb0-ffffffff81ab2d9a: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff815ed68e-ffffffff815ed6c7: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff815ed550-ffffffff815ed63b: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81bf4c7a-ffffffff81bf4cb3: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81611d10-ffffffff81611dfb: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81be6b9d-ffffffff81be6bd6: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff815f53f0-ffffffff815f54db: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81cdf4b4-ffffffff81cdf4ed: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81662860-ffffffff8166294b: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81ea5c6e-ffffffff81ea5ca7: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff8177c6a0-ffffffff8177c7c2: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff82039170)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff82039170-ffffffff820392b4: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, int exclude_cpu, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff820b7480)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff820b7480-ffffffff820b75e0: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, int exclude_cpu, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (ffffffff82191630)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff82191630-ffffffff82191790: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (c0e8748c)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
c0e8748c-c0e875d4: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nmi_backtrace.c (c000000000ecf0b0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/powerpc/kernel/stacktrace.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
c000000000ecf0b0-c000000000ecf280: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a51c3d-ffffffff81a51c76: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81a51b00-ffffffff81a51bea: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81a0ed3d-ffffffff81a0ed76: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81a0ec00-ffffffff81a0ecea: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81abe02d-ffffffff81abe066: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81abdef0-ffffffff81abdfda: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void nmi_trigger_cpumask_backtrace(const cpumask_t *mask, bool exclude_self, void (*raise)(cpumask_t *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/nmi_backtrace.c (0)
Location: lib/nmi_backtrace.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/apic/hw_nmi.c:arch_trigger_cpumask_backtrace
```
**Symbols:**

```
ffffffff81aca4cb-ffffffff81aca504: nmi_trigger_cpumask_backtrace.cold (STB_LOCAL)
ffffffff81aca370-ffffffff81aca478: nmi_trigger_cpumask_backtrace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int exclude_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>bool exclude_self</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
