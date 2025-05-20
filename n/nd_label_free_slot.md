# Function: <code>nd_label_free_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159f9d0)
Location: drivers/nvdimm/label.c:394
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8159f9d0-ffffffff8159fa67: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f59e0)
Location: drivers/nvdimm/label.c:394
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff815f59e0-ffffffff815f5a6f: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816236a0)
Location: drivers/nvdimm/label.c:394
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816236a0-ffffffff8162372f: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816383d0)
Location: drivers/nvdimm/label.c:475
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816383d0-ffffffff81638454: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a0ad0)
Location: drivers/nvdimm/label.c:477
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816a0ad0-ffffffff816a0b54: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dcdc0)
Location: drivers/nvdimm/label.c:486
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816dcdc0-ffffffff816dce28: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ff110)
Location: drivers/nvdimm/label.c:616
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816ff110-ffffffff816ff178: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:613
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8173a632-ffffffff8173a645: nd_label_free_slot.cold (STB_LOCAL)
ffffffff81738eb0-ffffffff81738f16: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175cc00)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8175cc00-ffffffff8175cc66: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c500)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8181c500-ffffffff8181c566: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b550)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff8182b550-ffffffff8182b5b6: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180e870)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff8180e870-ffffffff8180e8d8: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898e50)
Location: drivers/nvdimm/label.c:624
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:reap_victim
```
**Symbols:**

```
ffffffff81898e50-ffffffff81898eb8: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e2d90)
Location: drivers/nvdimm/label.c:629
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819e2d90-ffffffff819e2e08: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5e9e0)
Location: drivers/nvdimm/label.c:629
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81b5e9e0-ffffffff81b5ea58: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb1f90)
Location: drivers/nvdimm/label.c:629
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bb1f90-ffffffff81bb2008: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c06480)
Location: drivers/nvdimm/label.c:629
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81c06480-ffffffff81c064f8: nd_label_free_slot (STB_GLOBAL)
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
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e3d8)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffff80001095e3d8-ffff80001095e4d4: nd_label_free_slot (STB_GLOBAL)
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
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a10310)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
c000000000a10310-c000000000a10414: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc378)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffe0005cc378-ffffffe0005cc424: nd_label_free_slot (STB_GLOBAL)
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
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817112f0)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff817112f0-ffffffff81711356: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4d70)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816e4d70-ffffffff816e4dd6: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817500c0)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff817500c0-ffffffff81750126: nd_label_free_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool nd_label_free_slot(struct nvdimm_drvdata *ndd, u32 slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b540)
Location: drivers/nvdimm/label.c:608
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8176b540-ffffffff8176b5a6: nd_label_free_slot (STB_GLOBAL)
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
