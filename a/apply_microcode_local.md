# Function: <code>apply_microcode_local</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c720)
Location: arch/x86/kernel/cpu/microcode/core.c:264
Inline: False
```
**Symbols:**

```
ffffffff8104c720-ffffffff8104c743: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104c7a0)
Location: arch/x86/kernel/cpu/microcode/core.c:256
Inline: False
```
**Symbols:**

```
ffffffff8104c7a0-ffffffff8104c7c3: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104ebf0)
Location: arch/x86/kernel/cpu/microcode/core.c:331
Inline: False
```
**Symbols:**

```
ffffffff8104ebf0-ffffffff8104ec13: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104eb20)
Location: arch/x86/kernel/cpu/microcode/core.c:371
Inline: False
```
**Symbols:**

```
ffffffff8104eb20-ffffffff8104eb43: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052aa7)
Location: arch/x86/kernel/cpu/microcode/core.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81052490-ffffffff810524b9: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810558f1)
Location: arch/x86/kernel/cpu/microcode/core.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff810551b0-ffffffff810551d9: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052f91)
Location: arch/x86/kernel/cpu/microcode/core.c:384
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81052850-ffffffff81052879: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056145)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff810559b0-ffffffff810559d9: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810569f5)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81056280-ffffffff810562a9: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105bbab)
Location: arch/x86/kernel/cpu/microcode/core.c:375
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff8105b3a0-ffffffff8105b3cc: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a5fb)
Location: arch/x86/kernel/cpu/microcode/core.c:373
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81059df0-ffffffff81059e1c: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105af97)
Location: arch/x86/kernel/cpu/microcode/core.c:373
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff8105a790-ffffffff8105a7bc: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810644f0)
Location: arch/x86/kernel/cpu/microcode/core.c:373
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81063ce0-ffffffff81063d0c: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810709e0)
Location: arch/x86/kernel/cpu/microcode/core.c:356
Inline: False
```
**Symbols:**

```
ffffffff810709e0-ffffffff81070a14: apply_microcode_local (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056575)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81055e00-ffffffff81055e29: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046785)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81046010-ffffffff81046039: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810569a5)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff81056230-ffffffff81056259: apply_microcode_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void apply_microcode_local(void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810579d7)
Location: arch/x86/kernel/cpu/microcode/core.c:380
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:__reload_late
```
**Symbols:**

```
ffffffff810576d0-ffffffff810576f9: apply_microcode_local (STB_LOCAL)
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
