# Function: <code>msi_verify_entries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81453910)
Location: drivers/pci/msi.c:583
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff81453910-ffffffff81453966: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a0220)
Location: drivers/pci/msi.c:587
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814a0220-ffffffff814a0276: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c1da0)
Location: drivers/pci/msi.c:595
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814c1da0-ffffffff814c1df6: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc450)
Location: drivers/pci/msi.c:574
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff814cc450-ffffffff814cc4a6: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150c980)
Location: drivers/pci/msi.c:574
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff8150c980-ffffffff8150c9d6: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815417d0)
Location: drivers/pci/msi.c:574
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msix
```
**Symbols:**

```
ffffffff815417d0-ffffffff81541826: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558b20)
Location: drivers/pci/msi.c:573
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81558b20-ffffffff81558b76: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:596
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81588bc0-ffffffff81588c17: msi_verify_entries (STB_LOCAL)
ffffffff8158a91c-ffffffff8158a939: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815aa4e0-ffffffff815aa537: msi_verify_entries (STB_LOCAL)
ffffffff815ac29c-ffffffff815ac2b9: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816545c1)
Location: drivers/pci/msi.c:597
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165dca6)
Location: drivers/pci/msi.c:621
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8163ff06)
Location: drivers/pci/msi.c:612
Inline: True
Inline callers:
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msi_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0ccd)
Location: drivers/pci/msi.c:508
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:__pci_enable_msi_range
  - drivers/pci/msi.c:msix_capability_init
  - drivers/pci/msi.c:msix_capability_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi/msi.c (0)
Location: drivers/pci/msi/msi.c:401
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
  - drivers/pci/msi/msi.c:msix_capability_init
```
**Symbols:**

```
ffffffff817d3cb0-ffffffff817d3d16: msi_verify_entries (STB_LOCAL)
ffffffff81eac61f-ffffffff81eac63b: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f4bf0)
Location: drivers/pci/msi/msi.c:318
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff818f4bf0-ffffffff818f4c81: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81938020)
Location: drivers/pci/msi/msi.c:318
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81938020-ffffffff819380b1: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff81980e80)
Location: drivers/pci/msi/msi.c:319
Inline: False
Direct callers:
  - drivers/pci/msi/msi.c:__pci_enable_msix_range
  - drivers/pci/msi/msi.c:msi_capability_init
```
**Symbols:**

```
ffffffff81980e80-ffffffff81980f11: msi_verify_entries (STB_LOCAL)
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
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713a80)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffff800010713a80-ffff800010713af0: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e518)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c089e518-c089e588: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c0000000008833b0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c0000000008833b0-c000000000883440: msi_verify_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd638)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffe0004dd638-ffffffe0004dd690: msi_verify_entries (STB_LOCAL)
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
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159dcb0-ffffffff8159dd07: msi_verify_entries (STB_LOCAL)
ffffffff8159fa6c-ffffffff8159fa89: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8158ce40-ffffffff8158ce97: msi_verify_entries (STB_LOCAL)
ffffffff8158ebfc-ffffffff8158ec19: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159e230-ffffffff8159e287: msi_verify_entries (STB_LOCAL)
ffffffff8159ffec-ffffffff815a0009: msi_verify_entries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int msi_verify_entries(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/msi.c (0)
Location: drivers/pci/msi.c:597
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815b8660-ffffffff815b86b7: msi_verify_entries (STB_LOCAL)
ffffffff815ba41c-ffffffff815ba439: msi_verify_entries.cold (STB_LOCAL)
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
