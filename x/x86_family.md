# Function: <code>x86_family</code>

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
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81f6ce33)
Location: arch/x86/include/asm/microcode.h:133
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8143cdb5)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8143cd80-ffffffff8143cda3: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81459d35)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
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
ffffffff81459d00-ffffffff81459d23: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff818fb8a5)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff818fb870-ffffffff818fb894: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff819826f5)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff819826c0-ffffffff819826e4: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff819dec05)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff819debd0-ffffffff819debf4: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a19b35)
Location: arch/x86/lib/cpu.c:4
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81a19b00-ffffffff81a19b24: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a89855)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81a89820-ffffffff81a89844: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81ac0af5)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81ac0ac0-ffffffff81ac0ae4: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff815fcde5)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/intel.c:microcode_matches
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff815fcdb0-ffffffff815fcdd4: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81621b75)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:parse_container
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81621b40-ffffffff81621b64: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81605475)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81605440-ffffffff81605464: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81673d65)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81673d30-ffffffff81673d54: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8178e415)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8178e3e0-ffffffff8178e410: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff8204bce5)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8204bca0-ffffffff8204bcd0: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff820ca555)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/intel.c:intel_cpu_collect_info
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff820ca510-ffffffff820ca540: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff821a4e55)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
  - arch/x86/kernel/cpu/microcode/intel.c:intel_collect_cpu_info
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
```
**Symbols:**

```
ffffffff821a4e10-ffffffff821a4e40: x86_family (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a5f945)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81a5f910-ffffffff81a5f934: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81a1ca15)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
  - drivers/edac/mce_amd.c:amd_decode_mce
  - drivers/edac/mce_amd.c:amd_decode_mce
  - drivers/edac/mce_amd.c:amd_decode_mce
```
**Symbols:**

```
ffffffff81a1c9e0-ffffffff81a1ca04: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81acbd35)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81acbd00-ffffffff81acbd24: x86_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int x86_family(unsigned int sig);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/cpu.c (ffffffff81ad8285)
Location: arch/x86/lib/cpu.c:6
Inline: True
Inline callers:
  - arch/x86/lib/cpu.c:x86_model
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:collect_cpu_info_early
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/intel.c:scan_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:scan_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81ad8250-ffffffff81ad8274: x86_family (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
