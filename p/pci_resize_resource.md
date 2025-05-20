# Function: <code>pci_resize_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f4630)
Location: drivers/pci/setup-res.c:412
Inline: False
```
**Symbols:**

```
ffffffff814f4630-ffffffff814f4784: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff815246e0)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff815246e0-ffffffff81524837: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153a560)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff8153a560-ffffffff8153a6b7: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81569f10)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff81569f10-ffffffff8156a064: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8158aee0)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff8158aee0-ffffffff8158b034: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81632030)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff81632030-ffffffff81632179: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81657630)
Location: drivers/pci/setup-res.c:410
Inline: False
```
**Symbols:**

```
ffffffff81657630-ffffffff81657792: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81639fb0)
Location: drivers/pci/setup-res.c:410
Inline: False
```
**Symbols:**

```
ffffffff81639fb0-ffffffff8163a10f: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:410
Inline: False
```
**Symbols:**

```
ffffffff81ce4f93-ffffffff81ce4fff: pci_resize_resource.cold (STB_LOCAL)
ffffffff816aa790-ffffffff816aa920: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:414
Inline: False
```
**Symbols:**

```
ffffffff81eaba22-ffffffff81eaba8e: pci_resize_resource.cold (STB_LOCAL)
ffffffff817cd6a0-ffffffff817cd84d: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:425
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff8208f3a6-ffffffff8208f412: pci_resize_resource.cold (STB_LOCAL)
ffffffff818eccb0-ffffffff818ece5d: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:425
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff8210f70c-ffffffff8210f778: pci_resize_resource.cold (STB_LOCAL)
ffffffff81930190-ffffffff81930332: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (0)
Location: drivers/pci/setup-res.c:430
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:resource5_resize_store
  - drivers/pci/pci-sysfs.c:resource4_resize_store
  - drivers/pci/pci-sysfs.c:resource3_resize_store
  - drivers/pci/pci-sysfs.c:resource2_resize_store
  - drivers/pci/pci-sysfs.c:resource1_resize_store
  - drivers/pci/pci-sysfs.c:resource0_resize_store
```
**Symbols:**

```
ffffffff821ed3a1-ffffffff821ed40d: pci_resize_resource.cold (STB_LOCAL)
ffffffff81978b30-ffffffff81978cd2: pci_resize_resource (STB_GLOBAL)
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
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106efc48)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffff8000106efc48-ffff8000106efdc0: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088a7f8)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
c088a7f8-c088a954: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086cf60)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
c00000000086cf60-c00000000086d170: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c39b8)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffe0004c39b8-ffffffe0004c3ac2: pci_resize_resource (STB_GLOBAL)
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
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157ed60)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff8157ed60-ffffffff8157eeb4: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8156db40)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff8156db40-ffffffff8156dc94: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157ec30)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff8157ec30-ffffffff8157ed84: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_resize_resource(struct pci_dev *dev, int resno, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff815990e0)
Location: drivers/pci/setup-res.c:409
Inline: False
```
**Symbols:**

```
ffffffff815990e0-ffffffff81599234: pci_resize_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
