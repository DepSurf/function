# Function: <code>pci_vpd_wait</code>

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
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff81479dd0)
Location: drivers/pci/access.c:355
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81479dd0-ffffffff81479ed9: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149b260)
Location: drivers/pci/access.c:367
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8149b260-ffffffff8149b360: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a5410)
Location: drivers/pci/access.c:375
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff814a5410-ffffffff814a5510: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e4250)
Location: drivers/pci/access.c:375
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff814e4250-ffffffff814e434c: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81525610)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81525610-ffffffff8152570d: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153b4a0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8153b4a0-ffffffff8153b599: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8156ae70-ffffffff8156af5e: pci_vpd_wait (STB_LOCAL)
ffffffff8156b752-ffffffff8156b76f: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8158be40-ffffffff8158bf2e: pci_vpd_wait (STB_LOCAL)
ffffffff8158c725-ffffffff8158c742: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81632d50-ffffffff81632e3e: pci_vpd_wait (STB_LOCAL)
ffffffff81633774-ffffffff81633791: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81657ea0-ffffffff81657f8e: pci_vpd_wait (STB_LOCAL)
ffffffff81bf85de-ffffffff81bf85fb: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:132
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8163a6c0-ffffffff8163a7ae: pci_vpd_wait (STB_LOCAL)
ffffffff81bea420-ffffffff81bea43d: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev, bool set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:129
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff816aaf70-ffffffff816ab02a: pci_vpd_wait (STB_LOCAL)
ffffffff81ce5282-ffffffff81ce52a0: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev, bool set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:126
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff817cdfa0-ffffffff817ce072: pci_vpd_wait (STB_LOCAL)
ffffffff81eabd1f-ffffffff81eabd3d: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev, bool set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff818ed980)
Location: drivers/pci/vpd.c:126
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff818ed980-ffffffff818eda69: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev, bool set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81930e80)
Location: drivers/pci/vpd.c:126
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81930e80-ffffffff81930f69: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev, bool set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff819798b0)
Location: drivers/pci/vpd.c:126
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff819798b0-ffffffff81979999: pci_vpd_wait (STB_LOCAL)
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
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f0ee0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffff8000106f0ee0-ffff8000106f0ffc: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088b8fc)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
c088b8fc-c088ba30: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086e5d0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
c00000000086e5d0-c00000000086e7a8: pci_vpd_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c4886)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffe0004c4886-ffffffe0004c4972: pci_vpd_wait (STB_LOCAL)
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
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8157fcc0-ffffffff8157fdae: pci_vpd_wait (STB_LOCAL)
ffffffff815805a5-ffffffff815805c2: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8156eaa0-ffffffff8156eb8e: pci_vpd_wait (STB_LOCAL)
ffffffff8156f385-ffffffff8156f3a2: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8157fb90-ffffffff8157fc7e: pci_vpd_wait (STB_LOCAL)
ffffffff81580475-ffffffff81580492: pci_vpd_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_vpd_wait(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:138
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8159a040-ffffffff8159a12e: pci_vpd_wait (STB_LOCAL)
ffffffff8159a925-ffffffff8159a942: pci_vpd_wait.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool set</code>
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
