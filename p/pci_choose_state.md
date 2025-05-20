# Function: <code>pci_choose_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81433f30)
Location: drivers/pci/pci.c:908
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81433f30-ffffffff81433fa6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147f8d0)
Location: drivers/pci/pci.c:929
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff8147f8d0-ffffffff8147f94c: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a0f20)
Location: drivers/pci/pci.c:954
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff814a0f20-ffffffff814a0f9c: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aaba0)
Location: drivers/pci/pci.c:950
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff814aaba0-ffffffff814aac1a: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e9dc0)
Location: drivers/pci/pci.c:953
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff814e9dc0-ffffffff814e9e40: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815194f0)
Location: drivers/pci/pci.c:965
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff815194f0-ffffffff8151956a: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152ef50)
Location: drivers/pci/pci.c:1136
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff8152ef50-ffffffff8152efca: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1165
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff8156496d-ffffffff81564985: pci_choose_state.cold (STB_LOCAL)
ffffffff8155e6c0-ffffffff8155e736: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1161
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81585c6d-ffffffff81585c85: pci_choose_state.cold (STB_LOCAL)
ffffffff8157f730-ffffffff8157f7a6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1226
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff8162c9ea-ffffffff8162ca02: pci_choose_state.cold (STB_LOCAL)
ffffffff81624d00-ffffffff81624d76: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1360
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81bf7bc5-ffffffff81bf7bdd: pci_choose_state.cold (STB_LOCAL)
ffffffff8164a930-ffffffff8164a9a6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1390
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81be9a6c-ffffffff81be9a84: pci_choose_state.cold (STB_LOCAL)
ffffffff8162d510-ffffffff8162d586: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1400
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81ce440c-ffffffff81ce4424: pci_choose_state.cold (STB_LOCAL)
ffffffff8169c950-ffffffff8169c9c6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0c40)
Location: drivers/pci/pci.c:2936
Inline: True
```
**Symbols:**

```
ffffffff817c0c40-ffffffff817c0c69: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd520)
Location: drivers/pci/pci.c:2886
Inline: True
```
**Symbols:**

```
ffffffff818dd520-ffffffff818dd549: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920a80)
Location: drivers/pci/pci.c:2924
Inline: True
```
**Symbols:**

```
ffffffff81920a80-ffffffff81920aa9: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968c20)
Location: drivers/pci/pci.c:3037
Inline: True
```
**Symbols:**

```
ffffffff81968c20-ffffffff81968c49: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2188)
Location: drivers/pci/pci.c:1161
Inline: False
```
**Symbols:**

```
ffff8000106e2188-ffff8000106e2244: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087de30)
Location: drivers/pci/pci.c:1161
Inline: False
```
**Symbols:**

```
c087de30-c087dedc: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085b880)
Location: drivers/pci/pci.c:1161
Inline: False
```
**Symbols:**

```
c00000000085b880-c00000000085b998: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b9c66)
Location: drivers/pci/pci.c:1161
Inline: False
```
**Symbols:**

```
ffffffe0004b9c66-ffffffe0004b9d0e: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1161
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff8157a18d-ffffffff8157a1a5: pci_choose_state.cold (STB_LOCAL)
ffffffff81573c50-ffffffff81573cc6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1161
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff815688cd-ffffffff815688e5: pci_choose_state.cold (STB_LOCAL)
ffffffff815623b0-ffffffff81562426: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1161
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff815799bd-ffffffff815799d5: pci_choose_state.cold (STB_LOCAL)
ffffffff81573480-ffffffff815734f6: pci_choose_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
pci_power_t pci_choose_state(struct pci_dev *dev, pm_message_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1161
Inline: False
Direct callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_suspend
```
**Symbols:**

```
ffffffff81593e6d-ffffffff81593e85: pci_choose_state.cold (STB_LOCAL)
ffffffff8158d960-ffffffff8158d9d6: pci_choose_state (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
