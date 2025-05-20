# Function: <code>has_newer_microcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int has_newer_microcode(void *mc, unsigned int csig, int cpf, int new_rev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104e040)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:161
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_microcode_early
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
```
**Symbols:**

```
ffffffff8104e040-ffffffff8104e058: has_newer_microcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int has_newer_microcode(void *mc, unsigned int csig, int cpf, int new_rev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel_lib.c (ffffffff8104e1d0)
Location: arch/x86/kernel/cpu/microcode/intel_lib.c:176
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:find_microcode_patch
```
**Symbols:**

```
ffffffff8104e1d0-ffffffff8104e1e8: has_newer_microcode (STB_GLOBAL)
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fdcd)
Location: arch/x86/kernel/cpu/microcode/intel.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fe54)
Location: arch/x86/kernel/cpu/microcode/intel.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053811)
Location: arch/x86/kernel/cpu/microcode/intel.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810564a4)
Location: arch/x86/kernel/cpu/microcode/intel.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053b34)
Location: arch/x86/kernel/cpu/microcode/intel.c:96
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056cf5)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810575b5)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c875)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b0f5)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105baa5)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810650d0)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071b2e)
Location: arch/x86/kernel/cpu/microcode/intel.c:79
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810817c3)
Location: arch/x86/kernel/cpu/microcode/intel.c:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083cf2)
Location: arch/x86/kernel/cpu/microcode/intel.c:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
</details>
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057135)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047325)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057565)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058a05)
Location: arch/x86/kernel/cpu/microcode/intel.c:93
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
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
</ul>
