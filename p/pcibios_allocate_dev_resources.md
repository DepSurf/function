# Function: <code>pcibios_allocate_dev_resources</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff816f6159)
Location: arch/x86/pci/i386.c:248
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8175ae11)
Location: arch/x86/pci/i386.c:248
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8178737c)
Location: arch/x86/pci/i386.c:248
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff817a656d)
Location: arch/x86/pci/i386.c:248
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8181d80d)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81867a4d)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff81887a8d)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818d23fd)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff819047ad)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
```
**Symbols:**

```
ffffffff81bb4b90-ffffffff81bb4dc5: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff81bb5106-ffffffff81bb5121: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
```
**Symbols:**

```
ffffffff81bc9df0-ffffffff81bca025: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff81c33fa4-ffffffff81c33fbf: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
```
**Symbols:**

```
ffffffff81bbd630-ffffffff81bbd976: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff81c26331-ffffffff81c26354: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
```
**Symbols:**

```
ffffffff81c8d540-ffffffff81c8d8a5: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff81d4407d-ffffffff81d440c5: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
```
**Symbols:**

```
ffffffff81e3c420-ffffffff81e3c7d3: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff81f10ec4-ffffffff81f10f26: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
```
**Symbols:**

```
ffffffff820155b0-ffffffff82015985: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff820b7174-ffffffff820b71a7: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
```
**Symbols:**

```
ffffffff82095900-ffffffff82095d4d: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff8213851b-ffffffff82138546: pcibios_allocate_dev_resources.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcibios_allocate_dev_resources(struct pci_dev *dev, int pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/i386.c (0)
Location: arch/x86/pci/i386.c:249
Inline: False
Direct callers:
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
  - arch/x86/pci/i386.c:pcibios_resource_survey_bus
```
**Symbols:**

```
ffffffff8216cde0-ffffffff8216d256: pcibios_allocate_dev_resources (STB_LOCAL)
ffffffff8221a44c-ffffffff8221a477: pcibios_allocate_dev_resources.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818a3bdd)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8185f34d)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff818f51cd)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/pci/i386.c (ffffffff8191626d)
Location: arch/x86/pci/i386.c:249
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_resources
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
