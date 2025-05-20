# Function: <code>pci_acs_flags_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435cd0)
Location: drivers/pci/pci.c:2596
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81435cd0-ffffffff81435d78: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81481810)
Location: drivers/pci/pci.c:2774
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81481810-ffffffff814818be: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2ce0)
Location: drivers/pci/pci.c:2812
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff814a2ce0-ffffffff814a2d8e: pci_acs_flags_enabled (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff814aefec)
Location: drivers/pci/pci.c:2829
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff814acad0-ffffffff814acb66: pci_acs_flags_enabled.part.21 (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff814ee3bc)
Location: drivers/pci/pci.c:2838
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_acs_enabled
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff814ebdd0-ffffffff814ebe66: pci_acs_flags_enabled.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b830)
Location: drivers/pci/pci.c:2909
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8151b830-ffffffff8151b8d7: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815315b0)
Location: drivers/pci/pci.c:3174
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff815315b0-ffffffff81531657: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155ff00)
Location: drivers/pci/pci.c:3294
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8155ff00-ffffffff8155ffa2: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81581030)
Location: drivers/pci/pci.c:3290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81581030-ffffffff815810d2: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816267c0)
Location: drivers/pci/pci.c:3360
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff816267c0-ffffffff81626864: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164a320)
Location: drivers/pci/pci.c:3400
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8164a320-ffffffff8164a3a4: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162cf10)
Location: drivers/pci/pci.c:3430
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8162cf10-ffffffff8162cf94: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169c1d0)
Location: drivers/pci/pci.c:3472
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8169c1d0-ffffffff8169c254: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bdb50)
Location: drivers/pci/pci.c:3566
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff817bdb50-ffffffff817bdbf2: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818d9d80)
Location: drivers/pci/pci.c:3509
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff818d9d80-ffffffff818d9e22: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191d0d0)
Location: drivers/pci/pci.c:3547
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8191d0d0-ffffffff8191d172: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81965500)
Location: drivers/pci/pci.c:3662
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81965500-ffffffff819655a2: pci_acs_flags_enabled (STB_LOCAL)
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
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3f70)
Location: drivers/pci/pci.c:3290
Inline: False
```
**Symbols:**

```
ffff8000106e3f70-ffff8000106e4028: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087fdb4)
Location: drivers/pci/pci.c:3290
Inline: False
```
**Symbols:**

```
c087fdb4-c087fe6c: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085e290)
Location: drivers/pci/pci.c:3290
Inline: False
```
**Symbols:**

```
c00000000085e290-c00000000085e3a4: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb34e)
Location: drivers/pci/pci.c:3290
Inline: False
```
**Symbols:**

```
ffffffe0004bb34e-ffffffe0004bb3e4: pci_acs_flags_enabled (STB_LOCAL)
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
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575550)
Location: drivers/pci/pci.c:3290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81575550-ffffffff815755f2: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563cb0)
Location: drivers/pci/pci.c:3290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81563cb0-ffffffff81563d52: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574d80)
Location: drivers/pci/pci.c:3290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff81574d80-ffffffff81574e22: pci_acs_flags_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pci_acs_flags_enabled(struct pci_dev *pdev, u16 acs_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f350)
Location: drivers/pci/pci.c:3290
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_acs_enabled
```
**Symbols:**

```
ffffffff8158f350-ffffffff8158f3f2: pci_acs_flags_enabled (STB_LOCAL)
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
