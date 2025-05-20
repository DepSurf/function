# Function: <code>msi_ht_cap_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81444770)
Location: drivers/pci/quirks.c:2300
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff81444770-ffffffff81444835: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81490650)
Location: drivers/pci/quirks.c:2341
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff81490650-ffffffff81490715: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814b1ea0)
Location: drivers/pci/quirks.c:2353
Inline: False
Direct callers:
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff814b1ea0-ffffffff814b1f65: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814bc360)
Location: drivers/pci/quirks.c:2413
Inline: False
```
**Symbols:**

```
ffffffff814bc360-ffffffff814bc41d: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff814fc700)
Location: drivers/pci/quirks.c:2414
Inline: False
```
**Symbols:**

```
ffffffff814fc700-ffffffff814fc7bd: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8152d360)
Location: drivers/pci/quirks.c:2450
Inline: False
```
**Symbols:**

```
ffffffff8152d360-ffffffff8152d41d: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff815441b0)
Location: drivers/pci/quirks.c:2491
Inline: False
```
**Symbols:**

```
ffffffff815441b0-ffffffff8154426d: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2506
Inline: False
```
**Symbols:**

```
ffffffff81573770-ffffffff81573802: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81576c6a-ffffffff81576c9f: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81594dc0-ffffffff81594e52: msi_ht_cap_enabled (STB_LOCAL)
ffffffff8159837d-ffffffff815983b2: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2577
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff816434e0-ffffffff81643572: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81646c79-ffffffff81646cae: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2578
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
```
**Symbols:**

```
ffffffff81669940-ffffffff816699d6: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81bfa84a-ffffffff81bfa87f: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2575
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff8164bde0-ffffffff8164be76: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81bec6a4-ffffffff81bec6d9: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2614
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff816bd840-ffffffff816bd8d6: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81ce7283-ffffffff81ce72b8: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2627
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff817e32f0-ffffffff817e3396: msi_ht_cap_enabled (STB_LOCAL)
ffffffff81eae373-ffffffff81eae3a8: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff819072f0)
Location: drivers/pci/quirks.c:2629
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff819072f0-ffffffff819073c4: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff8194a940)
Location: drivers/pci/quirks.c:2735
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff8194a940-ffffffff8194aa14: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffff81993cf0)
Location: drivers/pci/quirks.c:2749
Inline: False
Direct callers:
  - drivers/pci/quirks.c:nv_ht_enable_msi_mapping
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
  - drivers/pci/quirks.c:quirk_nvidia_ck804_msi_ht_cap
```
**Symbols:**

```
ffffffff81993cf0-ffffffff81993dc4: msi_ht_cap_enabled (STB_LOCAL)
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
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffff8000106fc110)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffff8000106fc110-ffff8000106fc1f0: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c089481c)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
c089481c-c08948fc: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (c00000000087a5c0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
c00000000087a5c0-c00000000087a6ec: msi_ht_cap_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/quirks.c (ffffffe0004cbec8)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffe0004cbec8-ffffffe0004cbf70: msi_ht_cap_enabled (STB_LOCAL)
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
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81588c50-ffffffff81588ce2: msi_ht_cap_enabled (STB_LOCAL)
ffffffff8158c20d-ffffffff8158c242: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81577a00-ffffffff81577a92: msi_ht_cap_enabled (STB_LOCAL)
ffffffff8157ad4d-ffffffff8157ad82: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffff81588b10-ffffffff81588ba2: msi_ht_cap_enabled (STB_LOCAL)
ffffffff8158c0cd-ffffffff8158c102: msi_ht_cap_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int msi_ht_cap_enabled(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/quirks.c (0)
Location: drivers/pci/quirks.c:2500
Inline: False
```
**Symbols:**

```
ffffffff815a2fc0-ffffffff815a3052: msi_ht_cap_enabled (STB_LOCAL)
ffffffff815a657d-ffffffff815a65b2: msi_ht_cap_enabled.cold (STB_LOCAL)
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
