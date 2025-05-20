# Function: <code>amd_iommu_is_attach_deferred</code>

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
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162a9b0)
Location: drivers/iommu/amd_iommu.c:3159
Inline: False
```
**Symbols:**

```
ffffffff8162a9b0-ffffffff8162a9c6: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665640)
Location: drivers/iommu/amd_iommu.c:3167
Inline: False
```
**Symbols:**

```
ffffffff81665640-ffffffff81665656: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683f00)
Location: drivers/iommu/amd_iommu.c:3233
Inline: False
```
**Symbols:**

```
ffffffff81683f00-ffffffff81683f16: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb490)
Location: drivers/iommu/amd_iommu.c:3214
Inline: False
```
**Symbols:**

```
ffffffff816bb490-ffffffff816bb4a6: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de290)
Location: drivers/iommu/amd_iommu.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816de290-ffffffff816de2a6: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81794c60)
Location: drivers/iommu/amd/iommu.c:2619
Inline: False
```
**Symbols:**

```
ffffffff81794c60-ffffffff81794c7a: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3120)
Location: drivers/iommu/amd/iommu.c:2710
Inline: False
```
**Symbols:**

```
ffffffff817a3120-ffffffff817a313f: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81785ea0)
Location: drivers/iommu/amd/iommu.c:2140
Inline: False
```
**Symbols:**

```
ffffffff81785ea0-ffffffff81785ebf: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2201
Inline: False
```
**Symbols:**

```
ffffffff81cfdc1d-ffffffff81cfdc3d: amd_iommu_is_attach_deferred.cold (STB_LOCAL)
ffffffff8180d460-ffffffff8180d485: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool amd_iommu_is_attach_deferred(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2219
Inline: False
```
**Symbols:**

```
ffffffff81ec6521-ffffffff81ec654b: amd_iommu_is_attach_deferred.cold (STB_LOCAL)
ffffffff8194dbf0-ffffffff8194dc1f: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool amd_iommu_is_attach_deferred(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2368
Inline: False
```
**Symbols:**

```
ffffffff82096c8f-ffffffff82096cb9: amd_iommu_is_attach_deferred.cold (STB_LOCAL)
ffffffff81ab2420-ffffffff81ab244f: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool amd_iommu_is_attach_deferred(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2389
Inline: False
```
**Symbols:**

```
ffffffff82117b52-ffffffff82117b7c: amd_iommu_is_attach_deferred.cold (STB_LOCAL)
ffffffff81afe4d0-ffffffff81afe4ff: amd_iommu_is_attach_deferred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool amd_iommu_is_attach_deferred(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2559
Inline: False
```
**Symbols:**

```
ffffffff821f58e6-ffffffff821f5910: amd_iommu_is_attach_deferred.cold (STB_LOCAL)
ffffffff81b51c20-ffffffff81b51c4f: amd_iommu_is_attach_deferred (STB_GLOBAL)
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
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a3ce0)
Location: drivers/iommu/amd_iommu.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816a3ce0-ffffffff816a3cf6: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816816d0)
Location: drivers/iommu/amd_iommu.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816816d0-ffffffff816816e6: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d1f50)
Location: drivers/iommu/amd_iommu.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816d1f50-ffffffff816d1f66: amd_iommu_is_attach_deferred (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool amd_iommu_is_attach_deferred(struct iommu_domain *domain, struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec550)
Location: drivers/iommu/amd_iommu.c:3249
Inline: False
```
**Symbols:**

```
ffffffff816ec550-ffffffff816ec566: amd_iommu_is_attach_deferred (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct iommu_domain *domain</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, dev</code> ➡️ <code>dev</code>
</li>
</ul>
</details>
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
