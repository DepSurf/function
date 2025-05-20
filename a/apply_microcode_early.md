# Function: <code>apply_microcode_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104d4e0)
Location: arch/x86/kernel/cpu/microcode/intel.c:647
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
**Symbols:**

```
ffffffff8104d4e0-ffffffff8104d589: apply_microcode_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dce0)
Location: arch/x86/kernel/cpu/microcode/intel.c:616
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8104dce0-ffffffff8104de17: apply_microcode_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050660)
Location: arch/x86/kernel/cpu/microcode/intel.c:575
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81050660-ffffffff8105078d: apply_microcode_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810504c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:587
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff810504c0-ffffffff81050581: apply_microcode_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810540a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:583
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff810540a0-ffffffff81054193: apply_microcode_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81056c90-ffffffff81056d6c: apply_microcode_early (STB_LOCAL)
ffffffff81057015-ffffffff8105703c: apply_microcode_early.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:584
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81054320-ffffffff810543fc: apply_microcode_early (STB_LOCAL)
ffffffff810546a5-ffffffff810546cc: apply_microcode_early.cold.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81057540-ffffffff8105761c: apply_microcode_early (STB_LOCAL)
ffffffff810578ef-ffffffff81057916: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81057e20-ffffffff81057efc: apply_microcode_early (STB_LOCAL)
ffffffff810581c1-ffffffff810581e8: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8105d030-ffffffff8105d10a: apply_microcode_early (STB_LOCAL)
ffffffff8105d3ca-ffffffff8105d3ed: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8105b890-ffffffff8105b96a: apply_microcode_early (STB_LOCAL)
ffffffff81bd613a-ffffffff81bd615d: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8105c240-ffffffff8105c324: apply_microcode_early (STB_LOCAL)
ffffffff81bc84e6-ffffffff81bc8503: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81065710-ffffffff81065813: apply_microcode_early (STB_LOCAL)
ffffffff81c9c360-ffffffff81c9c3b0: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:500
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81072180-ffffffff8107229d: apply_microcode_early (STB_LOCAL)
ffffffff81e4b6a7-ffffffff81e4b6e8: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81082300)
Location: arch/x86/kernel/cpu/microcode/intel.c:374
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81082300-ffffffff8108242b: apply_microcode_early.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810847a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:364
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff810847a0-ffffffff8108489a: apply_microcode_early.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8108bd15)
Location: arch/x86/kernel/cpu/microcode/intel.c:339
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
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
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff810579a0-ffffffff81057a7c: apply_microcode_early (STB_LOCAL)
ffffffff81057d41-ffffffff81057d68: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81047b90-ffffffff81047c6c: apply_microcode_early (STB_LOCAL)
ffffffff81047f32-ffffffff81047f59: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81057dd0-ffffffff81057eac: apply_microcode_early (STB_LOCAL)
ffffffff81058171-ffffffff81058198: apply_microcode_early.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int apply_microcode_early(struct ucode_cpu_info *uci, bool early);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (0)
Location: arch/x86/kernel/cpu/microcode/intel.c:581
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff81059270-ffffffff8105934c: apply_microcode_early (STB_LOCAL)
ffffffff81059611-ffffffff81059638: apply_microcode_early.cold (STB_LOCAL)
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
