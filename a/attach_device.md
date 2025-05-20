# Function: <code>attach_device</code>

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
In drivers/iommu/amd_iommu.c (ffffffff81530397)
Location: drivers/iommu/amd_iommu.c:2071
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81584f48)
Location: drivers/iommu/amd_iommu.c:1951
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b204c)
Location: drivers/iommu/amd_iommu.c:2044
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c7d43)
Location: drivers/iommu/amd_iommu.c:2291
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d240)
Location: drivers/iommu/amd_iommu.c:2062
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff8162d240-ffffffff8162d507: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667d00)
Location: drivers/iommu/amd_iommu.c:2064
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81667d00-ffffffff81667fc5: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686a20)
Location: drivers/iommu/amd_iommu.c:2146
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81686a20-ffffffff81686cbf: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816be280)
Location: drivers/iommu/amd_iommu.c:2128
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff816be280-ffffffff816be51c: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e16b0)
Location: drivers/iommu/amd_iommu.c:2156
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff816e16b0-ffffffff816e195a: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799360)
Location: drivers/iommu/amd/iommu.c:2017
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81799360-ffffffff817994c7: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7be0)
Location: drivers/iommu/amd/iommu.c:2108
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_get_v2_domain
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff817a7be0-ffffffff817a7d53: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789fa0)
Location: drivers/iommu/amd/iommu.c:1569
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81789fa0-ffffffff8178a212: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1618
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81811280-ffffffff81811523: attach_device (STB_LOCAL)
ffffffff81cfe3a3-ffffffff81cfe418: attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1640
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81951830-ffffffff81951b0f: attach_device (STB_LOCAL)
ffffffff81ec6b61-ffffffff81ec6bc8: attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1746
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81ab68c0-ffffffff81ab6baf: attach_device (STB_LOCAL)
ffffffff82096f76-ffffffff82096fe0: attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1771
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81b02ae0-ffffffff81b02e38: attach_device (STB_LOCAL)
ffffffff82117e5c-ffffffff82117ec6: attach_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b56c9f)
Location: drivers/iommu/amd/iommu.c:1868
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a7100)
Location: drivers/iommu/amd_iommu.c:2156
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff816a7100-ffffffff816a73aa: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684af0)
Location: drivers/iommu/amd_iommu.c:2156
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff81684af0-ffffffff81684d9a: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d5370)
Location: drivers/iommu/amd_iommu.c:2156
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff816d5370-ffffffff816d561a: attach_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int attach_device(struct device *dev, struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816efcb0)
Location: drivers/iommu/amd_iommu.c:2156
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
```
**Symbols:**

```
ffffffff816efcb0-ffffffff816eff4c: attach_device (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
