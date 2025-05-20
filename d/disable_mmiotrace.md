# Function: <code>disable_mmiotrace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff810748d0)
Location: arch/x86/mm/mmio-mod.c:461
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff810748d0-ffffffff81074a70: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81075ec0)
Location: arch/x86/mm/mmio-mod.c:461
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81075ec0-ffffffff8107606f: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81079aa0)
Location: arch/x86/mm/mmio-mod.c:461
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81079aa0-ffffffff81079c53: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff81078350)
Location: arch/x86/mm/mmio-mod.c:461
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81078350-ffffffff8107850a: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmio-mod.c (ffffffff8107e6a0)
Location: arch/x86/mm/mmio-mod.c:461
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8107e6a0-ffffffff8107e847: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:460
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff810818ea-ffffffff81081981: disable_mmiotrace.cold.13 (STB_LOCAL)
ffffffff810816c0-ffffffff810817d4: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:460
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff810884fa-ffffffff81088591: disable_mmiotrace.cold.14 (STB_LOCAL)
ffffffff810882d0-ffffffff810883e4: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8108c13e-ffffffff8108c1d2: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8108bf20-ffffffff8108c024: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8108cd9e-ffffffff8108ce32: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8108cb80-ffffffff8108cc84: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81094319-ffffffff810943ad: disable_mmiotrace.cold (STB_LOCAL)
ffffffff81094150-ffffffff81094254: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81bda10a-ffffffff81bda19e: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810936a0-ffffffff810937a4: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81bcc1bc-ffffffff81bcc250: disable_mmiotrace.cold (STB_LOCAL)
ffffffff81094060-ffffffff81094164: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81ca217f-ffffffff81ca2233: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810a3e60-ffffffff810a3f64: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff81e517e0-ffffffff81e5188f: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810b8560-ffffffff810b8671: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff820552e9-ffffffff820552fe: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810d3de0-ffffffff810d3f1e: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff820d38b8-ffffffff820d38cd: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810d71c0-ffffffff810d72fe: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:446
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff821ae726-ffffffff821ae73b: disable_mmiotrace.cold (STB_LOCAL)
ffffffff810dfa20-ffffffff810dfb5e: disable_mmiotrace (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8108bd5e-ffffffff8108bdf2: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8108bb40-ffffffff8108bc44: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8107a89c-ffffffff8107a930: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8107a660-ffffffff8107a75e: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8108bd0e-ffffffff8108bda2: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8108baf0-ffffffff8108bbf4: disable_mmiotrace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void disable_mmiotrace();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmio-mod.c (0)
Location: arch/x86/mm/mmio-mod.c:448
Inline: False
Direct callers:
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
```
**Symbols:**

```
ffffffff8108e073-ffffffff8108e107: disable_mmiotrace.cold (STB_LOCAL)
ffffffff8108de50-ffffffff8108df4b: disable_mmiotrace (STB_GLOBAL)
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
