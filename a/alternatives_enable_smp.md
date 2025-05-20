# Function: <code>alternatives_enable_smp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036ad0)
Location: arch/x86/kernel/alternative.c:535
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81036ad0-ffffffff81036c2b: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035cd0)
Location: arch/x86/kernel/alternative.c:536
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81035cd0-ffffffff81035e2d: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035a00)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81035a00-ffffffff81035b59: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810339b0)
Location: arch/x86/kernel/alternative.c:547
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810339b0-ffffffff81033b07: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035d00)
Location: arch/x86/kernel/alternative.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81035d00-ffffffff81035e50: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:534
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810370d1-ffffffff81037192: alternatives_enable_smp.cold.10 (STB_LOCAL)
ffffffff81036c50-ffffffff81036cd6: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810382e1-ffffffff810383a2: alternatives_enable_smp.cold.9 (STB_LOCAL)
ffffffff81037e60-ffffffff81037ee6: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103a5ca-ffffffff8103a68b: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff81039d70-ffffffff81039df6: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103ad97-ffffffff8103ae54: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103a550-ffffffff8103a5d6: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8103da1d-ffffffff8103dada: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103d390-ffffffff8103d410: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:545
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81bd3f3c-ffffffff81bd3ff9: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103d870-ffffffff8103d8f0: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81bc641d-ffffffff81bc64da: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103f220-ffffffff8103f2a0: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81c99468-ffffffff81c99539: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff81044fd0-ffffffff8104505c: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:725
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff81e48a75-ffffffff81e48b4e: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8104d580-ffffffff8104d61a: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1179
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff82052420-ffffffff82052434: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff81059a80-ffffffff81059be0: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1356
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff820d0919-ffffffff820d092d: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8105b020-ffffffff8105b180: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1506
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff821ab442-ffffffff821ab456: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff81062320-ffffffff81062480: alternatives_enable_smp (STB_GLOBAL)
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
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103aef7-ffffffff8103afb4: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103a6b0-ffffffff8103a736: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8102a707-ffffffff8102a7c4: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff81029ee0-ffffffff81029f66: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103ad57-ffffffff8103ae14: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103a510-ffffffff8103a596: alternatives_enable_smp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void alternatives_enable_smp();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:542
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:common_cpu_up
```
**Symbols:**

```
ffffffff8103bd57-ffffffff8103be14: alternatives_enable_smp.cold (STB_LOCAL)
ffffffff8103b510-ffffffff8103b596: alternatives_enable_smp (STB_GLOBAL)
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
