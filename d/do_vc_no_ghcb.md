# Function: <code>do_vc_no_ghcb</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff82fd13d1)
Location: arch/x86/kernel/sev-es-shared.c:144
Inline: False
```
**Symbols:**

```
ffffffff82fd13d1-ffffffff82fd14f0: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff831dc093)
Location: arch/x86/kernel/sev-shared.c:145
Inline: False
```
**Symbols:**

```
ffffffff831dc093-ffffffff831dc198: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff832bf149)
Location: arch/x86/kernel/sev-shared.c:147
Inline: False
```
**Symbols:**

```
ffffffff832bf149-ffffffff832bf24e: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83471592)
Location: arch/x86/kernel/sev-shared.c:530
Inline: False
```
**Symbols:**

```
ffffffff83471592-ffffffff83471678: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff83e98750)
Location: arch/x86/kernel/sev-shared.c:530
Inline: False
```
**Symbols:**

```
ffffffff83e98750-ffffffff83e98836: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff836bc180)
Location: arch/x86/kernel/sev-shared.c:533
Inline: False
```
**Symbols:**

```
ffffffff836bc180-ffffffff836bc264: do_vc_no_ghcb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_vc_no_ghcb(struct pt_regs *regs, long unsigned int exit_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff838ecb60)
Location: arch/x86/kernel/sev-shared.c:573
Inline: False
```
**Symbols:**

```
ffffffff838ecb60-ffffffff838ecc48: do_vc_no_ghcb (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
