# Function: <code>cpu_startup_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c3d80)
Location: kernel/sched/idle.c:281
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c3d80-ffffffff810c40c8: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c7a60)
Location: kernel/sched/idle.c:274
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c7a60-ffffffff810c7da3: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cdd20)
Location: kernel/sched/idle.c:325
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp.c:xen_play_dead
  - arch/x86/xen/smp.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810cdd20-ffffffff810cdd93: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca680)
Location: kernel/sched/idle.c:331
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810ca680-ffffffff810ca6f5: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d1e90)
Location: kernel/sched/idle.c:331
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d1e90-ffffffff810d1f05: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c4620)
Location: kernel/sched/idle.c:348
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c4620-ffffffff810c4695: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd8e0)
Location: kernel/sched/idle.c:348
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810cd8e0-ffffffff810cd8ff: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d5cd0)
Location: kernel/sched/idle.c:349
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d5cd0-ffffffff810d5cf2: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e02d0)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e02d0-ffffffff810e02f2: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e8630)
Location: kernel/sched/idle.c:367
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e8630-ffffffff810e8652: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e6240)
Location: kernel/sched/idle.c:392
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e6240-ffffffff810e6262: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e8210)
Location: kernel/sched/idle.c:398
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e8210-ffffffff810e8232: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff8d0)
Location: kernel/sched/idle.c:398
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810ff8d0-ffffffff810ff8f2: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133940)
Location: kernel/sched/idle.c:395
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81133940-ffffffff8113395f: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115dd90)
Location: kernel/sched/idle.c:395
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8115dd90-ffffffff8115ddaf: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e470)
Location: kernel/sched/idle.c:374
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8116e470-ffffffff8116e48f: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117ba30)
Location: kernel/sched/idle.c:404
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff8117ba30-ffffffff8117ba5c: cpu_startup_entry (STB_GLOBAL)
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
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff800010140040)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/arm64/kernel/smp.c:secondary_start_kernel
  - arch/arm64/kernel/smp.c:secondary_start_kernel
```
**Symbols:**

```
ffff800010140040-ffff800010140070: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c0390098)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/arm/kernel/smp.c:secondary_start_kernel
```
**Symbols:**

```
c0390098-c03900c4: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018f280)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/powerpc/kernel/smp.c:start_secondary
```
**Symbols:**

```
c00000000018f280-c00000000018f2c0: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000ee188)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/riscv/kernel/smpboot.c:smp_callin
```
**Symbols:**

```
ffffffe0000ee188-ffffffe0000ee1ba: cpu_startup_entry (STB_GLOBAL)
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
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810da480)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810da480-ffffffff810da4a2: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c9490)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c9490-ffffffff810c94b2: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d6800)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d6800-ffffffff810d6822: cpu_startup_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_startup_entry(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e2110)
Location: kernel/sched/idle.c:350
Inline: False
Direct callers:
  - init/main.c:rest_init
  - arch/x86/xen/smp_pv.c:cpu_bringup_and_idle
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e2110-ffffffff810e2132: cpu_startup_entry (STB_GLOBAL)
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
