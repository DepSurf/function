# Function: <code>get_ins_reg_val</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81073d10)
Location: arch/x86/mm/pf_in.c:410
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81073d10-ffffffff81073fa1: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810752f0)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff810752f0-ffffffff81075581: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81078e70)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81078e70-ffffffff81079101: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81077730)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81077730-ffffffff810779ec: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff8107da80)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8107da80-ffffffff8107dd42: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81080af0)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81080af0-ffffffff81080df4: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff81087670)
Location: arch/x86/mm/pf_in.c:409
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81087670-ffffffff81087a02: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8108b71a-ffffffff8108b72d: get_ins_reg_val.cold (STB_LOCAL)
ffffffff8108b220-ffffffff8108b5df: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8108c38a-ffffffff8108c39d: get_ins_reg_val.cold (STB_LOCAL)
ffffffff8108be90-ffffffff8108c24f: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81093800-ffffffff81093813: get_ins_reg_val.cold (STB_LOCAL)
ffffffff81093320-ffffffff810936de: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81bd9ff5-ffffffff81bda008: get_ins_reg_val.cold (STB_LOCAL)
ffffffff810928e0-ffffffff81092c9e: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81bcc050-ffffffff81bcc063: get_ins_reg_val.cold (STB_LOCAL)
ffffffff810933b0-ffffffff8109376b: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81ca1fbd-ffffffff81ca1fd0: get_ins_reg_val.cold (STB_LOCAL)
ffffffff810a3180-ffffffff810a353b: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81e51618-ffffffff81e5162b: get_ins_reg_val.cold (STB_LOCAL)
ffffffff810b7850-ffffffff810b7b8c: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810d2e00)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff810d2e00-ffffffff810d3166: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810d6240)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff810d6240-ffffffff810d654b: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pf_in.c (ffffffff810dea70)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:post
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff810dea70-ffffffff810ded7b: get_ins_reg_val (STB_GLOBAL)
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
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8108b34a-ffffffff8108b35d: get_ins_reg_val.cold (STB_LOCAL)
ffffffff8108ae50-ffffffff8108b20f: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff81079eba-ffffffff81079ecd: get_ins_reg_val.cold (STB_LOCAL)
ffffffff810799c0-ffffffff81079d7f: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8108b2fa-ffffffff8108b30d: get_ins_reg_val.cold (STB_LOCAL)
ffffffff8108ae00-ffffffff8108b1bf: get_ins_reg_val (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int get_ins_reg_val(long unsigned int ins_addr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pf_in.c (0)
Location: arch/x86/mm/pf_in.c:394
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:pre
```
**Symbols:**

```
ffffffff8108d5fa-ffffffff8108d60d: get_ins_reg_val.cold (STB_LOCAL)
ffffffff8108d100-ffffffff8108d4bf: get_ins_reg_val (STB_GLOBAL)
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
