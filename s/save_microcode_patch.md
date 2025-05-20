# Function: <code>save_microcode_patch</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fbd0)
Location: arch/x86/kernel/cpu/microcode/intel.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8104fbd0-ffffffff8104fce4: save_microcode_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fc50)
Location: arch/x86/kernel/cpu/microcode/intel.c:166
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8104fc50-ffffffff8104fd6a: save_microcode_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053600)
Location: arch/x86/kernel/cpu/microcode/intel.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81053600-ffffffff81053714: save_microcode_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810562a0-ffffffff810563ae: save_microcode_patch (STB_LOCAL)
ffffffff81056f71-ffffffff81056f99: save_microcode_patch.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:170
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81053930-ffffffff81053a3e: save_microcode_patch (STB_LOCAL)
ffffffff81054601-ffffffff81054629: save_microcode_patch.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81056ac0-ffffffff81056bd3: save_microcode_patch (STB_LOCAL)
ffffffff8105781f-ffffffff81057847: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81057370-ffffffff81057483: save_microcode_patch (STB_LOCAL)
ffffffff810580ff-ffffffff81058127: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105c630-ffffffff8105c743: save_microcode_patch (STB_LOCAL)
ffffffff8105d30f-ffffffff8105d337: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105aea0-ffffffff8105afca: save_microcode_patch (STB_LOCAL)
ffffffff81bd607f-ffffffff81bd60a7: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff8105b850-ffffffff8105b97a: save_microcode_patch (STB_LOCAL)
ffffffff81bc842b-ffffffff81bc8453: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81064e60-ffffffff81064f8a: save_microcode_patch (STB_LOCAL)
ffffffff81c9c310-ffffffff81c9c338: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:106
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81071890-ffffffff810719df: save_microcode_patch (STB_LOCAL)
ffffffff81e4b64f-ffffffff81e4b677: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081500)
Location: arch/x86/kernel/cpu/microcode/intel.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81081500-ffffffff81081658: save_microcode_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_microcode_patch(struct ucode_cpu_info *uci, void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083a30)
Location: arch/x86/kernel/cpu/microcode/intel.c:78
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81083a30-ffffffff81083b88: save_microcode_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff838d674d)
Location: arch/x86/kernel/cpu/microcode/intel.c:248
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_builtin_microcode
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
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81056ef0-ffffffff81057003: save_microcode_patch (STB_LOCAL)
ffffffff81057c7f-ffffffff81057ca7: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810470e0-ffffffff810471f3: save_microcode_patch (STB_LOCAL)
ffffffff81047e72-ffffffff81047e9a: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81057320-ffffffff81057433: save_microcode_patch (STB_LOCAL)
ffffffff810580af-ffffffff810580d7: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void save_microcode_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:167
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:generic_load_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff810587c0-ffffffff810588d3: save_microcode_patch (STB_LOCAL)
ffffffff8105954f-ffffffff81059577: save_microcode_patch.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucode_cpu_info *uci</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, size</code> ➡️ <code>uci, data, size</code>
</li>
</ul>
</details>
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
