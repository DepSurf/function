# Function: <code>old_ich_force_enable_hpet</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81035130)
Location: arch/x86/kernel/quirks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81035130-ffffffff81035278: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81034330)
Location: arch/x86/kernel/quirks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81034330-ffffffff8103447e: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81033f70)
Location: arch/x86/kernel/quirks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81033f70-ffffffff810340be: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81032080)
Location: arch/x86/kernel/quirks.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81032080-ffffffff810321be: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810343b0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff810343b0-ffffffff810344ee: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81035500)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81035500-ffffffff81035641: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810366e0)
Location: arch/x86/kernel/quirks.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff810366e0-ffffffff81036821: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:209
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff810387f0-ffffffff810388ad: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81039188-ffffffff8103921a: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81038fc0-ffffffff8103907d: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81039958-ffffffff810399ea: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff8103bac0-ffffffff8103bb7b: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff8103c4d6-ffffffff8103c568: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff8103c230-ffffffff8103c2eb: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81bd3cac-ffffffff81bd3d3e: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff8103dbc0-ffffffff8103dc7b: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81bc61a2-ffffffff81bc6234: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81043840-ffffffff810438fb: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81c9917f-ffffffff81c99211: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff8104b9b0-ffffffff8104ba86: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81e48791-ffffffff81e48823: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff810578a0)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff810578a0-ffffffff81057a00: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff81058a40)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81058a40-ffffffff81058ba0: old_ich_force_enable_hpet (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/quirks.c (ffffffff8105fc60)
Location: arch/x86/kernel/quirks.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff8105fc60-ffffffff8105fdc0: old_ich_force_enable_hpet (STB_LOCAL)
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
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81039120-ffffffff810391dd: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81039ab8-ffffffff81039b4a: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81028a30-ffffffff81028aed: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff810293c8-ffffffff8102945a: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81038f80-ffffffff8103903d: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff81039918-ffffffff810399aa: old_ich_force_enable_hpet.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void old_ich_force_enable_hpet(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/quirks.c (0)
Location: arch/x86/kernel/quirks.c:207
Inline: False
Direct callers:
  - arch/x86/kernel/quirks.c:old_ich_force_enable_hpet_user
```
**Symbols:**

```
ffffffff81039f80-ffffffff8103a03d: old_ich_force_enable_hpet (STB_LOCAL)
ffffffff8103a918-ffffffff8103a9aa: old_ich_force_enable_hpet.cold (STB_LOCAL)
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
