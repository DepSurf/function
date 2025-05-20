# Function: <code>stop_this_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039630)
Location: arch/x86/kernel/process.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_stop_nmi_callback
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff81039630-ffffffff81039670: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038610)
Location: arch/x86/kernel/process.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_stop_nmi_callback
```
**Symbols:**

```
ffffffff81038610-ffffffff81038655: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81037fe0)
Location: arch/x86/kernel/process.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
  - arch/x86/kernel/smp.c:smp_stop_nmi_callback
```
**Symbols:**

```
ffffffff81037fe0-ffffffff81038024: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81036170)
Location: arch/x86/kernel/process.c:358
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff81036170-ffffffff810361b4: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81038500)
Location: arch/x86/kernel/process.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff81038500-ffffffff8103854c: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81039a20)
Location: arch/x86/kernel/process.c:518
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff81039a20-ffffffff81039a6c: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103af50)
Location: arch/x86/kernel/process.c:582
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103af50-ffffffff8103af9c: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103d560)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103d560-ffffffff8103d5ba: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dd20)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103dd20-ffffffff8103dd76: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040de0)
Location: arch/x86/kernel/process.c:705
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81040de0-ffffffff81040e34: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040d40)
Location: arch/x86/kernel/process.c:705
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81040d40-ffffffff81040d94: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81042740)
Location: arch/x86/kernel/process.c:717
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81042740-ffffffff81042794: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81048a90)
Location: arch/x86/kernel/process.c:734
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81048a90-ffffffff81048ae1: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81051d20)
Location: arch/x86/kernel/process.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81051d20-ffffffff81051daf: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8105f3f0)
Location: arch/x86/kernel/process.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff8105f3f0-ffffffff8105f47e: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81060ae0)
Location: arch/x86/kernel/process.c:784
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81060ae0-ffffffff81060b86: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81067b90)
Location: arch/x86/kernel/process.c:796
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:__sysvec_reboot
```
**Symbols:**

```
ffffffff81067b90-ffffffff81067c36: stop_this_cpu (STB_GLOBAL)
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
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dea0)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103dea0-ffffffff8103def6: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8102d6c0)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8102d6c0-ffffffff8102d710: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103dce0)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103dce0-ffffffff8103dd36: stop_this_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void stop_this_cpu(void *dummy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff8103ee40)
Location: arch/x86/kernel/process.c:598
Inline: False
Direct callers:
  - arch/x86/kernel/reboot.c:native_machine_halt
  - arch/x86/kernel/smp.c:smp_reboot_interrupt
```
**Symbols:**

```
ffffffff8103ee40-ffffffff8103ee96: stop_this_cpu (STB_GLOBAL)
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
