# Function: <code>arch_kexec_unprotect_crashkres</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c530)
Location: arch/x86/kernel/machine_kexec_64.c:582
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105c530-ffffffff8105c542: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f4b0)
Location: arch/x86/kernel/machine_kexec_64.c:583
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105f4b0-ffffffff8105f4c2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb80)
Location: arch/x86/kernel/machine_kexec_64.c:601
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105eb80-ffffffff8105eb92: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810628c0)
Location: arch/x86/kernel/machine_kexec_64.c:604
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff810628c0-ffffffff810628d2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065820)
Location: arch/x86/kernel/machine_kexec_64.c:554
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81065820-ffffffff81065832: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b4f0)
Location: arch/x86/kernel/machine_kexec_64.c:554
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106b4f0-ffffffff8106b502: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106efe0)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106efe0-ffffffff8106eff2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070590)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81070590-ffffffff810705a2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810778e0)
Location: arch/x86/kernel/machine_kexec_64.c:585
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810778e0-ffffffff810778f2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077f10)
Location: arch/x86/kernel/machine_kexec_64.c:585
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81077f10-ffffffff81077f22: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810789a0)
Location: arch/x86/kernel/machine_kexec_64.c:585
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810789a0-ffffffff810789b2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810861f0)
Location: arch/x86/kernel/machine_kexec_64.c:556
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810861f0-ffffffff81086202: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81096600)
Location: arch/x86/kernel/machine_kexec_64.c:565
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81096600-ffffffff81096618: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ac330)
Location: arch/x86/kernel/machine_kexec_64.c:565
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810ac330-ffffffff810ac348: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afe60)
Location: arch/x86/kernel/machine_kexec_64.c:554
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810afe60-ffffffff810afe78: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b69f0)
Location: arch/x86/kernel/machine_kexec_64.c:551
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810b69f0-ffffffff810b6a08: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/machine_kexec.c (ffff8000100aa110)
Location: arch/arm64/kernel/machine_kexec.c:287
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000100aa110-ffff8000100aa190: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (0)
Location: kernel/kexec_core.c:1214
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
c0410e04-c0410e1c: arch_kexec_unprotect_crashkres (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0000000002329f0)
Location: kernel/kexec_core.c:1214
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c0000000002329f0-c0000000002329fc: arch_kexec_unprotect_crashkres (STB_WEAK)
```
</details>
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
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f530)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106f530-ffffffff8106f542: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f900)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8105f900-ffffffff8105f912: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f9e0)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106f9e0-ffffffff8106f9f2: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_kexec_unprotect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071c60)
Location: arch/x86/kernel/machine_kexec_64.c:652
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81071c60-ffffffff81071c72: arch_kexec_unprotect_crashkres (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
