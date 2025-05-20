# Function: <code>pci_serr_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81032720)
Location: arch/x86/kernel/nmi.c:213
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032720-ffffffff81032790: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81031870)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81031870-ffffffff810318ed: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810314c0)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810314c0-ffffffff8103153d: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8102f6e0)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8102f6e0-ffffffff8102f74f: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810316e0)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810316e0-ffffffff8103174f: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (0)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81032960-ffffffff81032989: pci_serr_error (STB_LOCAL)
ffffffff81032ce6-ffffffff81032d33: pci_serr_error.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81034096)
Location: arch/x86/kernel/nmi.c:216
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81033c20-ffffffff81033c7f: pci_serr_error (STB_LOCAL)
ffffffff81034096-ffffffff810340b2: pci_serr_error.cold.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81035e46)
Location: arch/x86/kernel/nmi.c:219
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81035a90-ffffffff81035ab8: pci_serr_error (STB_LOCAL)
ffffffff81035e46-ffffffff81035e91: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036666)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036290-ffffffff810362b8: pci_serr_error (STB_LOCAL)
ffffffff81036666-ffffffff810366b1: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81bbddb2)
Location: arch/x86/kernel/nmi.c:213
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81038372-ffffffff810383cd: pci_serr_error.part.0 (STB_LOCAL)
ffffffff810382b0-ffffffff810382d8: pci_serr_error (STB_LOCAL)
ffffffff81038482-ffffffff81038492: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c36692)
Location: arch/x86/kernel/nmi.c:213
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81bd3948-ffffffff81bd39a3: pci_serr_error.part.0 (STB_LOCAL)
ffffffff81038de0-ffffffff81038e08: pci_serr_error (STB_LOCAL)
ffffffff81bd3a58-ffffffff81bd3a68: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81c28b22)
Location: arch/x86/kernel/nmi.c:213
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81bc5dba-ffffffff81bc5e15: pci_serr_error.part.0 (STB_LOCAL)
ffffffff8103a8f0-ffffffff8103a918: pci_serr_error (STB_LOCAL)
ffffffff81bc5eca-ffffffff81bc5eda: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81d46cc2)
Location: arch/x86/kernel/nmi.c:213
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81c98b04-ffffffff81c98b5f: pci_serr_error.part.0 (STB_LOCAL)
ffffffff810402d0-ffffffff810402f8: pci_serr_error (STB_LOCAL)
ffffffff81c98c14-ffffffff81c98c24: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81f1520c)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Inline callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81e480ea-ffffffff81e48151: pci_serr_error.part.0 (STB_LOCAL)
ffffffff81047b80-ffffffff81047bb3: pci_serr_error (STB_LOCAL)
ffffffff81e48151-ffffffff81e48162: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81052650)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81052650-ffffffff810526db: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810533b0)
Location: arch/x86/kernel/nmi.c:226
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810533b0-ffffffff8105343b: pci_serr_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff8105a5d0)
Location: arch/x86/kernel/nmi.c:227
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff8105a5d0-ffffffff8105a65b: pci_serr_error (STB_LOCAL)
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
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff810367c6)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff810363f0-ffffffff81036418: pci_serr_error (STB_LOCAL)
ffffffff810367c6-ffffffff81036811: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81026106)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81025d40-ffffffff81025d68: pci_serr_error (STB_LOCAL)
ffffffff81026106-ffffffff81026151: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81036626)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81036250-ffffffff81036278: pci_serr_error (STB_LOCAL)
ffffffff81036626-ffffffff81036671: pci_serr_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_serr_error(unsigned char reason, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/nmi.c (ffffffff81037626)
Location: arch/x86/kernel/nmi.c:217
Inline: True
Direct callers:
  - arch/x86/kernel/nmi.c:default_do_nmi
```
**Symbols:**

```
ffffffff81037250-ffffffff81037278: pci_serr_error (STB_LOCAL)
ffffffff81037626-ffffffff81037671: pci_serr_error.cold (STB_LOCAL)
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
