# Function: <code>arch_kexec_protect_crashkres</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c510)
Location: arch/x86/kernel/machine_kexec_64.c:577
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105c510-ffffffff8105c525: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f490)
Location: arch/x86/kernel/machine_kexec_64.c:578
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105f490-ffffffff8105f4a5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105eb60)
Location: arch/x86/kernel/machine_kexec_64.c:596
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff8105eb60-ffffffff8105eb75: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810628a0)
Location: arch/x86/kernel/machine_kexec_64.c:599
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:SyS_kexec_file_load
```
**Symbols:**

```
ffffffff810628a0-ffffffff810628b5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81065800)
Location: arch/x86/kernel/machine_kexec_64.c:549
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81065800-ffffffff81065815: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106b4d0)
Location: arch/x86/kernel/machine_kexec_64.c:549
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106b4d0-ffffffff8106b4e5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106efc0)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106efc0-ffffffff8106efd5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81070570)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81070570-ffffffff81070585: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810778c0)
Location: arch/x86/kernel/machine_kexec_64.c:580
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810778c0-ffffffff810778d5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81077ef0)
Location: arch/x86/kernel/machine_kexec_64.c:580
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81077ef0-ffffffff81077f05: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81078980)
Location: arch/x86/kernel/machine_kexec_64.c:580
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81078980-ffffffff81078995: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810861d0)
Location: arch/x86/kernel/machine_kexec_64.c:551
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810861d0-ffffffff810861e5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810965e0)
Location: arch/x86/kernel/machine_kexec_64.c:560
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810965e0-ffffffff810965fb: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810ac300)
Location: arch/x86/kernel/machine_kexec_64.c:560
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810ac300-ffffffff810ac31b: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afe30)
Location: arch/x86/kernel/machine_kexec_64.c:549
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810afe30-ffffffff810afe4b: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b69c0)
Location: arch/x86/kernel/machine_kexec_64.c:546
Inline: False
Direct callers:
  - kernel/crash_core.c:crash_handle_hotplug_event
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff810b69c0-ffffffff810b69db: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/machine_kexec.c (ffff8000100aa088)
Location: arch/arm64/kernel/machine_kexec.c:275
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__arm64_sys_kexec_file_load
```
**Symbols:**

```
ffff8000100aa088-ffff8000100aa110: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0410dec)
Location: kernel/kexec_core.c:1211
Inline: True
Direct callers:
  - kernel/kexec.c:do_kexec_load
```
**Symbols:**

```
c0410dec-c0410e04: arch_kexec_protect_crashkres (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (c0000000002329e0)
Location: kernel/kexec_core.c:1211
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
**Symbols:**

```
c0000000002329e0-c0000000002329ec: arch_kexec_protect_crashkres (STB_WEAK)
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
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f510)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106f510-ffffffff8106f525: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f8e0)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8105f8e0-ffffffff8105f8f5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8106f9c0)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8106f9c0-ffffffff8106f9d5: arch_kexec_protect_crashkres (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_kexec_protect_crashkres();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81071c40)
Location: arch/x86/kernel/machine_kexec_64.c:647
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__ia32_sys_kexec_file_load
  - kernel/kexec_file.c:__x64_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81071c40-ffffffff81071c55: arch_kexec_protect_crashkres (STB_GLOBAL)
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
