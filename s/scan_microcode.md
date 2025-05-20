# Function: <code>scan_microcode</code>

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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81f6d1ed)
Location: arch/x86/kernel/cpu/microcode/intel.c:543
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81f954e9)
Location: arch/x86/kernel/cpu/microcode/intel.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:load_ucode_intel_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050090)
Location: arch/x86/kernel/cpu/microcode/intel.c:310
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81050090-ffffffff810502ad: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81050100)
Location: arch/x86/kernel/cpu/microcode/intel.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81050100-ffffffff81050330: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053b30)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81053b30-ffffffff81053d60: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810567b0)
Location: arch/x86/kernel/cpu/microcode/intel.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff810567b0-ffffffff810569ae: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053e40)
Location: arch/x86/kernel/cpu/microcode/intel.c:330
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81053e40-ffffffff81054039: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057040)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057040-ffffffff81057241: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057910)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057910-ffffffff81057b11: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105cbd0)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105cbd0-ffffffff8105ccd5: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b450)
Location: arch/x86/kernel/cpu/microcode/intel.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105b450-ffffffff8105b540: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105be00)
Location: arch/x86/kernel/cpu/microcode/intel.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff8105be00-ffffffff8105bef0: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81065480)
Location: arch/x86/kernel/cpu/microcode/intel.c:283
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81065480-ffffffff81065570: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071f90)
Location: arch/x86/kernel/cpu/microcode/intel.c:269
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81071f90-ffffffff81072094: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081c90)
Location: arch/x86/kernel/cpu/microcode/intel.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81081c90-ffffffff81081dc8: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810841d0)
Location: arch/x86/kernel/cpu/microcode/intel.c:143
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff810841d0-ffffffff81084308: scan_microcode (STB_LOCAL)
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
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff838d65b7)
Location: arch/x86/kernel/cpu/microcode/intel.c:261
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/intel.c:get_microcode_blob
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
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057490)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81057490-ffffffff81057691: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047680)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81047680-ffffffff81047881: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810578c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff810578c0-ffffffff81057ac1: scan_microcode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct microcode_intel *scan_microcode(void *data, size_t size, struct ucode_cpu_info *uci, bool save);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058d60)
Location: arch/x86/kernel/cpu/microcode/intel.c:327
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:__load_ucode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_in_initrd_intel
```
**Symbols:**

```
ffffffff81058d60-ffffffff81058f61: scan_microcode (STB_LOCAL)
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
