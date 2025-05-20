# Function: <code>__reload_late</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052a70)
Location: arch/x86/kernel/cpu/microcode/core.c:550
Inline: False
```
**Symbols:**

```
ffffffff81052a70-ffffffff81052b3d: __reload_late (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:558
Inline: False
```
**Symbols:**

```
ffffffff810558b0-ffffffff8105595f: __reload_late (STB_LOCAL)
ffffffff81055cc6-ffffffff81055ce6: __reload_late.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:559
Inline: False
```
**Symbols:**

```
ffffffff81052f50-ffffffff81052fff: __reload_late (STB_LOCAL)
ffffffff81053366-ffffffff81053386: __reload_late.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff81056100-ffffffff810561a9: __reload_late (STB_LOCAL)
ffffffff81056561-ffffffff81056581: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff810569b0-ffffffff81056a58: __reload_late (STB_LOCAL)
ffffffff81056e11-ffffffff81056e31: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:550
Inline: False
```
**Symbols:**

```
ffffffff8105bb20-ffffffff8105bc06: __reload_late (STB_LOCAL)
ffffffff8105bfc1-ffffffff8105bfe5: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:548
Inline: False
```
**Symbols:**

```
ffffffff8105a570-ffffffff8105a656: __reload_late (STB_LOCAL)
ffffffff81bd5f34-ffffffff81bd5f58: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:548
Inline: False
```
**Symbols:**

```
ffffffff8105af10-ffffffff8105aff4: __reload_late (STB_LOCAL)
ffffffff81bc82e0-ffffffff81bc8304: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:548
Inline: False
```
**Symbols:**

```
ffffffff81064450-ffffffff8106457a: __reload_late (STB_LOCAL)
ffffffff81c9c15b-ffffffff81c9c17f: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff81056530-ffffffff810565d8: __reload_late (STB_LOCAL)
ffffffff81056991-ffffffff810569b1: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff81046740-ffffffff810467e8: __reload_late (STB_LOCAL)
ffffffff81046ba1-ffffffff81046bc1: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff81056960-ffffffff81056a08: __reload_late (STB_LOCAL)
ffffffff81056dc1-ffffffff81056de1: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __reload_late(void *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (0)
Location: arch/x86/kernel/cpu/microcode/core.c:556
Inline: False
```
**Symbols:**

```
ffffffff81057990-ffffffff81057a39: __reload_late (STB_LOCAL)
ffffffff810581f0-ffffffff81058210: __reload_late.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
