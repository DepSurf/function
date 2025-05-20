# Function: <code>__nd_attach_ndns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff815a0a50)
Location: drivers/nvdimm/claim.c:46
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
Direct callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff815a0a50-ffffffff815a0ae7: __nd_attach_ndns.part.1 (STB_LOCAL)
ffffffff815a0bf0-ffffffff815a0c0d: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff815f6f8a)
Location: drivers/nvdimm/claim.c:47
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
Direct callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff815f6da0-ffffffff815f6e37: __nd_attach_ndns.part.3 (STB_LOCAL)
ffffffff815f6f40-ffffffff815f6f5d: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816251fa)
Location: drivers/nvdimm/claim.c:46
Inline: True
Inline callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
Direct callers:
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff81624dc0-ffffffff81624e4f: __nd_attach_ndns.part.4 (STB_LOCAL)
ffffffff816251b0-ffffffff816251cd: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8163a170)
Location: drivers/nvdimm/claim.c:51
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8163a170-ffffffff8163a21c: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816a2d70)
Location: drivers/nvdimm/claim.c:51
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff816a2d70-ffffffff816a2e1c: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816deef0)
Location: drivers/nvdimm/claim.c:51
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff816deef0-ffffffff816def9a: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff817012d0)
Location: drivers/nvdimm/claim.c:51
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff817012d0-ffffffff8170137a: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8173b150)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8173b150-ffffffff8173b1f9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8175ee20)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
ffffffff8175ee20-ffffffff8175eec9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8181e800)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8181e800-ffffffff8181e8a9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8182d740)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8182d740-ffffffff8182d7e9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81810a30)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff81810a30-ffffffff81810ad9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff81d0b543-ffffffff81d0b558: __nd_attach_ndns.cold (STB_LOCAL)
ffffffff8189b080-ffffffff8189b137: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff81ed440b-ffffffff81ed4420: __nd_attach_ndns.cold (STB_LOCAL)
ffffffff819e47c0-ffffffff819e4895: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8209b481-ffffffff8209b496: __nd_attach_ndns.cold (STB_LOCAL)
ffffffff81b60530-ffffffff81b60605: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff8211c350-ffffffff8211c365: __nd_attach_ndns.cold (STB_LOCAL)
ffffffff81bb3ac0-ffffffff81bb3b95: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/claim.c:44
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffff821fa1d7-ffffffff821fa1ec: __nd_attach_ndns.cold (STB_LOCAL)
ffffffff81c08010-ffffffff81c080e5: __nd_attach_ndns (STB_GLOBAL)
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
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffff800010960620)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffff800010960620-ffff8000109606e8: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (c000000000a13640)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
c000000000a13640-c000000000a1376c: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffe0005ce076)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
```
**Symbols:**

```
ffffffe0005ce076-ffffffe0005ce12c: __nd_attach_ndns (STB_GLOBAL)
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
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff81713510)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
ffffffff81713510-ffffffff817135b9: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff816e6f90)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
ffffffff816e6f90-ffffffff816e7039: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff817522e0)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
ffffffff817522e0-ffffffff81752389: __nd_attach_ndns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __nd_attach_ndns(struct device *dev, struct nd_namespace_common *attach, struct nd_namespace_common **_ndns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/claim.c (ffffffff8176d750)
Location: drivers/nvdimm/claim.c:43
Inline: False
Direct callers:
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_attach_ndns
  - drivers/nvdimm/pfn_devs.c:nd_pfn_devinit
```
**Symbols:**

```
ffffffff8176d750-ffffffff8176d7f9: __nd_attach_ndns (STB_GLOBAL)
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
