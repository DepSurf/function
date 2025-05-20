# Function: <code>intel_init_lmce</code>

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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff810479e4)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff81047acf)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104966d)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104900d)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104ca3d)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
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
In arch/x86/kernel/cpu/mcheck/mce_intel.c (ffffffff8104f71b)
Location: arch/x86/kernel/cpu/mcheck/mce_intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mcheck/mce_intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104cddb)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8104fd0b)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105069b)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81054c80)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81054c80-ffffffff81054cfd: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81053bc0)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81053bc0-ffffffff81053c3d: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81055490)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81055490-ffffffff8105550d: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105de30)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8105de30-ffffffff8105dead: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8106a580)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8106a580-ffffffff8106a64a: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107a3b0)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8107a3b0-ffffffff8107a47a: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8107c660)
Location: arch/x86/kernel/cpu/mce/intel.c:448
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff8107c660-ffffffff8107c727: intel_init_lmce (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void intel_init_lmce();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81083b50)
Location: arch/x86/kernel/cpu/mce/intel.c:425
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:__mcheck_cpu_init_vendor
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
**Symbols:**

```
ffffffff81083b50-ffffffff81083c17: intel_init_lmce (STB_GLOBAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105079b)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8103fde8)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff8105064b)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/intel.c (ffffffff81051a8b)
Location: arch/x86/kernel/cpu/mce/intel.c:445
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/intel.c:mce_intel_feature_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
