# Function: <code>pci_quirk_intel_spt_pch_acs_match</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814912ef)
Location: drivers/pci/quirks.c:4073
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
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
In drivers/pci/quirks.c (ffffffff814b2b5f)
Location: drivers/pci/quirks.c:4212
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bd0ff)
Location: drivers/pci/quirks.c:4383
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff814bcfd0-ffffffff814bd014: pci_quirk_intel_spt_pch_acs_match.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fd48f)
Location: drivers/pci/quirks.c:4403
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff814fd360-ffffffff814fd3a4: pci_quirk_intel_spt_pch_acs_match.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152dd80)
Location: drivers/pci/quirks.c:4261
Inline: True
```
**Symbols:**

```
ffffffff8152dd80-ffffffff8152dde8: pci_quirk_intel_spt_pch_acs_match.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81544bd0)
Location: drivers/pci/quirks.c:4413
Inline: True
```
**Symbols:**

```
ffffffff81544bd0-ffffffff81544c38: pci_quirk_intel_spt_pch_acs_match.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815740d0)
Location: drivers/pci/quirks.c:4431
Inline: True
```
**Symbols:**

```
ffffffff815740d0-ffffffff81574128: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81595780)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffff81595780-ffffffff815957d8: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81645f7f)
Location: drivers/pci/quirks.c:4661
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff81645b70-ffffffff81645c02: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8166c354)
Location: drivers/pci/quirks.c:4608
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff8166bf50-ffffffff8166bfd6: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8164e894)
Location: drivers/pci/quirks.c:4696
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff8164e1e0-ffffffff8164e266: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff816c0584)
Location: drivers/pci/quirks.c:4749
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff816bffb0-ffffffff816c0021: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff817e5da5)
Location: drivers/pci/quirks.c:4762
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff817e0e00-ffffffff817e0ea1: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81903ec0)
Location: drivers/pci/quirks.c:4773
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff81903ec0-ffffffff81903f61: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81947530)
Location: drivers/pci/quirks.c:4883
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff81947530-ffffffff819475aa: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_quirk_intel_spt_pch_acs_match(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81990880)
Location: drivers/pci/quirks.c:4914
Inline: False
Direct callers:
  - drivers/pci/quirks.c:pci_quirk_disable_intel_spt_pch_acs_redir
  - drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs
  - drivers/pci/quirks.c:pci_quirk_intel_spt_pch_acs
```
**Symbols:**

```
ffffffff81990880-ffffffff819908fa: pci_quirk_intel_spt_pch_acs_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fce18)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffff8000106fce18-ffff8000106fcecc: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (c089541c)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
c089541c-c08954cc: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (c00000000087b4f0)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
c00000000087b4f0-c00000000087b598: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cca00)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffe0004cca00-ffffffe0004cca8c: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81589610)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffff81589610-ffffffff81589668: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81578150)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffff81578150-ffffffff815781a8: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815894d0)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffff815894d0-ffffffff81589528: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815a3980)
Location: drivers/pci/quirks.c:4549
Inline: True
```
**Symbols:**

```
ffffffff815a3980-ffffffff815a39d8: pci_quirk_intel_spt_pch_acs_match.part.0 (STB_LOCAL)
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
