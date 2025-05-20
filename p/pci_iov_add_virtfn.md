# Function: <code>pci_iov_add_virtfn</code>

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
int pci_iov_add_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814a2d20)
Location: drivers/pci/iov.c:116
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814a2d20-ffffffff814a30ce: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814c4970)
Location: drivers/pci/iov.c:116
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814c4970-ffffffff814c4d2d: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id, int reset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff814cebf0)
Location: drivers/pci/iov.c:116
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814cebf0-ffffffff814cef30: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8150ee40)
Location: drivers/pci/iov.c:116
Inline: False
Direct callers:
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff8150ee40-ffffffff8150f167: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81543d70)
Location: drivers/pci/iov.c:138
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81543d70-ffffffff81544110: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8155b0f0)
Location: drivers/pci/iov.c:139
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8155b0f0-ffffffff8155b4a2: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158b400)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8158b400-ffffffff8158b7bc: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815acfb0)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815acfb0-ffffffff815ad36c: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81656830)
Location: drivers/pci/iov.c:160
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81656830-ffffffff81656b8b: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff81676de0)
Location: drivers/pci/iov.c:160
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff81676de0-ffffffff81677144: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816593b0)
Location: drivers/pci/iov.c:247
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff816593b0-ffffffff8165970f: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff816cb500)
Location: drivers/pci/iov.c:247
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff816cb500-ffffffff816cba05: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff817f1b90)
Location: drivers/pci/iov.c:289
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff817f1b90-ffffffff817f2098: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8191a100)
Location: drivers/pci/iov.c:289
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8191a100-ffffffff8191a608: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8195d730)
Location: drivers/pci/iov.c:289
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8195d730-ffffffff8195dc38: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff819a6d90)
Location: drivers/pci/iov.c:288
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff819a6d90-ffffffff819a7298: pci_iov_add_virtfn (STB_GLOBAL)
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
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffff800010716e90)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffff800010716e90-ffff8000107171e4: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c08a1640)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c08a1640-c08a1974: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (c0000000008878a0)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_add_virt_device
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
c0000000008878a0-c000000000887cf0: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffe0004e0202)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffe0004e0202-ffffffe0004e04f6: pci_iov_add_virtfn (STB_GLOBAL)
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
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a0780)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815a0780-ffffffff815a0b3c: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff8158f910)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff8158f910-ffffffff8158fccc: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815a0d00)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815a0d00-ffffffff815a10bc: pci_iov_add_virtfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_iov_add_virtfn(struct pci_dev *dev, int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/iov.c (ffffffff815bb130)
Location: drivers/pci/iov.c:137
Inline: False
Direct callers:
  - drivers/pci/iov.c:sriov_enable
```
**Symbols:**

```
ffffffff815bb130-ffffffff815bb4ec: pci_iov_add_virtfn (STB_GLOBAL)
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
