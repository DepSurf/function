# Function: <code>pci_af_flr</code>

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
In drivers/pci/pci.c (ffffffff814382ba)
Location: drivers/pci/pci.c:3436
Inline: True
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
In drivers/pci/pci.c (ffffffff81483f58)
Location: drivers/pci/pci.c:3757
Inline: True
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
In drivers/pci/pci.c (ffffffff814a56b8)
Location: drivers/pci/pci.c:3795
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad3d0)
Location: drivers/pci/pci.c:3910
Inline: False
```
**Symbols:**

```
ffffffff814ad3d0-ffffffff814ad4a9: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec7a0)
Location: drivers/pci/pci.c:3947
Inline: False
```
**Symbols:**

```
ffffffff814ec7a0-ffffffff814ec879: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151c370)
Location: drivers/pci/pci.c:4156
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8151c370-ffffffff8151c458: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81531c50)
Location: drivers/pci/pci.c:4425
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81531c50-ffffffff81531d48: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4522
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815612e0-ffffffff815613c3: pci_af_flr (STB_LOCAL)
ffffffff81564ae8-ffffffff81564b01: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815824a0-ffffffff81582583: pci_af_flr (STB_LOCAL)
ffffffff81585e03-ffffffff81585e1c: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4548
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81627dd0-ffffffff81627f0b: pci_af_flr (STB_LOCAL)
ffffffff8162cc65-ffffffff8162cc7e: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4623
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff8164da70-ffffffff8164dbac: pci_af_flr (STB_LOCAL)
ffffffff81bf7dec-ffffffff81bf7e05: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4672
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81630600-ffffffff8163073c: pci_af_flr (STB_LOCAL)
ffffffff81be9c93-ffffffff81be9cac: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4724
Inline: False
```
**Symbols:**

```
ffffffff816a03b0-ffffffff816a04ec: pci_af_flr (STB_LOCAL)
ffffffff81ce4792-ffffffff81ce47ab: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4820
Inline: False
```
**Symbols:**

```
ffffffff817c23a0-ffffffff817c24e0: pci_af_flr (STB_LOCAL)
ffffffff81eab1bc-ffffffff81eab1d4: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dec90)
Location: drivers/pci/pci.c:4763
Inline: False
```
**Symbols:**

```
ffffffff818dec90-ffffffff818dede4: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819220f0)
Location: drivers/pci/pci.c:4801
Inline: False
```
**Symbols:**

```
ffffffff819220f0-ffffffff81922243: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, bool probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196a650)
Location: drivers/pci/pci.c:4911
Inline: False
```
**Symbols:**

```
ffffffff8196a650-ffffffff8196a7a3: pci_af_flr (STB_LOCAL)
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
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e6000)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffff8000106e6000-ffff8000106e6104: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881324)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c0881324-c0881438: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008600f0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
c0000000008600f0-c000000000860238: pci_af_flr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bcb7c)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffe0004bcb7c-ffffffe0004bcc54: pci_af_flr (STB_LOCAL)
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
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815769c0-ffffffff81576aa3: pci_af_flr (STB_LOCAL)
ffffffff8157a323-ffffffff8157a33c: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff81565120-ffffffff81565203: pci_af_flr (STB_LOCAL)
ffffffff81568a63-ffffffff81568a7c: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815761f0-ffffffff815762d3: pci_af_flr (STB_LOCAL)
ffffffff81579b53-ffffffff81579b6c: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_af_flr(struct pci_dev *dev, int probe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4518
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_probe_reset_function
```
**Symbols:**

```
ffffffff815906d0-ffffffff815907b3: pci_af_flr (STB_LOCAL)
ffffffff81594003-ffffffff8159401c: pci_af_flr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int probe</code> ➡️ <code>bool probe</code>
</li>
</ul>
</details>
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
