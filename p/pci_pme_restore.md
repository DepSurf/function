# Function: <code>pci_pme_restore</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae230)
Location: drivers/pci/pci.c:1808
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff814ae230-ffffffff814ae2c5: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed610)
Location: drivers/pci/pci.c:1811
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff814ed610-ffffffff814ed6a5: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d260)
Location: drivers/pci/pci.c:1875
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff8151d260-ffffffff8151d2f1: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532960)
Location: drivers/pci/pci.c:2048
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_default_resume_early
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81532960-ffffffff815329f1: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81562060)
Location: drivers/pci/pci.c:2128
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81562060-ffffffff815620f7: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81583200)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81583200-ffffffff81583297: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81629de0)
Location: drivers/pci/pci.c:2194
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81629de0-ffffffff81629e75: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81650210)
Location: drivers/pci/pci.c:2338
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81650210-ffffffff816502a5: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81632dd0)
Location: drivers/pci/pci.c:2368
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81632dd0-ffffffff81632e65: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a2f40)
Location: drivers/pci/pci.c:2399
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff816a2f40-ffffffff816a2fd5: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c5120)
Location: drivers/pci/pci.c:2461
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff817c5120-ffffffff817c51c2: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e21c0)
Location: drivers/pci/pci.c:2435
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff818e21c0-ffffffff818e2262: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925600)
Location: drivers/pci/pci.c:2473
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff81925600-ffffffff819256a2: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196dd80)
Location: drivers/pci/pci.c:2586
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
  - drivers/pci/pci-driver.c:pci_pm_restore
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
```
**Symbols:**

```
ffffffff8196dd80-ffffffff8196de22: pci_pme_restore (STB_GLOBAL)
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
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e7058)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffff8000106e7058-ffff8000106e7104: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088228c)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
c088228c-c088232c: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008616b0)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
c0000000008616b0-c000000000861790: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd8e0)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_runtime_resume
```
**Symbols:**

```
ffffffe0004bd8e0-ffffffe0004bd964: pci_pme_restore (STB_GLOBAL)
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
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81577720)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81577720-ffffffff815777b7: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565e80)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81565e80-ffffffff81565f17: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576f50)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81576f50-ffffffff81576fe7: pci_pme_restore (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_pme_restore(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81591430)
Location: drivers/pci/pci.c:2124
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_pm_restore_noirq
  - drivers/pci/pci-driver.c:pci_pm_resume_noirq
  - drivers/pci/pci-driver.c:pci_restore_standard_config
```
**Symbols:**

```
ffffffff81591430-ffffffff815914c7: pci_pme_restore (STB_GLOBAL)
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
