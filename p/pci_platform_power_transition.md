# Function: <code>pci_platform_power_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814364f0)
Location: drivers/pci/pci.c:728
Inline: True
Direct callers:
  - drivers/pci/pci.c:__pci_complete_power_transition
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff814364f0-ffffffff81436575: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482040)
Location: drivers/pci/pci.c:749
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff81482040-ffffffff814820ce: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a35d0)
Location: drivers/pci/pci.c:774
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff814a35d0-ffffffff814a365e: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad5c0)
Location: drivers/pci/pci.c:769
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff814ad5c0-ffffffff814ad643: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec990)
Location: drivers/pci/pci.c:770
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff814ec990-ffffffff814eca1f: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c570)
Location: drivers/pci/pci.c:782
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff8151c570-ffffffff8151c5ff: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531e60)
Location: drivers/pci/pci.c:953
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff81531e60-ffffffff81531ef0: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815614e0)
Location: drivers/pci/pci.c:979
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff815614e0-ffffffff81561577: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582690)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff81582690-ffffffff81582727: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81628fe0)
Location: drivers/pci/pci.c:1019
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81628fe0-ffffffff81629077: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164f230)
Location: drivers/pci/pci.c:1159
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff8164f230-ffffffff8164f2c7: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81631d00)
Location: drivers/pci/pci.c:1189
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81631d00-ffffffff81631d97: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a1620)
Location: drivers/pci/pci.c:1199
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff816a1620-ffffffff816a16b7: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c374a)
Location: drivers/pci/pci.c:1135
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff817c33c0-ffffffff817c3425: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e05da)
Location: drivers/pci/pci.c:1119
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff818e01b0-ffffffff818e0215: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81923a17)
Location: drivers/pci/pci.c:1133
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:pci_set_power_state
```
**Symbols:**

```
ffffffff81923610-ffffffff81923675: pci_platform_power_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196c04c)
Location: drivers/pci/pci.c:1196
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/pci.c:__pci_set_power_state
```
**Symbols:**

```
ffffffff8196bc30-ffffffff8196bc95: pci_platform_power_transition (STB_GLOBAL)
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
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6240)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffff8000106e6240-ffff8000106e62f0: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881584)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
c0881584-c088161c: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008603d0)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
c0000000008603d0-c000000000860500: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bcd24)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffe0004bcd24-ffffffe0004bcda6: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576bb0)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff81576bb0-ffffffff81576c47: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565310)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff81565310-ffffffff815653a7: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815763e0)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff815763e0-ffffffff81576477: pci_platform_power_transition (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_platform_power_transition(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815908c0)
Location: drivers/pci/pci.c:966
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_power_up
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/pci.c:__pci_complete_power_transition
```
**Symbols:**

```
ffffffff815908c0-ffffffff81590957: pci_platform_power_transition (STB_LOCAL)
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
