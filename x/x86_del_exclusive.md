# Function: <code>x86_del_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006075)
Location: arch/x86/events/core.c:380
Inline: True
Inline callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006150-ffffffff8100616c: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006325)
Location: arch/x86/events/core.c:388
Inline: True
Inline callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81005aa0-ffffffff81005abc: x86_del_exclusive.part.18 (STB_LOCAL)
ffffffff81006360-ffffffff8100637a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006340)
Location: arch/x86/events/core.c:393
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006340-ffffffff8100636a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810060e0)
Location: arch/x86/events/core.c:394
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff810060e0-ffffffff8100610a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006460)
Location: arch/x86/events/core.c:394
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006460-ffffffff8100648c: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006bd0)
Location: arch/x86/events/core.c:398
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006bd0-ffffffff81006bfb: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b10)
Location: arch/x86/events/core.c:398
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006b10-ffffffff81006b3b: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d20)
Location: arch/x86/events/core.c:398
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006d20-ffffffff81006d4a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006da0)
Location: arch/x86/events/core.c:399
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006da0-ffffffff81006dca: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e00)
Location: arch/x86/events/core.c:400
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81007e00-ffffffff81007e2a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006eb0)
Location: arch/x86/events/core.c:432
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006eb0-ffffffff81006eda: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810075d0)
Location: arch/x86/events/core.c:458
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff810075d0-ffffffff810075fa: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:458
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81c950ca-ffffffff81c950df: x86_del_exclusive.cold (STB_LOCAL)
ffffffff81007e70-ffffffff81007ec9: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:460
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81e443b3-ffffffff81e443c8: x86_del_exclusive.cold (STB_LOCAL)
ffffffff810073d0-ffffffff81007431: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:463
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff820502a4-ffffffff820502b9: x86_del_exclusive.cold (STB_LOCAL)
ffffffff81008c50-ffffffff81008cb1: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:463
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff820ce729-ffffffff820ce73e: x86_del_exclusive.cold (STB_LOCAL)
ffffffff81008480-ffffffff810084e1: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:461
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff821a8f65-ffffffff821a8f7a: x86_del_exclusive.cold (STB_LOCAL)
ffffffff8100dba0-ffffffff8100dc01: x86_del_exclusive (STB_GLOBAL)
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
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006da0)
Location: arch/x86/events/core.c:399
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006da0-ffffffff81006dca: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810054c0)
Location: arch/x86/events/core.c:399
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff810054c0-ffffffff810054ea: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d60)
Location: arch/x86/events/core.c:399
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006d60-ffffffff81006d8a: x86_del_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void x86_del_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006ec0)
Location: arch/x86/events/core.c:399
Inline: False
Direct callers:
  - arch/x86/events/core.c:hw_perf_lbr_event_destroy
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/bts.c:bts_event_destroy
  - arch/x86/events/intel/pt.c:pt_event_init
  - arch/x86/events/intel/pt.c:pt_event_destroy
```
**Symbols:**

```
ffffffff81006ec0-ffffffff81006eea: x86_del_exclusive (STB_GLOBAL)
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
