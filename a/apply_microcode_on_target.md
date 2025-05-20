# Function: <code>apply_microcode_on_target</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c820)
Location: arch/x86/kernel/cpu/microcode/core.c:271
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff8104c820-ffffffff8104c874: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ce19)
Location: arch/x86/kernel/cpu/microcode/core.c:263
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_callback
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff8104c8a0-ffffffff8104c8f4: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f236)
Location: arch/x86/kernel/cpu/microcode/core.c:338
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff8104ed90-ffffffff8104ede4: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104efcf)
Location: arch/x86/kernel/cpu/microcode/core.c:378
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff8104ecc0-ffffffff8104ed15: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052630)
Location: arch/x86/kernel/cpu/microcode/core.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81052630-ffffffff81052684: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055350)
Location: arch/x86/kernel/cpu/microcode/core.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81055350-ffffffff810553a4: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810529f0)
Location: arch/x86/kernel/cpu/microcode/core.c:391
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:mc_cpu_online
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff810529f0-ffffffff81052a44: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055ba0)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81055ba0-ffffffff81055bf4: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056470)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81056470-ffffffff810564c4: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b9f3)
Location: arch/x86/kernel/cpu/microcode/core.c:382
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a443)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105ade3)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81064323)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81070ca1)
Location: arch/x86/kernel/cpu/microcode/core.c:363
Inline: True
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055ff0)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81055ff0-ffffffff81056044: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046200)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81046200-ffffffff81046254: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056420)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff81056420-ffffffff81056474: apply_microcode_on_target (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int apply_microcode_on_target(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810578c0)
Location: arch/x86/kernel/cpu/microcode/core.c:387
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_write
```
**Symbols:**

```
ffffffff810578c0-ffffffff81057914: apply_microcode_on_target (STB_LOCAL)
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
