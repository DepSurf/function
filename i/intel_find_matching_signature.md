# Function: <code>intel_find_matching_signature</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810719b0)
Location: arch/x86/kernel/cpu/intel.c:221
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
ffffffff810719b0-ffffffff81071a59: intel_find_matching_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_find_matching_signature(void *mc, unsigned int csig, int cpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff810735a0)
Location: arch/x86/kernel/cpu/intel.c:221
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
ffffffff810735a0-ffffffff81073649: intel_find_matching_signature (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool intel_find_matching_signature(void *mc, struct cpu_signature *sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108b200)
Location: arch/x86/kernel/cpu/microcode/intel.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:parse_microcode_blobs
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
```
**Symbols:**

```
ffffffff8108b200-ffffffff8108b2b5: intel_find_matching_signature (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct cpu_signature *sig</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int csig</code>
</li>
<li>
<b>Param removed. </b>
<code>int cpf</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
</ul>
