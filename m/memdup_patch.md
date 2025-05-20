# Function: <code>memdup_patch</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053490)
Location: arch/x86/kernel/cpu/microcode/intel.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81053490-ffffffff810534f1: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056130)
Location: arch/x86/kernel/cpu/microcode/intel.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056130-ffffffff81056191: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053570)
Location: arch/x86/kernel/cpu/microcode/intel.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81053570-ffffffff810535d1: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056740)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056740-ffffffff810567a1: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056ff0)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056ff0-ffffffff81057051: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c3c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105c3c0-ffffffff8105c421: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ac30)
Location: arch/x86/kernel/cpu/microcode/intel.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105ac30-ffffffff8105ac91: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b5e0)
Location: arch/x86/kernel/cpu/microcode/intel.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff8105b5e0-ffffffff8105b641: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064bc0)
Location: arch/x86/kernel/cpu/microcode/intel.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81064bc0-ffffffff81064c21: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071590)
Location: arch/x86/kernel/cpu/microcode/intel.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81071590-ffffffff81071603: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81081470)
Location: arch/x86/kernel/cpu/microcode/intel.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81081470-ffffffff810814e3: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810839a0)
Location: arch/x86/kernel/cpu/microcode/intel.c:61
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff810839a0-ffffffff81083a13: memdup_patch (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056b70)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056b70-ffffffff81056bd1: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81046d80)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81046d80-ffffffff81046de1: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056fa0)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81056fa0-ffffffff81057001: memdup_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ucode_patch *memdup_patch(void *data, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058440)
Location: arch/x86/kernel/cpu/microcode/intel.c:150
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
  - arch/x86/kernel/cpu/microcode/intel.c:save_microcode_patch
```
**Symbols:**

```
ffffffff81058440-ffffffff810584a1: memdup_patch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
