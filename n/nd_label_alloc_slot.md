# Function: <code>nd_label_alloc_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159f930)
Location: drivers/nvdimm/label.c:374
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8159f930-ffffffff8159f9c8: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f5940)
Location: drivers/nvdimm/label.c:374
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff815f5940-ffffffff815f59d8: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81623600)
Location: drivers/nvdimm/label.c:374
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81623600-ffffffff81623698: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81638340)
Location: drivers/nvdimm/label.c:455
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81638340-ffffffff816383cd: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a0a40)
Location: drivers/nvdimm/label.c:457
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816a0a40-ffffffff816a0acd: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dcd40)
Location: drivers/nvdimm/label.c:466
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816dcd40-ffffffff816dcdbb: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ff090)
Location: drivers/nvdimm/label.c:596
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816ff090-ffffffff816ff10b: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:593
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8173a61f-ffffffff8173a632: nd_label_alloc_slot.cold (STB_LOCAL)
ffffffff81738e20-ffffffff81738ea1: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175cb70)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8175cb70-ffffffff8175cbf1: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c470)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8181c470-ffffffff8181c4f1: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b4c0)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8182b4c0-ffffffff8182b541: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180e7e0)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8180e7e0-ffffffff8180e865: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898dc0)
Location: drivers/nvdimm/label.c:604
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81898dc0-ffffffff81898e45: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e2ce0)
Location: drivers/nvdimm/label.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819e2ce0-ffffffff819e2d85: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5e940)
Location: drivers/nvdimm/label.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81b5e940-ffffffff81b5e9cd: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb1ef0)
Location: drivers/nvdimm/label.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bb1ef0-ffffffff81bb1f7d: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c063e0)
Location: drivers/nvdimm/label.c:609
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81c063e0-ffffffff81c0646d: nd_label_alloc_slot (STB_GLOBAL)
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
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e310)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffff80001095e310-ffff80001095e3d8: nd_label_alloc_slot (STB_GLOBAL)
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
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a10200)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
c000000000a10200-c000000000a10308: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc2ca)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffe0005cc2ca-ffffffe0005cc378: nd_label_alloc_slot (STB_GLOBAL)
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
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81711260)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81711260-ffffffff817112e1: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4ce0)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816e4ce0-ffffffff816e4d61: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81750030)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81750030-ffffffff817500b1: nd_label_alloc_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 nd_label_alloc_slot(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b4b0)
Location: drivers/nvdimm/label.c:588
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8176b4b0-ffffffff8176b531: nd_label_alloc_slot (STB_GLOBAL)
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
