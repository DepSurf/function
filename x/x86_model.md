# Function: <code>x86_model</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d060)
Location: arch/x86/include/asm/microcode.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff8104d060-ffffffff8104d09f: x86_model (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8143cdb0)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8143cdb0-ffffffff8143cde5: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81459d30)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81459d30-ffffffff81459d65: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff818fb8a0)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff818fb8a0-ffffffff818fb8cd: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff819826f0)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff819826f0-ffffffff8198271d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff819dec00)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff819dec00-ffffffff819dec2d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a19b30)
Location: arch/x86/lib/cpu.c:17
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81a19b30-ffffffff81a19b5d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a89850)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81a89850-ffffffff81a8987d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81ac0af0)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81ac0af0-ffffffff81ac0b1d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff815fcde0)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
```
**Symbols:**

```
ffffffff815fcde0-ffffffff815fce0d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81621b70)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff81621b70-ffffffff81621b9d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81605470)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff81605470-ffffffff8160549d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81673d60)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff81673d60-ffffffff81673d8d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8178e410)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff8178e410-ffffffff8178e44d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8204bce0)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff8204bce0-ffffffff8204bd1d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff820ca550)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
```
**Symbols:**

```
ffffffff820ca550-ffffffff820ca58d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff821a4e50)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
```
**Symbols:**

```
ffffffff821a4e50-ffffffff821a4e8d: x86_model (STB_GLOBAL)
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
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a5f940)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81a5f940-ffffffff81a5f96d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a1ca10)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - drivers/edac/mce_amd.c:amd_decode_mce
```
**Symbols:**

```
ffffffff81a1ca10-ffffffff81a1ca3d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81acbd30)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81acbd30-ffffffff81acbd5d: x86_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int x86_model(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81ad8280)
Location: arch/x86/lib/cpu.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
```
**Symbols:**

```
ffffffff81ad8280-ffffffff81ad82ad: x86_model (STB_GLOBAL)
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
