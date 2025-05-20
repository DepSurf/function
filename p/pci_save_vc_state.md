# Function: <code>pci_save_vc_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81441390)
Location: drivers/pci/vc.c:355
Inline: False
```
**Symbols:**

```
ffffffff81441390-ffffffff81441472: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8148d2a0)
Location: drivers/pci/vc.c:355
Inline: False
```
**Symbols:**

```
ffffffff8148d2a0-ffffffff8148d382: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814aea90)
Location: drivers/pci/vc.c:355
Inline: False
```
**Symbols:**

```
ffffffff814aea90-ffffffff814aeb72: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814b8df0)
Location: drivers/pci/vc.c:355
Inline: False
```
**Symbols:**

```
ffffffff814b8df0-ffffffff814b8ed2: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff814f9240)
Location: drivers/pci/vc.c:355
Inline: False
```
**Symbols:**

```
ffffffff814f9240-ffffffff814f9322: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81529d10)
Location: drivers/pci/vc.c:351
Inline: False
```
**Symbols:**

```
ffffffff81529d10-ffffffff81529df2: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8153fbc0)
Location: drivers/pci/vc.c:351
Inline: False
```
**Symbols:**

```
ffffffff8153fbc0-ffffffff8153fca2: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:351
Inline: False
```
**Symbols:**

```
ffffffff8156f61d-ffffffff8156f682: pci_save_vc_state.cold (STB_LOCAL)
ffffffff8156f410-ffffffff8156f498: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffff8159065d-ffffffff815906c2: pci_save_vc_state.cold (STB_LOCAL)
ffffffff81590450-ffffffff815904d8: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff8163819e-ffffffff81638203: pci_save_vc_state.cold (STB_LOCAL)
ffffffff81637f80-ffffffff8163800e: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81bf8e09-ffffffff81bf8e6e: pci_save_vc_state.cold (STB_LOCAL)
ffffffff8165c940-ffffffff8165c9d0: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81beac60-ffffffff81beacc5: pci_save_vc_state.cold (STB_LOCAL)
ffffffff8163eee0-ffffffff8163ef70: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff816afa70)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff816afa70-ffffffff816afbbb: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff817d2f90)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff817d2f90-ffffffff817d30ea: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff818f38f0)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff818f38f0-ffffffff818f3a52: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81936d40)
Location: drivers/pci/vc.c:352
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff81936d40-ffffffff81936ea2: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8197fba0)
Location: drivers/pci/vc.c:353
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_save_state
```
**Symbols:**

```
ffffffff8197fba0-ffffffff8197fd02: pci_save_vc_state (STB_GLOBAL)
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
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffff8000106f55b0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffff8000106f55b0-ffff8000106f56a8: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c0890090)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
c0890090-c089016c: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (c0000000008741d0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
c0000000008741d0-c000000000874300: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffe0004c84d4)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffe0004c84d4-ffffffe0004c85c8: pci_save_vc_state (STB_GLOBAL)
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
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffff815844dd-ffffffff81584542: pci_save_vc_state.cold (STB_LOCAL)
ffffffff815842d0-ffffffff81584358: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffff815732bd-ffffffff81573322: pci_save_vc_state.cold (STB_LOCAL)
ffffffff815730b0-ffffffff81573138: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffff815843ad-ffffffff81584412: pci_save_vc_state.cold (STB_LOCAL)
ffffffff815841a0-ffffffff81584228: pci_save_vc_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pci_save_vc_state(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:353
Inline: False
```
**Symbols:**

```
ffffffff8159e85d-ffffffff8159e8c2: pci_save_vc_state.cold (STB_LOCAL)
ffffffff8159e650-ffffffff8159e6d8: pci_save_vc_state (STB_GLOBAL)
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
