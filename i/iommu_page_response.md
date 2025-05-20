# Function: <code>iommu_page_response</code>

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
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1026
Inline: False
```
**Symbols:**

```
ffffffff816b8965-ffffffff816b8983: iommu_page_response.cold (STB_LOCAL)
ffffffff816b6680-ffffffff816b6805: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffffffff816db7e5-ffffffff816db803: iommu_page_response.cold (STB_LOCAL)
ffffffff816d9380-ffffffff816d9505: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1185
Inline: False
```
**Symbols:**

```
ffffffff817906bb-ffffffff817906d9: iommu_page_response.cold (STB_LOCAL)
ffffffff8178e280-ffffffff8178e435: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1206
Inline: False
```
**Symbols:**

```
ffffffff81c0d524-ffffffff81c0d542: iommu_page_response.cold (STB_LOCAL)
ffffffff817ba430-ffffffff817ba615: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1235
Inline: False
```
**Symbols:**

```
ffffffff81bff8cf-ffffffff81bff8ed: iommu_page_response.cold (STB_LOCAL)
ffffffff8179e130-ffffffff8179e315: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1250
Inline: False
Direct callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_group
```
**Symbols:**

```
ffffffff81d019e8-ffffffff81d01a06: iommu_page_response.cold (STB_LOCAL)
ffffffff81827180-ffffffff81827365: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1224
Inline: False
Direct callers:
  - drivers/iommu/io-pgfault.c:iopf_handle_group
```
**Symbols:**

```
ffffffff81ec9e6d-ffffffff81ec9e8b: iommu_page_response.cold (STB_LOCAL)
ffffffff819650f0-ffffffff819652ac: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81ace4f0)
Location: drivers/iommu/iommu.c:1345
Inline: False
Direct callers:
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81ace4f0-ffffffff81ace6c0: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1c700)
Location: drivers/iommu/iommu.c:1336
Inline: False
Direct callers:
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81b1c700-ffffffff81b1c8d0: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b72a70)
Location: drivers/iommu/iommu.c:1480
Inline: False
Direct callers:
  - drivers/iommu/io-pgfault.c:iopf_handler
```
**Symbols:**

```
ffffffff81b72a70-ffffffff81b72c40: iommu_page_response (STB_GLOBAL)
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
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c4b90)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffff8000108c4b90-ffff8000108c4d30: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09bbf80)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
c09bbf80-c09bc108: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096aa80)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
c00000000096aa80-c00000000096aca0: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffffffff816a1235-ffffffff816a1253: iommu_page_response.cold (STB_LOCAL)
ffffffff8169edd0-ffffffff8169ef55: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffffffff8167ec25-ffffffff8167ec43: iommu_page_response.cold (STB_LOCAL)
ffffffff8167c7c0-ffffffff8167c945: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffffffff816cf4a5-ffffffff816cf4c3: iommu_page_response.cold (STB_LOCAL)
ffffffff816cd040-ffffffff816cd1c5: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_page_response(struct device *dev, struct iommu_page_response *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/iommu.c (0)
Location: drivers/iommu/iommu.c:1082
Inline: False
```
**Symbols:**

```
ffffffff816e9a2c-ffffffff816e9a4a: iommu_page_response.cold (STB_LOCAL)
ffffffff816e7520-ffffffff816e76a5: iommu_page_response (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
