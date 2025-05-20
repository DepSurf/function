# Function: <code>bsp_pm_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff816faec0)
Location: arch/x86/power/cpu.c:258
Inline: False
```
**Symbols:**

```
ffffffff816faec0-ffffffff816faf04: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81760020)
Location: arch/x86/power/cpu.c:314
Inline: False
```
**Symbols:**

```
ffffffff81760020-ffffffff8176006a: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8178d020)
Location: arch/x86/power/cpu.c:315
Inline: False
```
**Symbols:**

```
ffffffff8178d020-ffffffff8178d06c: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff817ab1b0)
Location: arch/x86/power/cpu.c:318
Inline: True
```
**Symbols:**

```
ffffffff817ab1b0-ffffffff817ab1fb: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818226a0)
Location: arch/x86/power/cpu.c:325
Inline: True
```
**Symbols:**

```
ffffffff818226a0-ffffffff818226eb: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:325
Inline: True
```
**Symbols:**

```
ffffffff8186c990-ffffffff8186c9cc: bsp_pm_callback (STB_LOCAL)
ffffffff8186cebd-ffffffff8186ced3: bsp_pm_callback.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8188c9b7)
Location: arch/x86/power/cpu.c:325
Inline: True
```
**Symbols:**

```
ffffffff8188c9a0-ffffffff8188c9dc: bsp_pm_callback (STB_LOCAL)
ffffffff8188cecd-ffffffff8188cee3: bsp_pm_callback.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818d72e2)
Location: arch/x86/power/cpu.c:335
Inline: True
```
**Symbols:**

```
ffffffff818d72c0-ffffffff818d7303: bsp_pm_callback (STB_LOCAL)
ffffffff818d7876-ffffffff818d788d: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81909662)
Location: arch/x86/power/cpu.c:331
Inline: True
```
**Symbols:**

```
ffffffff81909640-ffffffff81909683: bsp_pm_callback (STB_LOCAL)
ffffffff81909bb6-ffffffff81909bcd: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81bb9f74)
Location: arch/x86/power/cpu.c:337
Inline: True
```
**Symbols:**

```
ffffffff81bb9f50-ffffffff81bb9f97: bsp_pm_callback (STB_LOCAL)
ffffffff81bba4ca-ffffffff81bba4e1: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81bce7e4)
Location: arch/x86/power/cpu.c:337
Inline: True
```
**Symbols:**

```
ffffffff81bce7c0-ffffffff81bce807: bsp_pm_callback (STB_LOCAL)
ffffffff81c34afa-ffffffff81c34b11: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81bc2194)
Location: arch/x86/power/cpu.c:333
Inline: True
```
**Symbols:**

```
ffffffff81bc2170-ffffffff81bc21b7: bsp_pm_callback (STB_LOCAL)
ffffffff81c26fff-ffffffff81c27016: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff81c927a4)
Location: arch/x86/power/cpu.c:334
Inline: True
```
**Symbols:**

```
ffffffff81c92780-ffffffff81c927c7: bsp_pm_callback (STB_LOCAL)
ffffffff81d44f8a-ffffffff81d44fa1: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (0)
Location: arch/x86/power/cpu.c:343
Inline: False
```
**Symbols:**

```
ffffffff81e41f40-ffffffff81e41f8a: bsp_pm_callback (STB_LOCAL)
ffffffff81f11dc7-ffffffff81f11ddd: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8201c710)
Location: arch/x86/power/cpu.c:344
Inline: False
```
**Symbols:**

```
ffffffff8201c710-ffffffff8201c771: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8209cda0)
Location: arch/x86/power/cpu.c:344
Inline: False
```
**Symbols:**

```
ffffffff8209cda0-ffffffff8209ce01: bsp_pm_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff821745a0)
Location: arch/x86/power/cpu.c:344
Inline: False
```
**Symbols:**

```
ffffffff821745a0-ffffffff82174601: bsp_pm_callback (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818a8a22)
Location: arch/x86/power/cpu.c:331
Inline: True
```
**Symbols:**

```
ffffffff818a8a00-ffffffff818a8a43: bsp_pm_callback (STB_LOCAL)
ffffffff818a8f76-ffffffff818a8f8d: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818634b2)
Location: arch/x86/power/cpu.c:331
Inline: True
```
**Symbols:**

```
ffffffff81863490-ffffffff818634d3: bsp_pm_callback (STB_LOCAL)
ffffffff81863be6-ffffffff81863bfd: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff818fa082)
Location: arch/x86/power/cpu.c:331
Inline: True
```
**Symbols:**

```
ffffffff818fa060-ffffffff818fa0a3: bsp_pm_callback (STB_LOCAL)
ffffffff818fa5d6-ffffffff818fa5ed: bsp_pm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bsp_pm_callback(struct notifier_block *nb, long unsigned int action, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/power/cpu.c (ffffffff8191b1e2)
Location: arch/x86/power/cpu.c:331
Inline: True
```
**Symbols:**

```
ffffffff8191b1c0-ffffffff8191b203: bsp_pm_callback (STB_LOCAL)
ffffffff8191b736-ffffffff8191b74d: bsp_pm_callback.cold (STB_LOCAL)
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
