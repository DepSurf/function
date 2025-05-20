# Function: <code>call_on_cpu</code>

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
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81531420)
Location: drivers/acpi/processor_throttling.c:912
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81531420-ffffffff81531460: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81592480)
Location: drivers/acpi/processor_throttling.c:912
Inline: False
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81592480-ffffffff815924c3: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815c9bb0)
Location: drivers/acpi/processor_throttling.c:913
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff815c9bb0-ffffffff815c9bf1: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e3190)
Location: drivers/acpi/processor_throttling.c:913
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff815e3190-ffffffff815e31d1: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81614d40)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81614d40-ffffffff81614d81: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81636230)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff81636230-ffffffff81636271: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff810689fd)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e35b0)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106a69d)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff81701210)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff8106b15d)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff816e298c)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff81075c3e)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff8175b5d4)
Location: include/acpi/processor.h:300
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff810849cd)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff8188ee9d)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff810978fd)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff819d6ab6)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff8109a9d3)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a1e476)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/cstate.c (ffffffff810a2203)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - arch/x86/kernel/acpi/cstate.c:acpi_processor_ffh_cstate_probe
```
```
In drivers/acpi/processor_throttling.c (ffffffff81a6978a)
Location: include/acpi/processor.h:305
Inline: True
Inline callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816057f0)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff816057f0-ffffffff81605831: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815f07e0)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff815f07e0-ffffffff815f0821: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8162a510)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff8162a510-ffffffff8162a551: call_on_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int call_on_cpu(int cpu, long int (*fn)(void *), void *arg, bool direct);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816443b0)
Location: drivers/acpi/processor_throttling.c:900
Inline: True
Direct callers:
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:__acpi_processor_set_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff816443b0-ffffffff816443f1: call_on_cpu (STB_LOCAL)
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
