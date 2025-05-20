# Function: <code>native_write_cr0</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064500)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81064500-ffffffff81064509: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81064150)
Location: arch/x86/include/asm/special_insns.h:30
Inline: False
```
**Symbols:**

```
ffffffff81064150-ffffffff81064159: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067640)
Location: arch/x86/include/asm/special_insns.h:25
Inline: False
```
**Symbols:**

```
ffffffff81067640-ffffffff81067649: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81066900)
Location: arch/x86/include/asm/special_insns.h:25
Inline: False
```
**Symbols:**

```
ffffffff81066900-ffffffff81066909: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106aad0)
Location: arch/x86/include/asm/special_insns.h:26
Inline: False
```
**Symbols:**

```
ffffffff8106aad0-ffffffff8106aad9: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8106d7b0)
Location: arch/x86/include/asm/special_insns.h:26
Inline: False
```
**Symbols:**

```
ffffffff8106d7b0-ffffffff8106d7b9: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073950)
Location: arch/x86/include/asm/special_insns.h:26
Inline: False
```
**Symbols:**

```
ffffffff81073950-ffffffff81073959: native_write_cr0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81045a20)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
```
**Symbols:**

```
ffffffff81045a20-ffffffff81045a6a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046170)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
```
**Symbols:**

```
ffffffff81046170-ffffffff810461ba: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81049e50)
Location: arch/x86/kernel/cpu/common.c:356
Inline: False
```
**Symbols:**

```
ffffffff81049e50-ffffffff81049e9a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810492f0)
Location: arch/x86/kernel/cpu/common.c:358
Inline: False
```
**Symbols:**

```
ffffffff810492f0-ffffffff8104933a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8104abc0)
Location: arch/x86/kernel/cpu/common.c:357
Inline: False
```
**Symbols:**

```
ffffffff8104abc0-ffffffff8104ac0a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051d55)
Location: arch/x86/kernel/cpu/common.c:365
Inline: True
```
**Symbols:**

```
ffffffff81c9a9c9-ffffffff81c9a9dd: native_write_cr0.cold (STB_LOCAL)
ffffffff81051d40-ffffffff81051d9a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:421
Inline: False
```
**Symbols:**

```
ffffffff81e49e21-ffffffff81e49e35: native_write_cr0.cold (STB_LOCAL)
ffffffff8105d390-ffffffff8105d3fc: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:422
Inline: False
```
**Symbols:**

```
ffffffff820528a0-ffffffff820528b4: native_write_cr0.cold (STB_LOCAL)
ffffffff8106b810-ffffffff8106b87c: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d36f)
Location: arch/x86/kernel/cpu/common.c:410
Inline: True
```
**Symbols:**

```
ffffffff820d0d6f-ffffffff820d0d83: native_write_cr0.cold (STB_LOCAL)
ffffffff8106d350-ffffffff8106d3be: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8107445f)
Location: arch/x86/kernel/cpu/common.c:391
Inline: True
```
**Symbols:**

```
ffffffff821ab893-ffffffff821ab8a7: native_write_cr0.cold (STB_LOCAL)
ffffffff81074440-ffffffff810744ae: native_write_cr0 (STB_GLOBAL)
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
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810462f0)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
```
**Symbols:**

```
ffffffff810462f0-ffffffff8104633a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81035620)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
Direct callers:
  - arch/x86/kernel/traps.c:do_device_not_available
  - arch/x86/kernel/fpu/init.c:fpu__init_system
  - arch/x86/kernel/fpu/init.c:fpu__init_cpu_generic
  - arch/x86/kernel/cpu/mtrr/generic.c:post_set
  - arch/x86/kernel/cpu/mtrr/generic.c:prepare_set
  - arch/x86/power/cpu.c:restore_processor_state
```
**Symbols:**

```
ffffffff81035620-ffffffff8103566a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81046130)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
```
**Symbols:**

```
ffffffff81046130-ffffffff8104617a: native_write_cr0 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void native_write_cr0(long unsigned int val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81047530)
Location: arch/x86/kernel/cpu/common.c:372
Inline: True
```
**Symbols:**

```
ffffffff81047530-ffffffff8104757a: native_write_cr0 (STB_GLOBAL)
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
