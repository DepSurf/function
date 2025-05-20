# Function: <code>cpuhp_online_idle</code>

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
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084c10)
Location: kernel/cpu.c:907
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff81084c10-ffffffff81084c81: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089ba0)
Location: kernel/cpu.c:865
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff81089ba0-ffffffff81089c13: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086aa0)
Location: kernel/cpu.c:787
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff81086aa0-ffffffff81086ad3: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d850)
Location: kernel/cpu.c:971
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8108d850-ffffffff8108d883: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810913e0)
Location: kernel/cpu.c:1057
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810913e0-ffffffff81091413: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810996c0)
Location: kernel/cpu.c:1073
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810996c0-ffffffff810996f3: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109da10)
Location: kernel/cpu.c:1085
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8109da10-ffffffff8109da42: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3f50)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810a3f50-ffffffff810a3f92: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ab110)
Location: kernel/cpu.c:1171
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810ab110-ffffffff810ab158: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a69a0)
Location: kernel/cpu.c:1175
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810a69a0-ffffffff810a69e8: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a7a50)
Location: kernel/cpu.c:1278
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810a7a50-ffffffff810a7a98: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b94b0)
Location: kernel/cpu.c:1304
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810b94b0-ffffffff810b94f8: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cfec0)
Location: kernel/cpu.c:1316
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810cfec0-ffffffff810cff14: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee2f0)
Location: kernel/cpu.c:1340
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810ee2f0-ffffffff810ee344: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa330)
Location: kernel/cpu.c:1614
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810fa330-ffffffff810fa3a2: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103750)
Location: kernel/cpu.c:1652
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff81103750-ffffffff811037c2: cpuhp_online_idle (STB_GLOBAL)
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
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9a58)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffff8000100f9a58-ffff8000100f9ac8: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357c98)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
c0357c98-c0357cf0: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140a00)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
c000000000140a00-c000000000140a94: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c4056)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffe0000c4056-ffffffe0000c40c6: cpuhp_online_idle (STB_GLOBAL)
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
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d870)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8109d870-ffffffff8109d8b2: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c290)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8108c290-ffffffff8108c2d2: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d820)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8109d820-ffffffff8109d862: cpuhp_online_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuhp_online_idle(enum cpuhp_state state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a56b0)
Location: kernel/cpu.c:1094
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_play_dead
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810a56b0-ffffffff810a56f2: cpuhp_online_idle (STB_GLOBAL)
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
