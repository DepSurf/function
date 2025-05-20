# Function: <code>read_hpet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
cycle_t read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061fc0)
Location: arch/x86/kernel/hpet.c:764
Inline: False
```
**Symbols:**

```
ffffffff81061fc0-ffffffff81061fda: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
cycle_t read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81061df0)
Location: arch/x86/kernel/hpet.c:759
Inline: False
```
**Symbols:**

```
ffffffff81061df0-ffffffff81061e0a: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065830)
Location: arch/x86/kernel/hpet.c:795
Inline: True
```
**Symbols:**

```
ffffffff81065830-ffffffff810658f9: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064c20)
Location: arch/x86/kernel/hpet.c:790
Inline: True
```
**Symbols:**

```
ffffffff81064c20-ffffffff81064ce6: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068db0)
Location: arch/x86/kernel/hpet.c:790
Inline: True
```
**Symbols:**

```
ffffffff81068db0-ffffffff81068e77: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b560)
Location: arch/x86/kernel/hpet.c:791
Inline: True
```
**Symbols:**

```
ffffffff8106b560-ffffffff8106b62e: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810715e0)
Location: arch/x86/kernel/hpet.c:787
Inline: True
```
**Symbols:**

```
ffffffff810715e0-ffffffff810716a5: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075460)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff81075460-ffffffff8107552c: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076430)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff81076430-ffffffff810764fc: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d460)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff8107d460-ffffffff8107d500: read_hpet.part.0 (STB_LOCAL)
ffffffff8107d500-ffffffff8107d52e: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d3d0)
Location: arch/x86/kernel/hpet.c:793
Inline: True
```
**Symbols:**

```
ffffffff8107d3d0-ffffffff8107d470: read_hpet.part.0 (STB_LOCAL)
ffffffff8107d470-ffffffff8107d49e: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e770)
Location: arch/x86/kernel/hpet.c:793
Inline: True
```
**Symbols:**

```
ffffffff8107e770-ffffffff8107e829: read_hpet.part.0 (STB_LOCAL)
ffffffff8107e830-ffffffff8107e860: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108d3f0)
Location: arch/x86/kernel/hpet.c:794
Inline: True
```
**Symbols:**

```
ffffffff8108d3f0-ffffffff8108d4a9: read_hpet.part.0 (STB_LOCAL)
ffffffff8108d4b0-ffffffff8108d4e0: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109d650)
Location: arch/x86/kernel/hpet.c:794
Inline: False
```
**Symbols:**

```
ffffffff8109d650-ffffffff8109d75d: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4760)
Location: arch/x86/kernel/hpet.c:794
Inline: False
```
**Symbols:**

```
ffffffff810b4760-ffffffff810b4884: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7820)
Location: arch/x86/kernel/hpet.c:794
Inline: False
```
**Symbols:**

```
ffffffff810b7820-ffffffff810b7954: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bec60)
Location: arch/x86/kernel/hpet.c:794
Inline: False
```
**Symbols:**

```
ffffffff810bec60-ffffffff810bed94: read_hpet (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075430)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff81075430-ffffffff810754fc: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065260)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff81065260-ffffffff81065309: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810753e0)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff810753e0-ffffffff810754ac: read_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u64 read_hpet(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81077440)
Location: arch/x86/kernel/hpet.c:683
Inline: True
```
**Symbols:**

```
ffffffff81077440-ffffffff8107750c: read_hpet (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>cycle_t</code> ➡️ <code>u64</code>
</li>
</ul>
</details>
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
