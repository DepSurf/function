# Function: <code>mce_cpu_online</code>

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
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81047f20)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2560
Inline: False
```
**Symbols:**

```
ffffffff81047f20-ffffffff8104818d: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810477e0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2271
Inline: False
```
**Symbols:**

```
ffffffff810477e0-ffffffff81047a61: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104b2a0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2300
Inline: False
```
**Symbols:**

```
ffffffff8104b2a0-ffffffff8104b527: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104dbe0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2293
Inline: False
```
**Symbols:**

```
ffffffff8104dbe0-ffffffff8104de7d: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104b2d0)
Location: arch/x86/kernel/cpu/mce/core.c:2316
Inline: False
```
**Symbols:**

```
ffffffff8104b2d0-ffffffff8104b568: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104e1c0)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8104e1c0-ffffffff8104e490: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eb60)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8104eb60-ffffffff8104ee30: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81053070)
Location: arch/x86/kernel/cpu/mce/core.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81053070-ffffffff810530f1: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810521c0)
Location: arch/x86/kernel/cpu/mce/core.c:2576
Inline: False
```
**Symbols:**

```
ffffffff810521c0-ffffffff81052241: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810538f0)
Location: arch/x86/kernel/cpu/mce/core.c:2587
Inline: False
```
**Symbols:**

```
ffffffff810538f0-ffffffff81053a25: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2650
Inline: False
```
**Symbols:**

```
ffffffff8105c1d0-ffffffff8105c31d: mce_cpu_online (STB_LOCAL)
ffffffff81c9b7a9-ffffffff81c9b7ec: mce_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2662
Inline: False
```
**Symbols:**

```
ffffffff810686a0-ffffffff81068842: mce_cpu_online (STB_LOCAL)
ffffffff81e4acaa-ffffffff81e4acdf: mce_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2662
Inline: False
```
**Symbols:**

```
ffffffff81078260-ffffffff81078300: mce_cpu_online (STB_LOCAL)
ffffffff82052dcf-ffffffff82052de3: mce_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2679
Inline: False
```
**Symbols:**

```
ffffffff8107a510-ffffffff8107a5b0: mce_cpu_online (STB_LOCAL)
ffffffff820d12fe-ffffffff820d1312: mce_cpu_online.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2703
Inline: False
```
**Symbols:**

```
ffffffff81081a40-ffffffff81081ae0: mce_cpu_online (STB_LOCAL)
ffffffff821abe51-ffffffff821abe65: mce_cpu_online.cold (STB_LOCAL)
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
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ecc0)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8104ecc0-ffffffff8104ef90: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8103e190)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8103e190-ffffffff8103e472: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104eb10)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8104eb10-ffffffff8104ede0: mce_cpu_online (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mce_cpu_online(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8104ff50)
Location: arch/x86/kernel/cpu/mce/core.c:2372
Inline: False
```
**Symbols:**

```
ffffffff8104ff50-ffffffff81050220: mce_cpu_online (STB_LOCAL)
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
