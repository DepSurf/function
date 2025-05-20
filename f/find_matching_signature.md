# Function: <code>find_matching_signature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104dfc0)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:133
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:_save_mc
  - arch/x86/kernel/cpu/microcode/intel_lib.c:has_newer_microcode
```
**Symbols:**

```
ffffffff8104dfc0-ffffffff8104e03f: find_matching_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104e150)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:148
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:_save_mc
  - arch/x86/kernel/cpu/microcode/intel_lib.c:has_newer_microcode
```
**Symbols:**

```
ffffffff8104e150-ffffffff8104e1cf: find_matching_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fad0)
Location: arch/x86/kernel/cpu/microcode/intel.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8104fad0-ffffffff8104fb4f: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fa20)
Location: arch/x86/kernel/cpu/microcode/intel.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8104fa20-ffffffff8104fa9f: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053500)
Location: arch/x86/kernel/cpu/microcode/intel.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81053500-ffffffff8105357f: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810561a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff810561a0-ffffffff8105621d: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053830)
Location: arch/x86/kernel/cpu/microcode/intel.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81053830-ffffffff810538ad: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810569c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff810569c0-ffffffff81056a41: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057270)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81057270-ffffffff810572f1: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c520)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105c520-ffffffff8105c5a3: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ad90)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105ad90-ffffffff8105ae13: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b740)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105b740-ffffffff8105b7c3: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064d50)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81064d50-ffffffff81064dd3: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071750)
Location: arch/x86/kernel/cpu/microcode/intel.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81071750-ffffffff810717f9: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056df0)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056df0-ffffffff81056e71: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046fe0)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81046fe0-ffffffff81047061: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057220)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81057220-ffffffff810572a1: find_matching_signature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810586c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:find_patch
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff810586c0-ffffffff81058741: find_matching_signature (STB_LOCAL)
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
