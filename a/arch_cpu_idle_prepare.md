# Function: <code>arch_cpu_idle_prepare</code>

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
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (0)
Location: kernel/sched/idle.c:72
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810c79c0-ffffffff810c79cb: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (0)
Location: kernel/sched/idle.c:75
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810cd8a0-ffffffff810cd8ab: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ca2b0)
Location: kernel/sched/idle.c:77
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810ca2b0-ffffffff810ca2bb: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d1ad0)
Location: kernel/sched/idle.c:77
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810d1ad0-ffffffff810d1adb: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c41d0)
Location: kernel/sched/idle.c:72
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810c41d0-ffffffff810c41db: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810cd490)
Location: kernel/sched/idle.c:72
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810cd490-ffffffff810cd49b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d5880)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810d5880-ffffffff810d588b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810dfe90)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810dfe90-ffffffff810dfe9b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e8190)
Location: kernel/sched/idle.c:73
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810e8190-ffffffff810e819b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e5db0)
Location: kernel/sched/idle.c:74
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810e5db0-ffffffff810e5dbb: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e7d70)
Location: kernel/sched/idle.c:74
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810e7d70-ffffffff810e7d7b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810ff420)
Location: kernel/sched/idle.c:74
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810ff420-ffffffff810ff42b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133470)
Location: kernel/sched/idle.c:71
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff81133470-ffffffff8113347f: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115d7e0)
Location: kernel/sched/idle.c:71
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8115d7e0-ffffffff8115d7ef: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116df30)
Location: kernel/sched/idle.c:75
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8116df30-ffffffff8116df3f: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117b4f0)
Location: kernel/sched/idle.c:75
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff8117b4f0-ffffffff8117b4ff: arch_cpu_idle_prepare (STB_WEAK)
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
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffff80001013fb68)
Location: kernel/sched/idle.c:73
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffff80001013fb68-ffff80001013fb80: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/process.c (c030af70)
Location: arch/arm/kernel/process.c:75
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
c030af70-c030af8c: arch_cpu_idle_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (c00000000018ebc0)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
c00000000018ebc0-c00000000018ebcc: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffe0000edeb0)
Location: kernel/sched/idle.c:73
Inline: True
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffe0000edeb0-ffffffe0000edeca: arch_cpu_idle_prepare (STB_WEAK)
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
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810da080)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810da080-ffffffff810da08b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810c9070)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810c9070-ffffffff810c907b: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810d63c0)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810d63c0-ffffffff810d63cb: arch_cpu_idle_prepare (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void arch_cpu_idle_prepare();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/idle.c (ffffffff810e1cc0)
Location: kernel/sched/idle.c:73
Inline: False
Direct callers:
  - kernel/sched/idle.c:cpu_startup_entry
```
**Symbols:**

```
ffffffff810e1cc0-ffffffff810e1ccb: arch_cpu_idle_prepare (STB_WEAK)
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
