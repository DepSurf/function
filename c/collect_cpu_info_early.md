# Function: <code>collect_cpu_info_early</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dc00)
Location: arch/x86/kernel/cpu/microcode/intel.c:350
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
**Symbols:**

```
ffffffff8104dc00-ffffffff8104dce0: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104dba0)
Location: arch/x86/kernel/cpu/microcode/intel.c:359
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_ap
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
**Symbols:**

```
ffffffff8104dba0-ffffffff8104dcd1: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050450)
Location: arch/x86/kernel/cpu/microcode/intel.c:371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81050450-ffffffff81050583: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050330)
Location: arch/x86/kernel/cpu/microcode/intel.c:383
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81050330-ffffffff810503ed: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053d60)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81053d60-ffffffff81053e1d: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810569b0)
Location: arch/x86/kernel/cpu/microcode/intel.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff810569b0-ffffffff81056a6d: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81054040)
Location: arch/x86/kernel/cpu/microcode/intel.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81054040-ffffffff810540fd: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057250)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057250-ffffffff81057310: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057b20)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057b20-ffffffff81057be0: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cce0)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105cce0-ffffffff8105cd99: collect_cpu_info_early.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b540)
Location: arch/x86/kernel/cpu/microcode/intel.c:345
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105b540-ffffffff8105b5f9: collect_cpu_info_early.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105bef0)
Location: arch/x86/kernel/cpu/microcode/intel.c:345
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105bef0-ffffffff8105bfa9: collect_cpu_info_early.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81065570)
Location: arch/x86/kernel/cpu/microcode/intel.c:345
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81065570-ffffffff81065629: collect_cpu_info_early.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810576a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff810576a0-ffffffff81057760: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047890)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81047890-ffffffff81047950: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057ad0)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057ad0-ffffffff81057b90: collect_cpu_info_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int collect_cpu_info_early(struct ucode_cpu_info *uci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058f70)
Location: arch/x86/kernel/cpu/microcode/intel.c:388
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81058f70-ffffffff81059030: collect_cpu_info_early (STB_LOCAL)
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
