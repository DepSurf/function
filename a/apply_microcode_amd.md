# Function: <code>apply_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apply_microcode_amd(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e500)
Location: arch/x86/kernel/cpu/microcode/amd.c:668
Inline: False
```
**Symbols:**

```
ffffffff8104e500-ffffffff8104e632: apply_microcode_amd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_microcode_amd(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e960)
Location: arch/x86/kernel/cpu/microcode/amd.c:680
Inline: False
```
**Symbols:**

```
ffffffff8104e960-ffffffff8104ea79: apply_microcode_amd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81051140)
Location: arch/x86/kernel/cpu/microcode/amd.c:681
Inline: False
```
**Symbols:**

```
ffffffff81051140-ffffffff81051259: apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050900)
Location: arch/x86/kernel/cpu/microcode/amd.c:494
Inline: False
```
**Symbols:**

```
ffffffff81050900-ffffffff810509dc: apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054430)
Location: arch/x86/kernel/cpu/microcode/amd.c:501
Inline: False
```
**Symbols:**

```
ffffffff81054430-ffffffff8105451c: apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:501
Inline: False
```
**Symbols:**

```
ffffffff81057200-ffffffff810572d4: apply_microcode_amd (STB_LOCAL)
ffffffff81057c45-ffffffff81057c85: apply_microcode_amd.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:671
Inline: False
```
**Symbols:**

```
ffffffff810547c0-ffffffff81054894: apply_microcode_amd (STB_LOCAL)
ffffffff810555e5-ffffffff81055625: apply_microcode_amd.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff81057a10-ffffffff81057ad6: apply_microcode_amd (STB_LOCAL)
ffffffff81058815-ffffffff81058857: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff810582e0-ffffffff810583a6: apply_microcode_amd (STB_LOCAL)
ffffffff810590e5-ffffffff81059127: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff8105ddc0-ffffffff8105de84: apply_microcode_amd (STB_LOCAL)
ffffffff8105e42f-ffffffff8105e471: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:668
Inline: False
```
**Symbols:**

```
ffffffff8105c3a0-ffffffff8105c464: apply_microcode_amd (STB_LOCAL)
ffffffff81bd61f4-ffffffff81bd6236: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:668
Inline: False
```
**Symbols:**

```
ffffffff8105ccb0-ffffffff8105cd76: apply_microcode_amd (STB_LOCAL)
ffffffff81bc85c1-ffffffff81bc8603: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:668
Inline: False
```
**Symbols:**

```
ffffffff81066370-ffffffff8106645b: apply_microcode_amd (STB_LOCAL)
ffffffff81c9c4b9-ffffffff81c9c4fb: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:674
Inline: False
```
**Symbols:**

```
ffffffff810730e0-ffffffff810731e1: apply_microcode_amd (STB_LOCAL)
ffffffff81e4b7f3-ffffffff81e4b831: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810831b0)
Location: arch/x86/kernel/cpu/microcode/amd.c:685
Inline: False
```
**Symbols:**

```
ffffffff810831b0-ffffffff810832de: apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084ff0)
Location: arch/x86/kernel/cpu/microcode/amd.c:680
Inline: False
```
**Symbols:**

```
ffffffff81084ff0-ffffffff8108511e: apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c260)
Location: arch/x86/kernel/cpu/microcode/amd.c:647
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff8108c260-ffffffff8108c3b6: apply_microcode_amd (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff81057e60-ffffffff81057f26: apply_microcode_amd (STB_LOCAL)
ffffffff81058c65-ffffffff81058ca7: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff81048c70-ffffffff81048d6f: apply_microcode_amd (STB_LOCAL)
ffffffff81048f23-ffffffff81048f63: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff81058290-ffffffff81058356: apply_microcode_amd (STB_LOCAL)
ffffffff81059095-ffffffff810590d7: apply_microcode_amd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum ucode_state apply_microcode_amd(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (0)
Location: arch/x86/kernel/cpu/microcode/amd.c:669
Inline: False
```
**Symbols:**

```
ffffffff81059730-ffffffff810597f6: apply_microcode_amd (STB_LOCAL)
ffffffff8105a535-ffffffff8105a577: apply_microcode_amd.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum ucode_state</code>
</li>
</ul>
</details>
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
