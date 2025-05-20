# Function: <code>pci_iov_remove_virtfn</code>

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
void pci_iov_remove_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814a30d0)
Location: drivers/pci/iov.c:191
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814a30d0-ffffffff814a3252: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814c4d30)
Location: drivers/pci/iov.c:194
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814c4d30-ffffffff814c4eb2: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814cef30)
Location: drivers/pci/iov.c:190
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814cef30-ffffffff814cf06c: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8150f170)
Location: drivers/pci/iov.c:188
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_disable_sriov
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8150f170-ffffffff8150f280: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81544110)
Location: drivers/pci/iov.c:215
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81544110-ffffffff8154422c: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155b4b0)
Location: drivers/pci/iov.c:216
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8155b4b0-ffffffff8155b5cc: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158b7c0)
Location: drivers/pci/iov.c:214
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8158b7c0-ffffffff8158b8e4: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815ad370)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815ad370-ffffffff815ad494: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81656b90)
Location: drivers/pci/iov.c:226
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81656b90-ffffffff81656cb4: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81677150)
Location: drivers/pci/iov.c:227
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81677150-ffffffff81677274: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81659710)
Location: drivers/pci/iov.c:314
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81659710-ffffffff8165982c: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cba10)
Location: drivers/pci/iov.c:314
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff816cba10-ffffffff816cbb2c: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f20a0)
Location: drivers/pci/iov.c:356
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff817f20a0-ffffffff817f21d9: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191a620)
Location: drivers/pci/iov.c:356
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8191a620-ffffffff8191a75d: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195dc50)
Location: drivers/pci/iov.c:356
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8195dc50-ffffffff8195dd8d: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a72b0)
Location: drivers/pci/iov.c:355
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff819a72b0-ffffffff819a73ed: pci_iov_remove_virtfn (STB_GLOBAL)
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
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff8000107171e8)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffff8000107171e8-ffff800010717304: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a1974)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c08a1974-c08a1a98: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c000000000887cf0)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c000000000887cf0-c000000000887e7c: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e04f6)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffe0004e04f6-ffffffe0004e05ec: pci_iov_remove_virtfn (STB_GLOBAL)
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
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a0b40)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815a0b40-ffffffff815a0c64: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158fcd0)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8158fcd0-ffffffff8158fdf4: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a10c0)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815a10c0-ffffffff815a11e4: pci_iov_remove_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_iov_remove_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bb4f0)
Location: drivers/pci/iov.c:213
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_disable
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815bb4f0-ffffffff815bb614: pci_iov_remove_virtfn (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int reset</code>
</li>
</ul>
</details>
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
