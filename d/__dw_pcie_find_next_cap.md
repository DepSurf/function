# Function: <code>__dw_pcie_find_next_cap</code>

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
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815b0f30)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffff815b0f30-ffffffff815b0f82: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165a7c6)
Location: drivers/pci/controller/dwc/pcie-designware.c:23
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_link_set_max_speed
```
**Symbols:**

```
ffffffff8165a670-ffffffff8165a6e8: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8167aec2)
Location: drivers/pci/controller/dwc/pcie-designware.c:24
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
**Symbols:**

```
ffffffff8167ae20-ffffffff8167ae98: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff8165d912)
Location: drivers/pci/controller/dwc/pcie-designware.c:24
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
**Symbols:**

```
ffffffff8165d870-ffffffff8165d8e8: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff816d0382)
Location: drivers/pci/controller/dwc/pcie-designware.c:24
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
**Symbols:**

```
ffffffff816d02e0-ffffffff816d0359: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff817f91d3)
Location: drivers/pci/controller/dwc/pcie-designware.c:24
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
**Symbols:**

```
ffffffff817f9130-ffffffff817f91ac: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819251c2)
Location: drivers/pci/controller/dwc/pcie-designware.c:196
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
**Symbols:**

```
ffffffff81925000-ffffffff8192507c: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81968f12)
Location: drivers/pci/controller/dwc/pcie-designware.c:209
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_wait_for_link
```
**Symbols:**

```
ffffffff81968d50-ffffffff81968dcc: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff819b2733)
Location: drivers/pci/controller/dwc/pcie-designware.c:209
Inline: True
Inline callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
```
**Symbols:**

```
ffffffff819b2680-ffffffff819b26fc: __dw_pcie_find_next_cap (STB_LOCAL)
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
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffff80001072cf88)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffff80001072cf88-ffff80001072d014: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (c08b6778)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
c08b6778-c08b67dc: __dw_pcie_find_next_cap (STB_LOCAL)
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
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffe0004e7762)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffe0004e7762-ffffffe0004e77d4: __dw_pcie_find_next_cap (STB_LOCAL)
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
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a46f0)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffff815a46f0-ffffffff815a4742: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff81593890)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffff81593890-ffffffff815938e2: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815a4c80)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffff815a4c80-ffffffff815a4cd2: __dw_pcie_find_next_cap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u8 __dw_pcie_find_next_cap(struct dw_pcie *pci, u8 cap_ptr, u8 cap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/controller/dwc/pcie-designware.c (ffffffff815bf080)
Location: drivers/pci/controller/dwc/pcie-designware.c:22
Inline: False
Direct callers:
  - drivers/pci/controller/dwc/pcie-designware.c:dw_pcie_find_capability
  - drivers/pci/controller/dwc/pcie-designware.c:__dw_pcie_find_next_cap
```
**Symbols:**

```
ffffffff815bf080-ffffffff815bf0d2: __dw_pcie_find_next_cap (STB_LOCAL)
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
