# Function: <code>common_cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051a00)
Location: arch/x86/kernel/smpboot.c:920
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81051a00-ffffffff81051a49: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051b90)
Location: arch/x86/kernel/smpboot.c:932
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_cpu_up
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81051b90-ffffffff81051bd9: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810545c3)
Location: arch/x86/kernel/smpboot.c:948
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff81054480-ffffffff810544bf: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053f16)
Location: arch/x86/kernel/smpboot.c:951
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff81053dd0-ffffffff81053e0f: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057cc9)
Location: arch/x86/kernel/smpboot.c:888
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff81057b80-ffffffff81057bbf: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105a9ed)
Location: arch/x86/kernel/smpboot.c:941
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff8105a8d0-ffffffff8105a90f: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106066d)
Location: arch/x86/kernel/smpboot.c:942
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff81060550-ffffffff8106058f: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064210)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81064210-ffffffff8106425e: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064890)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81064890-ffffffff810648de: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b34a)
Location: arch/x86/kernel/smpboot.c:1007
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106b1f0-ffffffff8106b23e: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106ce60)
Location: arch/x86/kernel/smpboot.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106ce60-ffffffff8106cecb: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d8f0)
Location: arch/x86/kernel/smpboot.c:1001
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8106d8f0-ffffffff8106d95b: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81079080)
Location: arch/x86/kernel/smpboot.c:1003
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81079080-ffffffff81079152: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81087ec0)
Location: arch/x86/kernel/smpboot.c:1046
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81087ec0-ffffffff81087f9c: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109b860)
Location: arch/x86/kernel/smpboot.c:1044
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8109b860-ffffffff8109b93c: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109cb39)
Location: arch/x86/kernel/smpboot.c:1002
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff8109e8d0-ffffffff8109e96d: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a406f)
Location: arch/x86/kernel/smpboot.c:968
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_kick_ap
```
**Symbols:**

```
ffffffff810a5dd0-ffffffff810a5e6d: common_cpu_up (STB_GLOBAL)
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
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064380)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81064380-ffffffff810643ce: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81054680)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81054680-ffffffff810546ce: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064830)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81064830-ffffffff8106487e: common_cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int common_cpu_up(unsigned int cpu, struct task_struct *idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81065e10)
Location: arch/x86/kernel/smpboot.c:994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81065e10-ffffffff81065e5e: common_cpu_up (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
