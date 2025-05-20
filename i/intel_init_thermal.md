# Function: <code>intel_init_thermal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049940)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:472
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81049940-ffffffff81049c61: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff81049af0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:471
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81049af0-ffffffff81049dcc: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104bef0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:444
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8104bef0-ffffffff8104c1cc: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104b560)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:438
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8104b560-ffffffff8104b82a: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (ffffffff8104ef70)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8104ef70-ffffffff8104f246: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mcheck/therm_throt.c:424
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81051f87-ffffffff81051fb4: intel_init_thermal.cold.7 (STB_LOCAL)
ffffffff81051c70-ffffffff81051f41: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:427
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8104f5e9-ffffffff8104f616: intel_init_thermal.cold.8 (STB_LOCAL)
ffffffff8104f2f0-ffffffff8104f5c1: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81052752-ffffffff8105277f: intel_init_thermal.cold (STB_LOCAL)
ffffffff81052410-ffffffff810526e4: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81053042-ffffffff8105306f: intel_init_thermal.cold (STB_LOCAL)
ffffffff81052d00-ffffffff81052fd4: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8105802c-ffffffff81058059: intel_init_thermal.cold (STB_LOCAL)
ffffffff81057d10-ffffffff81057fa6: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81bd5aec-ffffffff81bd5b19: intel_init_thermal.cold (STB_LOCAL)
ffffffff81056a90-ffffffff81056d26: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81c17f27-ffffffff81c17f54: intel_init_thermal.cold (STB_LOCAL)
ffffffff81947450-ffffffff819476d9: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81d27212-ffffffff81d272e6: intel_init_thermal.cold (STB_LOCAL)
ffffffff819ec2b0-ffffffff819ec579: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:656
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff81ef30bc-ffffffff81ef3191: intel_init_thermal.cold (STB_LOCAL)
ffffffff81b522a0-ffffffff81b525a9: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:660
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff820a7c8c-ffffffff820a7d34: intel_init_thermal.cold (STB_LOCAL)
ffffffff81cea460-ffffffff81cea79d: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:716
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8212906a-ffffffff82129112: intel_init_thermal.cold (STB_LOCAL)
ffffffff81d52fa0-ffffffff81d533a4: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/intel/therm_throt.c (0)
Location: drivers/thermal/intel/therm_throt.c:716
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:init_intel
```
**Symbols:**

```
ffffffff8220aa53-ffffffff8220aafb: intel_init_thermal.cold (STB_LOCAL)
ffffffff81e09d00-ffffffff81e0a0e8: intel_init_thermal (STB_GLOBAL)
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
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81053142-ffffffff8105316f: intel_init_thermal.cold (STB_LOCAL)
ffffffff81052e00-ffffffff810530d4: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81042c8f-ffffffff81042cbc: intel_init_thermal.cold (STB_LOCAL)
ffffffff81042850-ffffffff81042c21: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81052ff2-ffffffff8105301f: intel_init_thermal.cold (STB_LOCAL)
ffffffff81052cb0-ffffffff81052f84: intel_init_thermal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void intel_init_thermal(struct cpuinfo_x86 *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/therm_throt.c (0)
Location: arch/x86/kernel/cpu/mce/therm_throt.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81054472-ffffffff8105449f: intel_init_thermal.cold (STB_LOCAL)
ffffffff81054130-ffffffff81054404: intel_init_thermal (STB_GLOBAL)
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
