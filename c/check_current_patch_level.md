# Function: <code>check_current_patch_level</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool check_current_patch_level(u32 *rev, bool early);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e33e)
Location: arch/x86/kernel/cpu/microcode/amd.c:627
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
**Symbols:**

```
ffffffff8104e850-ffffffff8104e8a7: check_current_patch_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool check_current_patch_level(u32 *rev, bool early);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e3d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:639
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
```
**Symbols:**

```
ffffffff8104e3d0-ffffffff8104e458: check_current_patch_level (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool check_current_patch_level(u32 *rev, bool early);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810510b0)
Location: arch/x86/kernel/cpu/microcode/amd.c:654
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff810510b0-ffffffff81051138: check_current_patch_level (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
