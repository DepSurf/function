# Function: <code>nmi_handle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032340)
Location: arch/x86/kernel/nmi.c:113
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032340-ffffffff8103245b: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031470)
Location: arch/x86/kernel/nmi.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81031470-ffffffff81031582: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810310c0)
Location: arch/x86/kernel/nmi.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810310c0-ffffffff810311d2: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f3a0)
Location: arch/x86/kernel/nmi.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8102f3a0-ffffffff8102f4b1: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810313a0)
Location: arch/x86/kernel/nmi.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810313a0-ffffffff810314b9: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032730)
Location: arch/x86/kernel/nmi.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032730-ffffffff8103284c: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810339f0)
Location: arch/x86/kernel/nmi.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810339f0-ffffffff81033b0c: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035780)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81035780-ffffffff8103588a: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036090-ffffffff810361b4: nmi_handle (STB_LOCAL)
ffffffff81036632-ffffffff81036666: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff81038190-ffffffff810382a3: nmi_handle (STB_LOCAL)
ffffffff8103844e-ffffffff81038482: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff81038cd0-ffffffff81038dd2: nmi_handle (STB_LOCAL)
ffffffff81bd3a24-ffffffff81bd3a58: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff8103a7e0-ffffffff8103a8e2: nmi_handle (STB_LOCAL)
ffffffff81bc5e96-ffffffff81bc5eca: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:unknown_nmi_error
```
**Symbols:**

```
ffffffff810401b0-ffffffff810402cc: nmi_handle (STB_LOCAL)
ffffffff81c98be0-ffffffff81c98c14: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81047920-ffffffff81047a5e: nmi_handle (STB_LOCAL)
ffffffff81e480b6-ffffffff81e480ea: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81052390)
Location: arch/x86/kernel/nmi.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81052390-ffffffff81052508: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81053220)
Location: arch/x86/kernel/nmi.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81053220-ffffffff81053398: nmi_handle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a440)
Location: arch/x86/kernel/nmi.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8105a440-ffffffff8105a5b8: nmi_handle (STB_LOCAL)
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
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810361f0-ffffffff81036314: nmi_handle (STB_LOCAL)
ffffffff81036792-ffffffff810367c6: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81025b40-ffffffff81025c64: nmi_handle (STB_LOCAL)
ffffffff810260d2-ffffffff81026106: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036050-ffffffff81036174: nmi_handle (STB_LOCAL)
ffffffff810365f2-ffffffff81036626: nmi_handle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nmi_handle(unsigned int type, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:125
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81037030-ffffffff81037179: nmi_handle (STB_LOCAL)
ffffffff810375f2-ffffffff81037626: nmi_handle.cold (STB_LOCAL)
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
