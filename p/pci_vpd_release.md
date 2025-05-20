# Function: <code>pci_vpd_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8142fb3c)
Location: drivers/pci/pci.h:110
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_release_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8147a6b0)
Location: drivers/pci/access.c:609
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8147a6b0-ffffffff8147a6c7: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149bb30)
Location: drivers/pci/access.c:621
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8149bb30-ffffffff8149bb47: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a5910)
Location: drivers/pci/access.c:629
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff814a5910-ffffffff814a5927: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e4750)
Location: drivers/pci/access.c:629
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff814e4750-ffffffff814e4767: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81525d70)
Location: drivers/pci/vpd.c:392
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff81525d70-ffffffff81525d87: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153bc00)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8153bc00-ffffffff8153bc17: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156b5d0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8156b5d0-ffffffff8156b5e7: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8158c5a0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8158c5a0-ffffffff8158c5b7: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81633650)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff81633650-ffffffff81633667: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff816587a0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff816587a0-ffffffff816587b7: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8163aee0)
Location: drivers/pci/vpd.c:357
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8163aee0-ffffffff8163aef7: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f16e8)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffff8000106f16e8-ffff8000106f1714: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088c1a0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
c088c1a0-c088c1c0: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086f1b0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
c00000000086f1b0-c00000000086f1e8: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c4f42)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffe0004c4f42-ffffffe0004c4f72: pci_vpd_release (STB_GLOBAL)
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
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff81580420)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff81580420-ffffffff81580437: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8156f200)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8156f200-ffffffff8156f217: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff815802f0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff815802f0-ffffffff81580307: pci_vpd_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pci_vpd_release(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8159a7a0)
Location: drivers/pci/vpd.c:395
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_release_dev
```
**Symbols:**

```
ffffffff8159a7a0-ffffffff8159a7b7: pci_vpd_release (STB_GLOBAL)
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
