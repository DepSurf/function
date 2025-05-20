# Function: <code>pci_msi_vec_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814537b0)
Location: drivers/pci/msi.c:861
Inline: False
Direct callers:
  - drivers/pci/msi.c:pci_enable_msi_range
```
**Symbols:**

```
ffffffff814537b0-ffffffff81453812: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a0050)
Location: drivers/pci/msi.c:875
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814a0050-ffffffff814a00b2: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c1bd0)
Location: drivers/pci/msi.c:889
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814c1bd0-ffffffff814c1c32: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814cc240)
Location: drivers/pci/msi.c:865
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff814cc240-ffffffff814cc29e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8150c770)
Location: drivers/pci/msi.c:865
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8150c770-ffffffff8150c7ce: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815415b0)
Location: drivers/pci/msi.c:865
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815415b0-ffffffff8154160e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81558910)
Location: drivers/pci/msi.c:864
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81558910-ffffffff8155896e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815889a0)
Location: drivers/pci/msi.c:899
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815889a0-ffffffff815889fe: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815aa2c0)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815aa2c0-ffffffff815aa31e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816540d4)
Location: drivers/pci/msi.c:900
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81653260-ffffffff816532be: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8165e524)
Location: drivers/pci/msi.c:924
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8165cf90-ffffffff8165cfee: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81640944)
Location: drivers/pci/msi.c:933
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8163f530-ffffffff8163f58e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff816b0b95)
Location: drivers/pci/msi.c:843
Inline: True
Inline callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff816b03c0-ffffffff816b041e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff817d40b0)
Location: drivers/pci/msi/msi.c:720
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff817d39a0-ffffffff817d3a10: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff818f555f)
Location: drivers/pci/msi/msi.c:472
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff818f48f0-ffffffff818f4960: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff8193898f)
Location: drivers/pci/msi/msi.c:472
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81937d20-ffffffff81937d90: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi/msi.c (ffffffff819817ef)
Location: drivers/pci/msi/msi.c:473
Inline: True
Inline callers:
  - drivers/pci/msi/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff81980b80-ffffffff81980bf0: pci_msi_vec_count (STB_GLOBAL)
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
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffff800010713808)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_vec_count
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffff800010713808-ffff800010713884: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c089e41c)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_vec_count
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c089e41c-c089e49c: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (c0000000008830e0)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
c0000000008830e0-c000000000883178: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffe0004dd5aa)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffe0004dd5aa-ffffffe0004dd5f4: pci_msi_vec_count (STB_GLOBAL)
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
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159da90)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159da90-ffffffff8159daee: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8158cc20)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8158cc20-ffffffff8158cc7e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff8159e010)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff8159e010-ffffffff8159e06e: pci_msi_vec_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_msi_vec_count(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff815b8440)
Location: drivers/pci/msi.c:900
Inline: False
Direct callers:
  - drivers/pci/msi.c:__pci_enable_msi_range
```
**Symbols:**

```
ffffffff815b8440-ffffffff815b849e: pci_msi_vec_count (STB_GLOBAL)
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
