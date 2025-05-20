# Function: <code>pci_update_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8143d420)
Location: drivers/pci/setup-res.c:29
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8143d420-ffffffff8143d666: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81489260)
Location: drivers/pci/setup-res.c:29
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff81489260-ffffffff814894a2: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814aaa40)
Location: drivers/pci/setup-res.c:123
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff814aaa40-ffffffff814aac98: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814b4d90)
Location: drivers/pci/setup-res.c:123
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff814b4d90-ffffffff814b4f99: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff814f4790)
Location: drivers/pci/setup-res.c:124
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff814f4790-ffffffff814f4999: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81524840)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff81524840-ffffffff81524a52: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8153a6c0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8153a6c0-ffffffff8153a8d2: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8156a0a0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8156a5d4-ffffffff8156a60d: pci_update_resource.cold (STB_LOCAL)
ffffffff8156a070-ffffffff8156a246: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8158b070)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8158b5a4-ffffffff8158b5dd: pci_update_resource.cold (STB_LOCAL)
ffffffff8158b040-ffffffff8158b216: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81632180)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:sriov_restore_state
```
**Symbols:**

```
ffffffff81632180-ffffffff816321a6: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff816577a0)
Location: drivers/pci/setup-res.c:121
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:sriov_restore_state
```
**Symbols:**

```
ffffffff816577a0-ffffffff816577c6: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8163a110)
Location: drivers/pci/setup-res.c:121
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8163a110-ffffffff8163a136: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff816aa920)
Location: drivers/pci/setup-res.c:121
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff816aa920-ffffffff816aa946: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff817cd850)
Location: drivers/pci/setup-res.c:125
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff817cd850-ffffffff817cd894: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff818ed2df)
Location: drivers/pci/setup-res.c:125
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff818ece70-ffffffff818eceb4: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff819307ca)
Location: drivers/pci/setup-res.c:125
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
Direct callers:
  - drivers/pci/pci.c:pci_set_power_state
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff81930350-ffffffff81930394: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff819791c8)
Location: drivers/pci/setup-res.c:126
Inline: True
Inline callers:
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
Direct callers:
  - drivers/pci/pci.c:__pci_set_power_state
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff81978cf0-ffffffff81978d34: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffff8000106efdc0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffff8000106efdc0-ffff8000106effe0: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c088a954)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
c088a954-c088ab70: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (c00000000086d170)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_vf_resource_shift
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
c00000000086d170-c00000000086d4a0: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-res.c (ffffffe0004c3ac2)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffe0004c3ac2-ffffffe0004c3c88: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157eef0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8157f424-ffffffff8157f45d: pci_update_resource.cold (STB_LOCAL)
ffffffff8157eec0-ffffffff8157f096: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8156dcd0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8156e204-ffffffff8156e23d: pci_update_resource.cold (STB_LOCAL)
ffffffff8156dca0-ffffffff8156de76: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff8157edc0)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff8157f2f4-ffffffff8157f32d: pci_update_resource.cold (STB_LOCAL)
ffffffff8157ed90-ffffffff8157ef66: pci_update_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pci_update_resource(struct pci_dev *dev, int resno);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-res.c (ffffffff81599270)
Location: drivers/pci/setup-res.c:120
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_raw_set_power_state
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/iov.c:pci_restore_iov_state
```
**Symbols:**

```
ffffffff815997a4-ffffffff815997dd: pci_update_resource.cold (STB_LOCAL)
ffffffff81599240-ffffffff81599416: pci_update_resource (STB_GLOBAL)
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
