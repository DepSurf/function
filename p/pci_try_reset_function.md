# Function: <code>pci_try_reset_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81438580)
Location: drivers/pci/pci.c:3825
Inline: True
```
**Symbols:**

```
ffffffff81438580-ffffffff814385ed: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81484230)
Location: drivers/pci/pci.c:4146
Inline: True
```
**Symbols:**

```
ffffffff81484230-ffffffff814842ac: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5990)
Location: drivers/pci/pci.c:4184
Inline: True
```
**Symbols:**

```
ffffffff814a5990-ffffffff814a5a0c: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814afaf0)
Location: drivers/pci/pci.c:4340
Inline: True
```
**Symbols:**

```
ffffffff814afaf0-ffffffff814afb5d: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ef020)
Location: drivers/pci/pci.c:4356
Inline: True
```
**Symbols:**

```
ffffffff814ef020-ffffffff814ef08d: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151eb50)
Location: drivers/pci/pci.c:4604
Inline: False
```
**Symbols:**

```
ffffffff8151eb50-ffffffff8151ebb8: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81534930)
Location: drivers/pci/pci.c:4895
Inline: False
```
**Symbols:**

```
ffffffff81534930-ffffffff81534998: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81563e10)
Location: drivers/pci/pci.c:4993
Inline: False
```
**Symbols:**

```
ffffffff81563e10-ffffffff81563e7b: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815850f0)
Location: drivers/pci/pci.c:5123
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff815850f0-ffffffff8158515b: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162bd60)
Location: drivers/pci/pci.c:5153
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff8162bd60-ffffffff8162bdf7: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651a90)
Location: drivers/pci/pci.c:5221
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff81651a90-ffffffff81651b27: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81634500)
Location: drivers/pci/pci.c:5270
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff81634500-ffffffff81634597: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a22d0)
Location: drivers/pci/pci.c:5460
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff816a22d0-ffffffff816a2367: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4390)
Location: drivers/pci/pci.c:5556
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff817c4390-ffffffff817c442c: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e12d0)
Location: drivers/pci/pci.c:5493
Inline: False
```
**Symbols:**

```
ffffffff818e12d0-ffffffff818e136c: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924710)
Location: drivers/pci/pci.c:5615
Inline: False
```
**Symbols:**

```
ffffffff81924710-ffffffff819247ac: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196cde0)
Location: drivers/pci/pci.c:5725
Inline: False
```
**Symbols:**

```
ffffffff8196cde0-ffffffff8196ce7c: pci_try_reset_function (STB_GLOBAL)
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
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e97d0)
Location: drivers/pci/pci.c:5123
Inline: False
```
**Symbols:**

```
ffff8000106e97d0-ffff8000106e9848: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c088474c)
Location: drivers/pci/pci.c:5123
Inline: False
```
**Symbols:**

```
c088474c-c08847c0: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0000000008647c0)
Location: drivers/pci/pci.c:5123
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
c0000000008647c0-c000000000864874: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bfb22)
Location: drivers/pci/pci.c:5123
Inline: False
```
**Symbols:**

```
ffffffe0004bfb22-ffffffe0004bfb9a: pci_try_reset_function (STB_GLOBAL)
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
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81579610)
Location: drivers/pci/pci.c:5123
Inline: False
```
**Symbols:**

```
ffffffff81579610-ffffffff8157967b: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81567d50)
Location: drivers/pci/pci.c:5123
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff81567d50-ffffffff81567dbb: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81578e40)
Location: drivers/pci/pci.c:5123
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff81578e40-ffffffff81578eab: pci_try_reset_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_try_reset_function(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815932f0)
Location: drivers/pci/pci.c:5123
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_enable
  - drivers/vfio/pci/vfio_pci_config.c:vfio_af_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_exp_config_write
```
**Symbols:**

```
ffffffff815932f0-ffffffff8159335b: pci_try_reset_function (STB_GLOBAL)
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
