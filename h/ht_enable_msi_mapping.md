# Function: <code>ht_enable_msi_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814448b0)
Location: drivers/pci/quirks.c:2359
Inline: False
```
**Symbols:**

```
ffffffff814448b0-ffffffff81444981: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81490790)
Location: drivers/pci/quirks.c:2400
Inline: False
```
**Symbols:**

```
ffffffff81490790-ffffffff81490861: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b1fe0)
Location: drivers/pci/quirks.c:2412
Inline: False
```
**Symbols:**

```
ffffffff814b1fe0-ffffffff814b20b1: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bc420)
Location: drivers/pci/quirks.c:2472
Inline: False
```
**Symbols:**

```
ffffffff814bc420-ffffffff814bc4e2: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fc7c0)
Location: drivers/pci/quirks.c:2473
Inline: False
```
**Symbols:**

```
ffffffff814fc7c0-ffffffff814fc882: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152d420)
Location: drivers/pci/quirks.c:2511
Inline: False
```
**Symbols:**

```
ffffffff8152d420-ffffffff8152d4e2: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81544270)
Location: drivers/pci/quirks.c:2552
Inline: False
```
**Symbols:**

```
ffffffff81544270-ffffffff81544332: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2567
Inline: False
```
**Symbols:**

```
ffffffff81573810-ffffffff815738b2: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81576c9f-ffffffff81576cc8: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffff81594e60-ffffffff81594f02: ht_enable_msi_mapping (STB_LOCAL)
ffffffff815983b2-ffffffff815983db: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2638
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff81643580-ffffffff81643622: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81646cae-ffffffff81646cd7: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2639
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff816699e0-ffffffff81669a86: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81bfa87f-ffffffff81bfa8a8: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2629
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff8164be80-ffffffff8164bf26: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81bec6d9-ffffffff81bec702: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2668
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff816bd8e0-ffffffff816bd986: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81ce72b8-ffffffff81ce72e1: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2681
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff817e33a0-ffffffff817e344e: ht_enable_msi_mapping (STB_LOCAL)
ffffffff81eae3a8-ffffffff81eae3d5: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff819073e0)
Location: drivers/pci/quirks.c:2683
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff819073e0-ffffffff819074c0: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194aa30)
Location: drivers/pci/quirks.c:2789
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff8194aa30-ffffffff8194ab10: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81993de0)
Location: drivers/pci/quirks.c:2803
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff81993de0-ffffffff81993ec0: ht_enable_msi_mapping (STB_LOCAL)
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
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fc1f0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffff8000106fc1f0-ffff8000106fc2dc: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c08948fc)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
c08948fc-c08949d4: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c00000000087a6f0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
c00000000087a6f0-c00000000087a82c: ht_enable_msi_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cbf70)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffe0004cbf70-ffffffe0004cc01a: ht_enable_msi_mapping (STB_LOCAL)
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
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffff81588cf0-ffffffff81588d92: ht_enable_msi_mapping (STB_LOCAL)
ffffffff8158c242-ffffffff8158c26b: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffff81577aa0-ffffffff81577b42: ht_enable_msi_mapping (STB_LOCAL)
ffffffff8157ad82-ffffffff8157adab: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffff81588bb0-ffffffff81588c52: ht_enable_msi_mapping (STB_LOCAL)
ffffffff8158c102-ffffffff8158c12b: ht_enable_msi_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ht_enable_msi_mapping(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2561
Inline: False
```
**Symbols:**

```
ffffffff815a3060-ffffffff815a3102: ht_enable_msi_mapping (STB_LOCAL)
ffffffff815a65b2-ffffffff815a65db: ht_enable_msi_mapping.cold (STB_LOCAL)
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
