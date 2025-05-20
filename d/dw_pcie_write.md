# Function: <code>dw_pcie_write</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d2ee0)
Location: drivers/pci/dwc/pcie-designware.c:47
Inline: True
```
**Symbols:**

```
ffffffff814d2ee0-ffffffff814d2f1b: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513380)
Location: drivers/pci/dwc/pcie-designware.c:47
Inline: True
```
**Symbols:**

```
ffffffff81513380-ffffffff815133bd: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548760)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: True
```
**Symbols:**

```
ffffffff81548760-ffffffff8154879c: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155ee20)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_wr_own_conf
```
**Symbols:**

```
ffffffff8155ee20-ffffffff8155ee5c: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158f487)
Location: drivers/pci/controller/dwc/pcie-designware.c:39
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_wr_own_conf
```
**Symbols:**

```
ffffffff8158f310-ffffffff8158f359: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b11f7)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff815b1080-ffffffff815b10c9: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a960)
Location: drivers/pci/controller/dwc/pcie-designware.c:120
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_msi_init
```
**Symbols:**

```
ffffffff8165a3e0-ffffffff8165a429: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167afa5)
Location: drivers/pci/controller/dwc/pcie-designware.c:121
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff8167a770-ffffffff8167a7b9: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165da01)
Location: drivers/pci/controller/dwc/pcie-designware.c:121
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff8165d280-ffffffff8165d2c9: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0471)
Location: drivers/pci/controller/dwc/pcie-designware.c:121
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff816cfcf0-ffffffff816cfd39: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f92e2)
Location: drivers/pci/controller/dwc/pcie-designware.c:121
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_upconfig_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff817f8a30-ffffffff817f8a7a: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81924d45)
Location: drivers/pci/controller/dwc/pcie-designware.c:293
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff81924810-ffffffff8192485a: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968a95)
Location: drivers/pci/controller/dwc/pcie-designware.c:306
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff819684b0-ffffffff819684fa: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b22d5)
Location: drivers/pci/controller/dwc/pcie-designware.c:306
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_writel_atu
```
**Symbols:**

```
ffffffff819b1cf0-ffffffff819b1d3a: dw_pcie_write (STB_GLOBAL)
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
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072ce18)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_am654_write_dbi2
  - drivers/pci/controller/dwc/pci-keystone.c:ks_pcie_wr_other_conf
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-kirin.c:kirin_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
  - drivers/pci/controller/dwc/pcie-al.c:al_pcie_wr_other_conf
```
**Symbols:**

```
ffff80001072ce18-ffff80001072ced0: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b663c)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pci-dra7xx.c:dra7xx_pcie_establish_link
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_wr_own_conf
  - drivers/pci/controller/dwc/pcie-histb.c:histb_pcie_write_dbi
```
**Symbols:**

```
c08b663c-c08b66c8: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7648)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_access_other_conf
```
**Symbols:**

```
ffffffe0004e7648-ffffffe0004e76dc: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a49b7)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_wr_own_conf
```
**Symbols:**

```
ffffffff815a4840-ffffffff815a4889: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593b57)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_wr_own_conf
```
**Symbols:**

```
ffffffff815939e0-ffffffff81593a29: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4f47)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
Direct callers:
  - drivers/pci/controller/dwc/pci-meson.c:meson_pcie_wr_own_conf
```
**Symbols:**

```
ffffffff815a4dd0-ffffffff815a4e19: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dw_pcie_write(void *addr, int size, u32 val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf347)
Location: drivers/pci/controller/dwc/pcie-designware.c:119
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_write_dbi2
```
**Symbols:**

```
ffffffff815bf1d0-ffffffff815bf219: dw_pcie_write (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
