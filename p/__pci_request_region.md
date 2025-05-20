# Function: <code>__pci_request_region</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434810)
Location: drivers/pci/pci.c:2833
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_request_region
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:__pci_request_selected_regions
```
**Symbols:**

```
ffffffff81434810-ffffffff8143494e: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480190)
Location: drivers/pci/pci.c:3011
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81480190-ffffffff814802b3: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a17e0)
Location: drivers/pci/pci.c:3049
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff814a17e0-ffffffff814a1907: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab370)
Location: drivers/pci/pci.c:3066
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff814ab370-ffffffff814ab48c: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea590)
Location: drivers/pci/pci.c:3176
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff814ea590-ffffffff814ea6ab: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151ac90)
Location: drivers/pci/pci.c:3322
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8151ac90-ffffffff8151ad6d: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815309f0)
Location: drivers/pci/pci.c:3587
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region_exclusive
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff815309f0-ffffffff81530ad4: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3708
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81560370-ffffffff8156043a: __pci_request_region (STB_LOCAL)
ffffffff81564a43-ffffffff81564a70: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81581490-ffffffff8158155a: __pci_request_region (STB_LOCAL)
ffffffff81585d5e-ffffffff81585d8b: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3774
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81626060-ffffffff81626137: __pci_request_region (STB_LOCAL)
ffffffff8162cb0e-ffffffff8162cb3a: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3838
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8164bd70-ffffffff8164be47: __pci_request_region (STB_LOCAL)
ffffffff81bf7c95-ffffffff81bf7cc1: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3869
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8162e9f0-ffffffff8162eacf: __pci_request_region (STB_LOCAL)
ffffffff81be9b3c-ffffffff81be9b68: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3919
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8169de50-ffffffff8169e183: __pci_request_region (STB_LOCAL)
ffffffff81ce44c9-ffffffff81ce44ea: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4013
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff817c0060-ffffffff817c03a5: __pci_request_region (STB_LOCAL)
ffffffff81eaaeee-ffffffff81eaaf0f: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3956
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff818dc6b0-ffffffff818dc9f5: __pci_request_region (STB_LOCAL)
ffffffff8208efc4-ffffffff8208efe5: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3994
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8191f9e0-ffffffff8191fcdd: __pci_request_region (STB_LOCAL)
ffffffff8210f30c-ffffffff8210f32d: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4108
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81967b60-ffffffff81967eb2: __pci_request_region (STB_LOCAL)
ffffffff821ecfb4-ffffffff821ecfd5: __pci_request_region.cold (STB_LOCAL)
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
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e44a0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffff8000106e44a0-ffff8000106e45ac: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08802b4)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
c08802b4-c08803bc: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085eaa0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
c00000000085eaa0-c00000000085ec40: __pci_request_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb9b8)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffe0004bb9b8-ffffffe0004bbaa6: __pci_request_region (STB_LOCAL)
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
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff815759b0-ffffffff81575a7a: __pci_request_region (STB_LOCAL)
ffffffff8157a27e-ffffffff8157a2ab: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff81564110-ffffffff815641da: __pci_request_region (STB_LOCAL)
ffffffff815689be-ffffffff815689eb: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff815751e0-ffffffff815752aa: __pci_request_region (STB_LOCAL)
ffffffff81579aae-ffffffff81579adb: __pci_request_region.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __pci_request_region(struct pci_dev *pdev, int bar, const char *res_name, int exclusive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3704
Inline: False
Direct callers:
  - drivers/pci/pci.c:__pci_request_selected_regions
  - drivers/pci/pci.c:pci_request_region
```
**Symbols:**

```
ffffffff8158f7b0-ffffffff8158f87a: __pci_request_region (STB_LOCAL)
ffffffff81593f5e-ffffffff81593f8b: __pci_request_region.cold (STB_LOCAL)
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
