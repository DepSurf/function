# Function: <code>cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810819d0)
Location: kernel/cpu.c:537
Inline: True
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810819d0-ffffffff81081a64: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084930)
Location: kernel/cpu.c:1018
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff81084930-ffffffff81084945: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810898c0)
Location: kernel/cpu.c:976
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810898c0-ffffffff810898d5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085d80)
Location: kernel/cpu.c:888
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff81085d80-ffffffff81085d95: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108caa0)
Location: kernel/cpu.c:1072
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff8108caa0-ffffffff8108cab5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090450)
Location: kernel/cpu.c:1162
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff81090450-ffffffff81090465: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810991e0)
Location: kernel/cpu.c:1179
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810991e0-ffffffff810991f5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d760)
Location: kernel/cpu.c:1191
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff8109d760-ffffffff8109d775: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3ca0)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810a3ca0-ffffffff810a3cb5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810aac93)
Location: kernel/cpu.c:1249
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810aac40-ffffffff810aacfe: cpu_up (STB_LOCAL)
ffffffff810ab868-ffffffff810ab881: cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810a6523)
Location: kernel/cpu.c:1253
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810a64d0-ffffffff810a658e: cpu_up (STB_LOCAL)
ffffffff81bdb4d9-ffffffff81bdb4f2: cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810a7593)
Location: kernel/cpu.c:1357
Inline: True
Direct callers:
  - kernel/cpu.c:write_cpuhp_target
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810a7540-ffffffff810a75fe: cpu_up (STB_LOCAL)
ffffffff81bcd5cb-ffffffff81bcd5e4: cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810b8f95)
Location: kernel/cpu.c:1383
Inline: True
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810b8f30-ffffffff810b9017: cpu_up (STB_LOCAL)
ffffffff81ca3ef7-ffffffff81ca3f10: cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (ffffffff810cf8ed)
Location: kernel/cpu.c:1395
Inline: True
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810cf880-ffffffff810cf975: cpu_up (STB_LOCAL)
ffffffff81e53766-ffffffff81e5377f: cpu_up.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810edc30)
Location: kernel/cpu.c:1419
Inline: True
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:bringup_nonboot_cpus
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810edc30-ffffffff810edd3e: cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9d20)
Location: kernel/cpu.c:1701
Inline: True
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff810f9d20-ffffffff810f9e2c: cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpu_up(unsigned int cpu, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103130)
Location: kernel/cpu.c:1739
Inline: True
Direct callers:
  - kernel/cpu.c:target_store
  - kernel/cpu.c:cpuhp_bringup_mask
  - kernel/cpu.c:bringup_hibernate_cpu
  - kernel/cpu.c:cpu_device_up
```
**Symbols:**

```
ffffffff81103130-ffffffff81103250: cpu_up (STB_LOCAL)
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
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9688)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffff8000100f9688-ffff8000100f96b8: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357924)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
c0357924-c0357944: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140520)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/powerpc/kernel/machine_kexec_64.c:default_machine_kexec
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
c000000000140520-c000000000140538: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c3e0c)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - kernel/smp.c:smp_init
```
**Symbols:**

```
ffffffe0000c3e0c-ffffffe0000c3fa8: cpu_up (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d5c0)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff8109d5c0-ffffffff8109d5d5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bfe0)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff8108bfe0-ffffffff8108bff5: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d570)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff8109d570-ffffffff8109d585: cpu_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_up(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a53f0)
Location: kernel/cpu.c:1206
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - kernel/smp.c:smp_init
  - drivers/base/cpu.c:cpu_subsys_online
```
**Symbols:**

```
ffffffff810a53f0-ffffffff810a5405: cpu_up (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state target</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
