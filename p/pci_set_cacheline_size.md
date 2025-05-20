# Function: <code>pci_set_cacheline_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434a90)
Location: drivers/pci/pci.c:3146
Inline: False
```
**Symbols:**

```
ffffffff81434a90-ffffffff81434b61: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480400)
Location: drivers/pci/pci.c:3456
Inline: False
```
**Symbols:**

```
ffffffff81480400-ffffffff814804d1: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1a50)
Location: drivers/pci/pci.c:3494
Inline: False
```
**Symbols:**

```
ffffffff814a1a50-ffffffff814a1b21: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ab670)
Location: drivers/pci/pci.c:3632
Inline: False
```
**Symbols:**

```
ffffffff814ab670-ffffffff814ab738: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ea890)
Location: drivers/pci/pci.c:3647
Inline: False
```
**Symbols:**

```
ffffffff814ea890-ffffffff814ea958: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81519d30)
Location: drivers/pci/pci.c:3831
Inline: False
```
**Symbols:**

```
ffffffff81519d30-ffffffff81519df8: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152fac0)
Location: drivers/pci/pci.c:4096
Inline: False
```
**Symbols:**

```
ffffffff8152fac0-ffffffff8152fb88: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4194
Inline: False
```
**Symbols:**

```
ffffffff815649f2-ffffffff81564a16: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff8155f2c0-ffffffff8155f361: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffff81585d22-ffffffff81585d46: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff81580400-ffffffff815804a1: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4261
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
```
**Symbols:**

```
ffffffff8162ca9f-ffffffff8162cac3: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff81625930-ffffffff816259d0: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164b780)
Location: drivers/pci/pci.c:4336
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
```
**Symbols:**

```
ffffffff8164b780-ffffffff8164b84f: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162e360)
Location: drivers/pci/pci.c:4368
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
```
**Symbols:**

```
ffffffff8162e360-ffffffff8162e42f: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169d620)
Location: drivers/pci/pci.c:4418
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_try_set_mwi
  - drivers/pci/pci.c:pcim_set_mwi
```
**Symbols:**

```
ffffffff8169d620-ffffffff8169d6ec: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bf930)
Location: drivers/pci/pci.c:4514
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_mwi
```
**Symbols:**

```
ffffffff817bf930-ffffffff817bfa00: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dbe60)
Location: drivers/pci/pci.c:4457
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_mwi
```
**Symbols:**

```
ffffffff818dbe60-ffffffff818dbf34: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191ef30)
Location: drivers/pci/pci.c:4495
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_mwi
```
**Symbols:**

```
ffffffff8191ef30-ffffffff8191f004: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81967070)
Location: drivers/pci/pci.c:4605
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_set_mwi
```
**Symbols:**

```
ffffffff81967070-ffffffff81967144: pci_set_cacheline_size (STB_GLOBAL)
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
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e2e48)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffff8000106e2e48-ffff8000106e2f30: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087ed20)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
c087ed20-c087ee0c: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085cb70)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
c00000000085cb70-c00000000085ccac: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba7ac)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffe0004ba7ac-ffffffe0004ba84c: pci_set_cacheline_size (STB_GLOBAL)
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
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffff8157a242-ffffffff8157a266: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff81574920-ffffffff815749c1: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffff81568982-ffffffff815689a6: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff81563080-ffffffff81563121: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffff81579a72-ffffffff81579a96: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff81574150-ffffffff815741f1: pci_set_cacheline_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_set_cacheline_size(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:4190
Inline: False
```
**Symbols:**

```
ffffffff81593f22-ffffffff81593f46: pci_set_cacheline_size.cold (STB_LOCAL)
ffffffff8158e630-ffffffff8158e6d1: pci_set_cacheline_size (STB_GLOBAL)
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
