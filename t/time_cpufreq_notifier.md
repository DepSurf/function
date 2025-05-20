# Function: <code>time_cpufreq_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037c30)
Location: arch/x86/kernel/tsc.c:919
Inline: False
```
**Symbols:**

```
ffffffff81037c30-ffffffff81037d0a: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036e40)
Location: arch/x86/kernel/tsc.c:976
Inline: False
```
**Symbols:**

```
ffffffff81036e40-ffffffff81036f13: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81036b70)
Location: arch/x86/kernel/tsc.c:997
Inline: False
```
**Symbols:**

```
ffffffff81036b70-ffffffff81036c43: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81034ce0)
Location: arch/x86/kernel/tsc.c:905
Inline: False
```
**Symbols:**

```
ffffffff81034ce0-ffffffff81034db2: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81037040)
Location: arch/x86/kernel/tsc.c:902
Inline: False
```
**Symbols:**

```
ffffffff81037040-ffffffff81037111: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81038060)
Location: arch/x86/kernel/tsc.c:920
Inline: False
```
**Symbols:**

```
ffffffff81038060-ffffffff81038131: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff81039520)
Location: arch/x86/kernel/tsc.c:955
Inline: False
```
**Symbols:**

```
ffffffff81039520-ffffffff810395f1: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103bd10)
Location: arch/x86/kernel/tsc.c:975
Inline: True
```
**Symbols:**

```
ffffffff8103bd10-ffffffff8103bdfd: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c280)
Location: arch/x86/kernel/tsc.c:975
Inline: True
```
**Symbols:**

```
ffffffff8103c280-ffffffff8103c358: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:982
Inline: False
```
**Symbols:**

```
ffffffff8103f230-ffffffff8103f3a4: time_cpufreq_notifier (STB_LOCAL)
ffffffff8103f984-ffffffff8103f9ad: time_cpufreq_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:982
Inline: False
```
**Symbols:**

```
ffffffff8103f2f0-ffffffff8103f464: time_cpufreq_notifier (STB_LOCAL)
ffffffff81bd440f-ffffffff81bd4438: time_cpufreq_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:983
Inline: False
```
**Symbols:**

```
ffffffff81040910-ffffffff81040a93: time_cpufreq_notifier (STB_LOCAL)
ffffffff81bc68d1-ffffffff81bc68fa: time_cpufreq_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:983
Inline: False
```
**Symbols:**

```
ffffffff81046a00-ffffffff81046b83: time_cpufreq_notifier (STB_LOCAL)
ffffffff81c99b95-ffffffff81c99bbe: time_cpufreq_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/tsc.c (0)
Location: arch/x86/kernel/tsc.c:983
Inline: False
```
**Symbols:**

```
ffffffff8104fb20-ffffffff8104fc44: time_cpufreq_notifier (STB_LOCAL)
ffffffff81e496d7-ffffffff81e496ff: time_cpufreq_notifier.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105ce00)
Location: arch/x86/kernel/tsc.c:983
Inline: True
```
**Symbols:**

```
ffffffff8105ce00-ffffffff8105cf98: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8105e300)
Location: arch/x86/kernel/tsc.c:1018
Inline: True
```
**Symbols:**

```
ffffffff8105e300-ffffffff8105e498: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff810653c0)
Location: arch/x86/kernel/tsc.c:1018
Inline: True
```
**Symbols:**

```
ffffffff810653c0-ffffffff81065558: time_cpufreq_notifier (STB_LOCAL)
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
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c3e0)
Location: arch/x86/kernel/tsc.c:977
Inline: True
```
**Symbols:**

```
ffffffff8103c3e0-ffffffff8103c4b8: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8102bca0)
Location: arch/x86/kernel/tsc.c:975
Inline: True
```
**Symbols:**

```
ffffffff8102bca0-ffffffff8102bd78: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103c240)
Location: arch/x86/kernel/tsc.c:975
Inline: True
```
**Symbols:**

```
ffffffff8103c240-ffffffff8103c318: time_cpufreq_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int time_cpufreq_notifier(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/tsc.c (ffffffff8103d290)
Location: arch/x86/kernel/tsc.c:975
Inline: True
```
**Symbols:**

```
ffffffff8103d290-ffffffff8103d368: time_cpufreq_notifier (STB_LOCAL)
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
