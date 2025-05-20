# Function: <code>quirk_apple_mbp_poweroff</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81490990)
Location: drivers/pci/quirks.c:2804
Inline: False
```
**Symbols:**

```
ffffffff81490990-ffffffff814909d4: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b21e0)
Location: drivers/pci/quirks.c:2816
Inline: False
```
**Symbols:**

```
ffffffff814b21e0-ffffffff814b2224: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff817a8be0)
Location: arch/x86/pci/fixup.c:603
Inline: False
```
**Symbols:**

```
ffffffff817a8be0-ffffffff817a8c88: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8181fe80)
Location: arch/x86/pci/fixup.c:604
Inline: False
```
**Symbols:**

```
ffffffff8181fe80-ffffffff8181ff28: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8186a0d0)
Location: arch/x86/pci/fixup.c:604
Inline: False
```
**Symbols:**

```
ffffffff8186a0d0-ffffffff8186a179: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff8188a150)
Location: arch/x86/pci/fixup.c:604
Inline: False
```
**Symbols:**

```
ffffffff8188a150-ffffffff8188a1f9: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff818d4780-ffffffff818d4808: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff818d4ebc-ffffffff818d4eeb: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff81906b00-ffffffff81906b88: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff8190723c-ffffffff8190726b: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff81bb71f0-ffffffff81bb727e: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81bb7922-ffffffff81bb7951: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff81bcc280-ffffffff81bcc30e: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81c34504-ffffffff81c34533: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff81bbfcc0-ffffffff81bbfd4e: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81c268df-ffffffff81c2690e: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff81c8fc50-ffffffff81c8fcde: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81d44736-ffffffff81d44765: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff81e3ed70-ffffffff81e3ee20: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81f11658-ffffffff81f11687: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff82018a00)
Location: arch/x86/pci/fixup.c:619
Inline: False
```
**Symbols:**

```
ffffffff82018a00-ffffffff82018ae8: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff82098fd0)
Location: arch/x86/pci/fixup.c:620
Inline: False
```
**Symbols:**

```
ffffffff82098fd0-ffffffff820990b8: quirk_apple_mbp_poweroff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/fixup.c (ffffffff821704b0)
Location: arch/x86/pci/fixup.c:622
Inline: False
```
**Symbols:**

```
ffffffff821704b0-ffffffff82170598: quirk_apple_mbp_poweroff (STB_LOCAL)
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
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff818a5ec0-ffffffff818a5f48: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff818a65fc-ffffffff818a662b: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff818609f0-ffffffff81860a78: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff8186112c-ffffffff8186115b: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff818f7520-ffffffff818f75a8: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff818f7c5c-ffffffff818f7c8b: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void quirk_apple_mbp_poweroff(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/fixup.c (0)
Location: arch/x86/pci/fixup.c:615
Inline: False
```
**Symbols:**

```
ffffffff81918620-ffffffff819186a8: quirk_apple_mbp_poweroff (STB_LOCAL)
ffffffff81918d5c-ffffffff81918d8b: quirk_apple_mbp_poweroff.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev *dev</code>
</li>
</ul>
</details>
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
