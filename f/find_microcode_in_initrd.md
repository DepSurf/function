# Function: <code>find_microcode_in_initrd</code>

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
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f430)
Location: arch/x86/kernel/cpu/microcode/core.c:215
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff8104f430-ffffffff8104f4f5: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f350)
Location: arch/x86/kernel/cpu/microcode/core.c:244
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8104f350-ffffffff8104f449: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052da0)
Location: arch/x86/kernel/cpu/microcode/core.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81052da0-ffffffff81052e99: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055a70)
Location: arch/x86/kernel/cpu/microcode/core.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81055a70-ffffffff81055b69: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81053110)
Location: arch/x86/kernel/cpu/microcode/core.c:261
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81053110-ffffffff81053209: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810562c0)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810562c0-ffffffff810563c4: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056b70)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81056b70-ffffffff81056c74: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bd20)
Location: arch/x86/kernel/cpu/microcode/core.c:252
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105bd20-ffffffff8105be22: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a770)
Location: arch/x86/kernel/cpu/microcode/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105a770-ffffffff8105a872: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b110)
Location: arch/x86/kernel/cpu/microcode/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff8105b110-ffffffff8105b212: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81c9c194-ffffffff81c9c1b0: find_microcode_in_initrd.cold (STB_LOCAL)
ffffffff810646a0-ffffffff810647bd: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81e4b513-ffffffff81e4b530: find_microcode_in_initrd.cold (STB_LOCAL)
ffffffff81070f80-ffffffff810710ad: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff82052f87-ffffffff82052fa4: find_microcode_in_initrd.cold (STB_LOCAL)
ffffffff81081040-ffffffff8108116d: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:233
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff820d152c-ffffffff820d1549: find_microcode_in_initrd.cold (STB_LOCAL)
ffffffff810834c0-ffffffff810835ed: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff838d63f0)
Location: arch/x86/kernel/cpu/microcode/core.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
  - arch/x86/kernel/cpu/microcode/amd.c:find_blobs_in_containers
```
**Symbols:**

```
ffffffff838d63f0-ffffffff838d648e: find_microcode_in_initrd (STB_GLOBAL)
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
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810566f0)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff810566f0-ffffffff810567f4: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046900)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81046900-ffffffff81046a04: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056b20)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81056b20-ffffffff81056c24: find_microcode_in_initrd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct cpio_data find_microcode_in_initrd(const char *path, bool use_pa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81057fc0)
Location: arch/x86/kernel/cpu/microcode/core.c:257
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
  - arch/x86/kernel/cpu/microcode/amd.c:__load_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:save_microcode_in_initrd_amd
```
**Symbols:**

```
ffffffff81057fc0-ffffffff810580c4: find_microcode_in_initrd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool use_pa</code>
</li>
</ul>
</details>
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
