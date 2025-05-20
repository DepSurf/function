# Function: <code>io_check_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032810)
Location: arch/x86/kernel/nmi.c:245
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032810-ffffffff8103289a: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031980)
Location: arch/x86/kernel/nmi.c:248
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81031980-ffffffff81031a0f: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810315d0)
Location: arch/x86/kernel/nmi.c:248
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810315d0-ffffffff8103165f: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f7e0)
Location: arch/x86/kernel/nmi.c:237
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8102f7e0-ffffffff8102f874: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810317e0)
Location: arch/x86/kernel/nmi.c:237
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810317e0-ffffffff81031874: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:237
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810329c0-ffffffff810329e9: io_check_error (STB_LOCAL)
ffffffff81032d8b-ffffffff81032e02: io_check_error.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81033d00)
Location: arch/x86/kernel/nmi.c:237
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81033d00-ffffffff81033d96: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035ee8)
Location: arch/x86/kernel/nmi.c:240
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81035af0-ffffffff81035b18: io_check_error (STB_LOCAL)
ffffffff81035ee8-ffffffff81035f5b: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036708)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810362f0-ffffffff81036318: io_check_error (STB_LOCAL)
ffffffff81036708-ffffffff8103677b: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81bbdd43)
Location: arch/x86/kernel/nmi.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810383cd-ffffffff8103844e: io_check_error.part.0 (STB_LOCAL)
ffffffff81038310-ffffffff81038338: io_check_error (STB_LOCAL)
ffffffff810384e9-ffffffff810384f9: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c36623)
Location: arch/x86/kernel/nmi.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81bd39a3-ffffffff81bd3a24: io_check_error.part.0 (STB_LOCAL)
ffffffff81038e40-ffffffff81038e68: io_check_error (STB_LOCAL)
ffffffff81bd3abf-ffffffff81bd3acf: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c28ab3)
Location: arch/x86/kernel/nmi.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81bc5e15-ffffffff81bc5e96: io_check_error.part.0 (STB_LOCAL)
ffffffff8103a950-ffffffff8103a978: io_check_error (STB_LOCAL)
ffffffff81bc5f31-ffffffff81bc5f41: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81d46c53)
Location: arch/x86/kernel/nmi.c:234
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81c98b5f-ffffffff81c98be0: io_check_error.part.0 (STB_LOCAL)
ffffffff81040330-ffffffff81040358: io_check_error (STB_LOCAL)
ffffffff81c98c7b-ffffffff81c98c8b: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81f15180)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81e481ae-ffffffff81e48236: io_check_error.part.0 (STB_LOCAL)
ffffffff81047c00-ffffffff81047c33: io_check_error (STB_LOCAL)
ffffffff81e48236-ffffffff81e48247: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81052790)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81052790-ffffffff8105283f: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810534f0)
Location: arch/x86/kernel/nmi.c:247
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810534f0-ffffffff8105359f: io_check_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a710)
Location: arch/x86/kernel/nmi.c:248
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8105a710-ffffffff8105a7bf: io_check_error (STB_LOCAL)
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
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036868)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036450-ffffffff81036478: io_check_error (STB_LOCAL)
ffffffff81036868-ffffffff810368db: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810261a8)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81025da0-ffffffff81025dc8: io_check_error (STB_LOCAL)
ffffffff810261a8-ffffffff8102621b: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810366c8)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810362b0-ffffffff810362d8: io_check_error (STB_LOCAL)
ffffffff810366c8-ffffffff8103673b: io_check_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void io_check_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810376c8)
Location: arch/x86/kernel/nmi.c:238
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810372b0-ffffffff810372d8: io_check_error (STB_LOCAL)
ffffffff810376c8-ffffffff8103773b: io_check_error.cold (STB_LOCAL)
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
