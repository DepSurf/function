# Function: <code>init_cpu_possible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81082010)
Location: kernel/cpu.c:821
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81082010-ffffffff81082046: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085070)
Location: kernel/cpu.c:1752
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81085070-ffffffff810850a6: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108a000)
Location: kernel/cpu.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8108a000-ffffffff8108a02c: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810870d0)
Location: kernel/cpu.c:1760
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810870d0-ffffffff81087113: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108de40)
Location: kernel/cpu.c:1994
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8108de40-ffffffff8108de83: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2238
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109197f-ffffffff8109198b: init_cpu_possible.cold.23 (STB_LOCAL)
ffffffff810916e0-ffffffff8109171b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2260
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81099c5f-ffffffff81099c6b: init_cpu_possible.cold.25 (STB_LOCAL)
ffffffff810999c0-ffffffff810999fb: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2303
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e274-ffffffff8109e280: init_cpu_possible.cold (STB_LOCAL)
ffffffff8109df90-ffffffff8109dfcb: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2322
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810a47d1-ffffffff810a47dd: init_cpu_possible.cold (STB_LOCAL)
ffffffff810a44e0-ffffffff810a451b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2453
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810abad9-ffffffff810abae5: init_cpu_possible.cold (STB_LOCAL)
ffffffff810ab7b0-ffffffff810ab7eb: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2464
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81bdb71b-ffffffff81bdb727: init_cpu_possible.cold (STB_LOCAL)
ffffffff810a7030-ffffffff810a706b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2584
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81bcd80d-ffffffff81bcd819: init_cpu_possible.cold (STB_LOCAL)
ffffffff810a80d0-ffffffff810a810b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2611
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81ca4163-ffffffff81ca416f: init_cpu_possible.cold (STB_LOCAL)
ffffffff810b9b80-ffffffff810b9bbb: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2633
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81e539ff-ffffffff81e53a0b: init_cpu_possible.cold (STB_LOCAL)
ffffffff810d0660-ffffffff810d06a7: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eef20)
Location: kernel/cpu.c:2659
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810eef20-ffffffff810eef6f: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810faed0)
Location: kernel/cpu.c:3055
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810faed0-ffffffff810faf1f: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81104370)
Location: kernel/cpu.c:3137
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81104370-ffffffff811043bf: init_cpu_possible (STB_GLOBAL)
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
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100fa150)
Location: kernel/cpu.c:2322
Inline: False
```
**Symbols:**

```
ffff8000100fa150-ffff8000100fa18c: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c035833c)
Location: kernel/cpu.c:2322
Inline: False
```
**Symbols:**

```
c035833c-c0358364: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000141330)
Location: kernel/cpu.c:2322
Inline: False
```
**Symbols:**

```
c000000000141330-c000000000141374: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c4282)
Location: kernel/cpu.c:2322
Inline: False
```
**Symbols:**

```
ffffffe0000c4282-ffffffe0000c42ea: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2322
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e0f1-ffffffff8109e0fd: init_cpu_possible.cold (STB_LOCAL)
ffffffff8109de00-ffffffff8109de3b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2322
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8108cb11-ffffffff8108cb1d: init_cpu_possible.cold (STB_LOCAL)
ffffffff8108c820-ffffffff8108c85b: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2322
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e0a1-ffffffff8109e0ad: init_cpu_possible.cold (STB_LOCAL)
ffffffff8109ddb0-ffffffff8109ddeb: init_cpu_possible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void init_cpu_possible(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2322
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810a5fc2-ffffffff810a5fce: init_cpu_possible.cold (STB_LOCAL)
ffffffff810a5ca0-ffffffff810a5cdb: init_cpu_possible (STB_GLOBAL)
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
