# Function: <code>trampoline_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f290)
Location: arch/x86/kernel/kprobes/core.c:711
Inline: False
```
**Symbols:**

```
ffffffff8105f290-ffffffff8105f48d: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f090)
Location: arch/x86/kernel/kprobes/core.c:713
Inline: False
```
**Symbols:**

```
ffffffff8105f090-ffffffff8105f2b7: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062130)
Location: arch/x86/kernel/kprobes/core.c:714
Inline: False
```
**Symbols:**

```
ffffffff81062130-ffffffff81062357: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810610d0)
Location: arch/x86/kernel/kprobes/core.c:747
Inline: False
```
**Symbols:**

```
ffffffff810610d0-ffffffff81061313: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81064f20)
Location: arch/x86/kernel/kprobes/core.c:766
Inline: False
```
**Symbols:**

```
ffffffff81064f20-ffffffff81065167: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81067ac0)
Location: arch/x86/kernel/kprobes/core.c:767
Inline: False
```
**Symbols:**

```
ffffffff81067ac0-ffffffff81067d07: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106d980)
Location: arch/x86/kernel/kprobes/core.c:754
Inline: False
```
**Symbols:**

```
ffffffff8106d980-ffffffff8106dbc2: trampoline_handler (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff81072790-ffffffff810727de: trampoline_handler.cold (STB_LOCAL)
ffffffff810719d0-ffffffff81071c17: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff810737ad-ffffffff810737f9: trampoline_handler.cold (STB_LOCAL)
ffffffff81072a00-ffffffff81072c46: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:760
Inline: False
```
**Symbols:**

```
ffffffff8107a8bd-ffffffff8107a909: trampoline_handler.cold (STB_LOCAL)
ffffffff81079a80-ffffffff81079ca2: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81079860)
Location: arch/x86/kernel/kprobes/core.c:774
Inline: False
```
**Symbols:**

```
ffffffff81079860-ffffffff810798b9: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107ade0)
Location: arch/x86/kernel/kprobes/core.c:1063
Inline: False
```
**Symbols:**

```
ffffffff8107ade0-ffffffff8107ae39: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81088f50)
Location: arch/x86/kernel/kprobes/core.c:1057
Inline: False
```
**Symbols:**

```
ffffffff81088f50-ffffffff81088fa9: trampoline_handler (STB_GLOBAL)
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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/probes/kprobes/core.c (c0ea0920)
Location: arch/arm/probes/kprobes/core.c:414
Inline: False
```
**Symbols:**

```
c0ea0920-c0ea0b54: trampoline_handler (STB_LOCAL)
```
</details>
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
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff810727ad-ffffffff810727f9: trampoline_handler.cold (STB_LOCAL)
ffffffff81071a00-ffffffff81071c46: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff8106282d-ffffffff81062879: trampoline_handler.cold (STB_LOCAL)
ffffffff81061a10-ffffffff81061c56: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff8107275d-ffffffff810727a9: trampoline_handler.cold (STB_LOCAL)
ffffffff810719b0-ffffffff81071bf6: trampoline_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *trampoline_handler(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:756
Inline: False
```
**Symbols:**

```
ffffffff810747ad-ffffffff810747f9: trampoline_handler.cold (STB_LOCAL)
ffffffff81073a10-ffffffff81073c74: trampoline_handler (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
