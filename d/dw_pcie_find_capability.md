# Function: <code>dw_pcie_find_capability</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0f90)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
```
**Symbols:**

```
ffffffff815b0f90-ffffffff815b0fc3: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a7a5)
Location: drivers/pci/controller/dwc/pcie-designware.c:45
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff8165a6f0-ffffffff8165a793: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167aea0)
Location: drivers/pci/controller/dwc/pcie-designware.c:46
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
```
**Symbols:**

```
ffffffff8167aea0-ffffffff8167af43: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d8f0)
Location: drivers/pci/controller/dwc/pcie-designware.c:46
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff8165d8f0-ffffffff8165d993: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0360)
Location: drivers/pci/controller/dwc/pcie-designware.c:46
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff816d0360-ffffffff816d0405: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f91b0)
Location: drivers/pci/controller/dwc/pcie-designware.c:46
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff817f91b0-ffffffff817f9267: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819251b0)
Location: drivers/pci/controller/dwc/pcie-designware.c:218
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff81925090-ffffffff81925147: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968f00)
Location: drivers/pci/controller/dwc/pcie-designware.c:231
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
```
**Symbols:**

```
ffffffff81968de0-ffffffff81968e97: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2710)
Location: drivers/pci/controller/dwc/pcie-designware.c:231
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_setup
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_suspend_noirq
```
**Symbols:**

```
ffffffff819b2710-ffffffff819b27c7: dw_pcie_find_capability (STB_GLOBAL)
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
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072d018)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffff80001072d018-ffff80001072d060: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b67dc)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
c08b67dc-c08b681c: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e77d4)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffe0004e77d4-ffffffe0004e781a: dw_pcie_find_capability (STB_GLOBAL)
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
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4750)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
```
**Symbols:**

```
ffffffff815a4750-ffffffff815a4783: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815938f0)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
```
**Symbols:**

```
ffffffff815938f0-ffffffff81593923: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4ce0)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
```
**Symbols:**

```
ffffffff815a4ce0-ffffffff815a4d13: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u8 dw_pcie_find_capability(struct dw_pcie *pci, u8 cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf0e0)
Location: drivers/pci/controller/dwc/pcie-designware.c:44
Inline: False
```
**Symbols:**

```
ffffffff815bf0e0-ffffffff815bf113: dw_pcie_find_capability (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
