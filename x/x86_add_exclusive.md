# Function: <code>x86_add_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006090)
Location: arch/x86/events/core.c:358
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006090-ffffffff81006144: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100643d)
Location: arch/x86/events/core.c:363
Inline: True
Inline callers:
  - arch/x86/events/core.c:x86_setup_perfctr
Direct callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff810059d0-ffffffff81005a96: x86_add_exclusive.part.17 (STB_LOCAL)
ffffffff81006340-ffffffff8100635c: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006260)
Location: arch/x86/events/core.c:364
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006260-ffffffff81006337: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006010)
Location: arch/x86/events/core.c:365
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006010-ffffffff810060d9: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006390)
Location: arch/x86/events/core.c:365
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006390-ffffffff81006459: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b00)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_setup_perfctr
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006b00-ffffffff81006bce: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006a40)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006a40-ffffffff81006b0e: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006c60)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006c60-ffffffff81006d11: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006cf0)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006cf0-ffffffff81006d9f: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d50)
Location: arch/x86/events/core.c:370
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81007d50-ffffffff81007dff: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006e00)
Location: arch/x86/events/core.c:402
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006e00-ffffffff81006eaf: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007520)
Location: arch/x86/events/core.c:428
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81007520-ffffffff810075cf: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:428
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81c950b5-ffffffff81c950ca: x86_add_exclusive.cold (STB_LOCAL)
ffffffff81007d70-ffffffff81007e68: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:430
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81e4439e-ffffffff81e443b3: x86_add_exclusive.cold (STB_LOCAL)
ffffffff810072b0-ffffffff810073c4: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:433
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff8205028f-ffffffff820502a4: x86_add_exclusive.cold (STB_LOCAL)
ffffffff81008b20-ffffffff81008c34: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:433
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff820ce714-ffffffff820ce729: x86_add_exclusive.cold (STB_LOCAL)
ffffffff81008350-ffffffff81008464: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:431
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_bts_config
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff821a8f50-ffffffff821a8f65: x86_add_exclusive.cold (STB_LOCAL)
ffffffff8100da70-ffffffff8100db84: x86_add_exclusive (STB_GLOBAL)
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
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006cf0)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006cf0-ffffffff81006d9f: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005410)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81005410-ffffffff810054bf: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006cb0)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006cb0-ffffffff81006d5f: x86_add_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x86_add_exclusive(unsigned int what);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006e10)
Location: arch/x86/events/core.c:369
Inline: False
Direct callers:
  - arch/x86/events/intel/bts.c:bts_event_init
  - arch/x86/events/intel/pt.c:pt_init
  - arch/x86/events/intel/pt.c:pt_event_init
```
**Symbols:**

```
ffffffff81006e10-ffffffff81006ebf: x86_add_exclusive (STB_GLOBAL)
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
