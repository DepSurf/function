# Function: <code>unknown_nmi_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032790)
Location: arch/x86/kernel/nmi.c:277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032790-ffffffff81032809: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810318f0)
Location: arch/x86/kernel/nmi.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810318f0-ffffffff81031975: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031540)
Location: arch/x86/kernel/nmi.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81031540-ffffffff810315c5: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f750)
Location: arch/x86/kernel/nmi.c:277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8102f750-ffffffff8102f7d5: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031750)
Location: arch/x86/kernel/nmi.c:277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81031750-ffffffff810317d5: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032990-ffffffff810329c0: unknown_nmi_error (STB_LOCAL)
ffffffff81032d33-ffffffff81032d8b: unknown_nmi_error.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81033cac)
Location: arch/x86/kernel/nmi.c:277
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81033c80-ffffffff81033cfc: unknown_nmi_error (STB_LOCAL)
ffffffff810340b2-ffffffff810340c3: unknown_nmi_error.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035e91)
Location: arch/x86/kernel/nmi.c:280
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81035ac0-ffffffff81035aef: unknown_nmi_error (STB_LOCAL)
ffffffff81035e91-ffffffff81035ee8: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810366b1)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810362c0-ffffffff810362ef: unknown_nmi_error (STB_LOCAL)
ffffffff810366b1-ffffffff81036708: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810382e0-ffffffff8103830f: unknown_nmi_error (STB_LOCAL)
ffffffff81038492-ffffffff810384e9: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81038e10-ffffffff81038e3f: unknown_nmi_error (STB_LOCAL)
ffffffff81bd3a68-ffffffff81bd3abf: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8103a920-ffffffff8103a94f: unknown_nmi_error (STB_LOCAL)
ffffffff81bc5eda-ffffffff81bc5f31: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:274
Inline: False
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81040300-ffffffff8104032f: unknown_nmi_error (STB_LOCAL)
ffffffff81c98c24-ffffffff81c98c7b: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81e48162)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81047bc0-ffffffff81047bfc: unknown_nmi_error (STB_LOCAL)
ffffffff81e48162-ffffffff81e481ae: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810526f0)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810526f0-ffffffff8105277e: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81053450)
Location: arch/x86/kernel/nmi.c:287
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81053450-ffffffff810534de: unknown_nmi_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a670)
Location: arch/x86/kernel/nmi.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8105a670-ffffffff8105a6fe: unknown_nmi_error (STB_LOCAL)
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
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036811)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036420-ffffffff8103644f: unknown_nmi_error (STB_LOCAL)
ffffffff81036811-ffffffff81036868: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81026151)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81025d70-ffffffff81025d9f: unknown_nmi_error (STB_LOCAL)
ffffffff81026151-ffffffff810261a8: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036671)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036280-ffffffff810362af: unknown_nmi_error (STB_LOCAL)
ffffffff81036671-ffffffff810366c8: unknown_nmi_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unknown_nmi_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81037671)
Location: arch/x86/kernel/nmi.c:278
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81037280-ffffffff810372af: unknown_nmi_error (STB_LOCAL)
ffffffff81037671-ffffffff810376c8: unknown_nmi_error.cold (STB_LOCAL)
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
