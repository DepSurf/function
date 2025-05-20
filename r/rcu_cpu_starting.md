# Function: <code>rcu_cpu_starting</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5d70)
Location: kernel/rcu/tree.c:3866
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff810f5d70-ffffffff810f5de6: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f6a50)
Location: kernel/rcu/tree.c:3881
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff810f6a50-ffffffff810f6ad4: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811008f0)
Location: kernel/rcu/tree.c:3894
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811008f0-ffffffff8110099c: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81108740)
Location: kernel/rcu/tree.c:3681
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81108740-ffffffff8110880d: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113b70)
Location: kernel/rcu/tree.c:3385
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81113b70-ffffffff81113c85: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d790)
Location: kernel/rcu/tree.c:3068
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8111d790-ffffffff8111d89f: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81129d30)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81129d30-ffffffff81129e3f: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81138170)
Location: kernel/rcu/tree.c:3844
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81138170-ffffffff81138298: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811339d0)
Location: kernel/rcu/tree.c:4155
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811339d0-ffffffff81133b2e: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81134660)
Location: kernel/rcu/tree.c:4267
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81134660-ffffffff811347be: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4238
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81caf616-ffffffff81caf62b: rcu_cpu_starting.cold (STB_LOCAL)
ffffffff81156d70-ffffffff81156efe: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4365
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81e602ba-ffffffff81e602cf: rcu_cpu_starting.cold (STB_LOCAL)
ffffffff8117fd90-ffffffff8117ffb8: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4259
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8205a35a-ffffffff8205a36f: rcu_cpu_starting.cold (STB_LOCAL)
ffffffff811ba280-ffffffff811ba490: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4418
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:start_secondary
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff820d8b88-ffffffff820d8b9d: rcu_cpu_starting.cold (STB_LOCAL)
ffffffff811ccbe0-ffffffff811ccdd0: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010191998)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffff800010191998-ffff800010191b38: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03df568)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c03df568-c03df680: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ecfb0)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
c0000000001ecfb0-c0000000001ed160: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124c64)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffe000124c64-ffffffe000124d8c: rcu_cpu_starting (STB_GLOBAL)
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
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81122310)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81122310-ffffffff8112241f: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811149c0)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff811149c0-ffffffff81114acf: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81120200)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81120200-ffffffff8112030f: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c440)
Location: kernel/rcu/tree.c:3123
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_ap_init
  - kernel/cpu.c:notify_cpu_starting
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8112c440-ffffffff8112c54f: rcu_cpu_starting (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
