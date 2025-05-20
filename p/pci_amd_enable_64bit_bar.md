# Function: <code>pci_amd_enable_64bit_bar</code>

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
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff81820160)
Location: arch/x86/pci/fixup.c:663
Inline: False
```
**Symbols:**

```
ffffffff81820160-ffffffff81820370: pci_amd_enable_64bit_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8186a380)
Location: arch/x86/pci/fixup.c:667
Inline: False
```
**Symbols:**

```
ffffffff8186a380-ffffffff8186a59d: pci_amd_enable_64bit_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8188a200)
Location: arch/x86/pci/fixup.c:677
Inline: False
```
**Symbols:**

```
ffffffff8188a200-ffffffff8188a41d: pci_amd_enable_64bit_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff818d4810-ffffffff818d49f4: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff818d4eeb-ffffffff818d4f25: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff81906b90-ffffffff81906d74: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff8190726b-ffffffff819072a5: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff81bb74d0-ffffffff81bb76ae: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81bb79aa-ffffffff81bb79e4: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff81bcc560-ffffffff81bcc73e: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81c3458c-ffffffff81c345c6: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff81bbffa0-ffffffff81bc017d: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81c26968-ffffffff81c269a2: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff81c8ff30-ffffffff81c9010d: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81d447bf-ffffffff81d447f9: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff81e3f010-ffffffff81e3f20e: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81f116ca-ffffffff81f11704: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff82018d80)
Location: arch/x86/pci/fixup.c:692
Inline: False
```
**Symbols:**

```
ffffffff82018d80-ffffffff82018fb8: pci_amd_enable_64bit_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff82099410)
Location: arch/x86/pci/fixup.c:693
Inline: False
```
**Symbols:**

```
ffffffff82099410-ffffffff82099643: pci_amd_enable_64bit_bar (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff821709c0)
Location: arch/x86/pci/fixup.c:695
Inline: False
```
**Symbols:**

```
ffffffff821709c0-ffffffff82170c22: pci_amd_enable_64bit_bar (STB_LOCAL)
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
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff818a5f50-ffffffff818a6134: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff818a662b-ffffffff818a6665: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff81860a80-ffffffff81860c64: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff8186115b-ffffffff81861195: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff818f75b0-ffffffff818f7794: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff818f7c8b-ffffffff818f7cc5: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_amd_enable_64bit_bar(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:688
Inline: False
```
**Symbols:**

```
ffffffff819186b0-ffffffff81918894: pci_amd_enable_64bit_bar (STB_LOCAL)
ffffffff81918d8b-ffffffff81918dc5: pci_amd_enable_64bit_bar.cold (STB_LOCAL)
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
