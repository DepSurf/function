# Function: <code>init_cpu_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081fd0)
Location: kernel/cpu.c:816
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81081fd0-ffffffff81082006: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085030)
Location: kernel/cpu.c:1747
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81085030-ffffffff81085066: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089fd0)
Location: kernel/cpu.c:1789
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81089fd0-ffffffff81089ffc: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81087080)
Location: kernel/cpu.c:1755
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81087080-ffffffff810870c3: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108ddf0)
Location: kernel/cpu.c:1989
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8108ddf0-ffffffff8108de33: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2233
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81091973-ffffffff8109197f: init_cpu_present.cold.22 (STB_LOCAL)
ffffffff810916a0-ffffffff810916db: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2255
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81099c53-ffffffff81099c5f: init_cpu_present.cold.24 (STB_LOCAL)
ffffffff81099980-ffffffff810999bb: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2298
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e268-ffffffff8109e274: init_cpu_present.cold (STB_LOCAL)
ffffffff8109df50-ffffffff8109df8b: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810a47c5-ffffffff810a47d1: init_cpu_present.cold (STB_LOCAL)
ffffffff810a44a0-ffffffff810a44db: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2448
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810abacd-ffffffff810abad9: init_cpu_present.cold (STB_LOCAL)
ffffffff810ab770-ffffffff810ab7ab: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2459
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81bdb70f-ffffffff81bdb71b: init_cpu_present.cold (STB_LOCAL)
ffffffff810a6ff0-ffffffff810a702b: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2579
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81bcd801-ffffffff81bcd80d: init_cpu_present.cold (STB_LOCAL)
ffffffff810a8090-ffffffff810a80cb: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2606
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81ca4157-ffffffff81ca4163: init_cpu_present.cold (STB_LOCAL)
ffffffff810b9b40-ffffffff810b9b7b: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2628
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81e539f3-ffffffff81e539ff: init_cpu_present.cold (STB_LOCAL)
ffffffff810d0610-ffffffff810d0657: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eeec0)
Location: kernel/cpu.c:2654
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810eeec0-ffffffff810eef0f: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fae70)
Location: kernel/cpu.c:3050
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810fae70-ffffffff810faebf: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81104310)
Location: kernel/cpu.c:3132
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff81104310-ffffffff8110435f: init_cpu_present (STB_GLOBAL)
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
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100fa110)
Location: kernel/cpu.c:2317
Inline: False
```
**Symbols:**

```
ffff8000100fa110-ffff8000100fa14c: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0358314)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/arm/kernel/smp.c:smp_prepare_cpus
```
**Symbols:**

```
c0358314-c035833c: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001412e0)
Location: kernel/cpu.c:2317
Inline: False
```
**Symbols:**

```
c0000000001412e0-c000000000141324: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c421a)
Location: kernel/cpu.c:2317
Inline: False
```
**Symbols:**

```
ffffffe0000c421a-ffffffe0000c4282: init_cpu_present (STB_GLOBAL)
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
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e0e5-ffffffff8109e0f1: init_cpu_present.cold (STB_LOCAL)
ffffffff8109ddc0-ffffffff8109ddfb: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8108cb05-ffffffff8108cb11: init_cpu_present.cold (STB_LOCAL)
ffffffff8108c7e0-ffffffff8108c81b: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff8109e095-ffffffff8109e0a1: init_cpu_present.cold (STB_LOCAL)
ffffffff8109dd70-ffffffff8109ddab: init_cpu_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void init_cpu_present(const struct cpumask *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:2317
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:disable_smp
```
**Symbols:**

```
ffffffff810a5fb6-ffffffff810a5fc2: init_cpu_present.cold (STB_LOCAL)
ffffffff810a5c60-ffffffff810a5c9b: init_cpu_present (STB_GLOBAL)
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
