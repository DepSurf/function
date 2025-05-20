# Function: <code>native_cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051a50)
Location: arch/x86/kernel/smpboot.c:1065
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
```
**Symbols:**

```
ffffffff81051a50-ffffffff81052437: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051be0)
Location: arch/x86/kernel/smpboot.c:1077
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
```
**Symbols:**

```
ffffffff81051be0-ffffffff81052502: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810544c0)
Location: arch/x86/kernel/smpboot.c:1090
Inline: False
```
**Symbols:**

```
ffffffff810544c0-ffffffff81054e0a: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053e10)
Location: arch/x86/kernel/smpboot.c:1087
Inline: False
```
**Symbols:**

```
ffffffff81053e10-ffffffff81054730: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057bc0)
Location: arch/x86/kernel/smpboot.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81057bc0-ffffffff81058529: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1072
Inline: False
```
**Symbols:**

```
ffffffff8105b7e3-ffffffff8105b8b6: native_cpu_up.cold.10 (STB_LOCAL)
ffffffff8105a910-ffffffff8105b1a7: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1073
Inline: False
```
**Symbols:**

```
ffffffff8106146d-ffffffff81061540: native_cpu_up.cold.12 (STB_LOCAL)
ffffffff81060590-ffffffff81060e27: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1132
Inline: False
```
**Symbols:**

```
ffffffff81064bcb-ffffffff81064c08: native_cpu_up.cold (STB_LOCAL)
ffffffff81064260-ffffffff8106442a: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1127
Inline: False
```
**Symbols:**

```
ffffffff81065238-ffffffff81065275: native_cpu_up.cold (STB_LOCAL)
ffffffff810648e0-ffffffff81064aaa: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1140
Inline: False
```
**Symbols:**

```
ffffffff8106bb29-ffffffff8106bb66: native_cpu_up.cold (STB_LOCAL)
ffffffff8106b240-ffffffff8106b43e: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1134
Inline: False
```
**Symbols:**

```
ffffffff81bd6a96-ffffffff81bd6ad3: native_cpu_up.cold (STB_LOCAL)
ffffffff8106ced0-ffffffff8106d0aa: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1135
Inline: False
```
**Symbols:**

```
ffffffff81bc8c70-ffffffff81bc8cad: native_cpu_up.cold (STB_LOCAL)
ffffffff8106d960-ffffffff8106db42: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1137
Inline: False
```
**Symbols:**

```
ffffffff81c9d616-ffffffff81c9d653: native_cpu_up.cold (STB_LOCAL)
ffffffff81079160-ffffffff81079360: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1188
Inline: False
```
**Symbols:**

```
ffffffff81e4cab3-ffffffff81e4caee: native_cpu_up.cold (STB_LOCAL)
ffffffff81087fa0-ffffffff81088191: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109b950)
Location: arch/x86/kernel/smpboot.c:1186
Inline: False
```
**Symbols:**

```
ffffffff8109b950-ffffffff8109bb6b: native_cpu_up (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1127
Inline: False
```
**Symbols:**

```
ffffffff81064d28-ffffffff81064d65: native_cpu_up.cold (STB_LOCAL)
ffffffff810643d0-ffffffff8106459a: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1127
Inline: False
```
**Symbols:**

```
ffffffff81054ffd-ffffffff8105503a: native_cpu_up.cold (STB_LOCAL)
ffffffff810546d0-ffffffff81054886: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1127
Inline: False
```
**Symbols:**

```
ffffffff810651d8-ffffffff81065215: native_cpu_up.cold (STB_LOCAL)
ffffffff81064880-ffffffff81064a4a: native_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int native_cpu_up(unsigned int cpu, struct task_struct *tidle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:1127
Inline: False
```
**Symbols:**

```
ffffffff810667b8-ffffffff810667f5: native_cpu_up.cold (STB_LOCAL)
ffffffff81065e60-ffffffff8106602a: native_cpu_up (STB_GLOBAL)
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
