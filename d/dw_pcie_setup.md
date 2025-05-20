# Function: <code>dw_pcie_setup</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff814d3680)
Location: drivers/pci/dwc/pcie-designware.c:343
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff814d3680-ffffffff814d36b4: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/dwc/pcie-designware.c (ffffffff81513a60)
Location: drivers/pci/dwc/pcie-designware.c:345
Inline: False
Direct callers:
  - drivers/pci/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff81513a60-ffffffff81513a94: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81548e40)
Location: drivers/pci/controller/dwc/pcie-designware.c:342
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff81548e40-ffffffff81548e74: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8155f520)
Location: drivers/pci/controller/dwc/pcie-designware.c:342
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff8155f520-ffffffff8155f554: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8158faa0)
Location: drivers/pci/controller/dwc/pcie-designware.c:407
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff8158faa0-ffffffff8158fb4b: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b1810)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff815b1810-ffffffff815b18b3: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165b050)
Location: drivers/pci/controller/dwc/pcie-designware.c:547
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff8165b050-ffffffff8165b0fa: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:613
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff81bfdf54-ffffffff81bfe172: dw_pcie_setup.cold (STB_LOCAL)
ffffffff8167b300-ffffffff8167b492: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:696
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff81befdc6-ffffffff81befddb: dw_pcie_setup.cold (STB_LOCAL)
ffffffff8165e020-ffffffff8165e323: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:697
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff81ceb41b-ffffffff81ceb430: dw_pcie_setup.cold (STB_LOCAL)
ffffffff816d0aa0-ffffffff816d0df5: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (0)
Location: drivers/pci/controller/dwc/pcie-designware.c:712
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff81eb2810-ffffffff81eb2824: dw_pcie_setup.cold (STB_LOCAL)
ffffffff817f9a00-ffffffff817f9d79: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81925e40)
Location: drivers/pci/controller/dwc/pcie-designware.c:785
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff81925e40-ffffffff819261c6: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8196a010)
Location: drivers/pci/controller/dwc/pcie-designware.c:980
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff8196a010-ffffffff8196a3a3: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b37f0)
Location: drivers/pci/controller/dwc/pcie-designware.c:1034
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init_complete
```
**Symbols:**

```
ffffffff819b37f0-ffffffff819b3b64: dw_pcie_setup (STB_GLOBAL)
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
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072da08)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffff80001072da08-ffff80001072dc70: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b7118)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
c08b7118-c08b73c8: dw_pcie_setup (STB_GLOBAL)
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
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e805a)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
  - drivers/pci/controller/dwc/pcie-designware-ep.c:dw_pcie_ep_init
```
**Symbols:**

```
ffffffe0004e805a-ffffffe0004e82e0: dw_pcie_setup (STB_GLOBAL)
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
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4fd0)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff815a4fd0-ffffffff815a5073: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81594170)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff81594170-ffffffff81594213: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a5560)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff815a5560-ffffffff815a5603: dw_pcie_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dw_pcie_setup(struct dw_pcie *pci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf960)
Location: drivers/pci/controller/dwc/pcie-designware.c:488
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware-host.c:dw_pcie_setup_rc
```
**Symbols:**

```
ffffffff815bf960-ffffffff815bfa03: dw_pcie_setup (STB_GLOBAL)
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
