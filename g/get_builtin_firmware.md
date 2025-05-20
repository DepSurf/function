# Function: <code>get_builtin_firmware</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ce50)
Location: arch/x86/kernel/cpu/microcode/core.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff8104ce50-ffffffff8104ceb7: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ced0)
Location: arch/x86/kernel/cpu/microcode/core.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff8104ced0-ffffffff8104cf37: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f320)
Location: arch/x86/kernel/cpu/microcode/core.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:get_builtin_microcode
```
**Symbols:**

```
ffffffff8104f320-ffffffff8104f387: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f240)
Location: arch/x86/kernel/cpu/microcode/core.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff8104f240-ffffffff8104f2a7: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052c90)
Location: arch/x86/kernel/cpu/microcode/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81052c90-ffffffff81052cf7: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055960)
Location: arch/x86/kernel/cpu/microcode/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81055960-ffffffff810559c7: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81053000)
Location: arch/x86/kernel/cpu/microcode/core.c:155
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81053000-ffffffff81053067: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810561b0)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff810561b0-ffffffff8105621c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056a60)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81056a60-ffffffff81056acc: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bc10)
Location: arch/x86/kernel/cpu/microcode/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff8105bc10-ffffffff8105bc7c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a660)
Location: arch/x86/kernel/cpu/microcode/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff8105a660-ffffffff8105a6cc: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b000)
Location: arch/x86/kernel/cpu/microcode/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff8105b000-ffffffff8105b06c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81064580)
Location: arch/x86/kernel/cpu/microcode/core.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81064580-ffffffff810645ec: get_builtin_firmware (STB_GLOBAL)
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
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810565e0)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff810565e0-ffffffff8105664c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810467f0)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff810467f0-ffffffff8104685c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056a10)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81056a10-ffffffff81056a7c: get_builtin_firmware (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool get_builtin_firmware(struct cpio_data *cd, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057eb0)
Location: arch/x86/kernel/cpu/microcode/core.c:151
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_builtin_intel_microcode
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
```
**Symbols:**

```
ffffffff81057eb0-ffffffff81057f1c: get_builtin_firmware (STB_GLOBAL)
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
