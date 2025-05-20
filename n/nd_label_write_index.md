# Function: <code>nd_label_write_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159eb00)
Location: drivers/nvdimm/label.c:424
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8159eb00-ffffffff8159ef2d: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f4b70)
Location: drivers/nvdimm/label.c:424
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff815f4b70-ffffffff815f4f6c: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816227f0)
Location: drivers/nvdimm/label.c:424
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816227f0-ffffffff81622bec: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81637440)
Location: drivers/nvdimm/label.c:505
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81637440-ffffffff8163782b: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8169fdb0)
Location: drivers/nvdimm/label.c:507
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8169fdb0-ffffffff816a009c: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dc090)
Location: drivers/nvdimm/label.c:516
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816dc090-ffffffff816dc3c6: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816fe080)
Location: drivers/nvdimm/label.c:646
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816fe080-ffffffff816fe3b6: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:643
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81738220-ffffffff8173854f: nd_label_write_index (STB_LOCAL)
ffffffff8173a5ef-ffffffff8173a61f: nd_label_write_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175bef0)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8175bef0-ffffffff8175c226: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181b6f0)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8181b6f0-ffffffff8181ba42: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182a750)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8182a750-ffffffff8182aa9e: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180da20)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8180da20-ffffffff8180dd6e: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81898010)
Location: drivers/nvdimm/label.c:654
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81898010-ffffffff8189835e: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e1ec0)
Location: drivers/nvdimm/label.c:659
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff819e1ec0-ffffffff819e2225: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5daf0)
Location: drivers/nvdimm/label.c:659
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81b5daf0-ffffffff81b5de55: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb10b0)
Location: drivers/nvdimm/label.c:659
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81bb10b0-ffffffff81bb1417: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c05570)
Location: drivers/nvdimm/label.c:659
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff81c05570-ffffffff81c058d7: nd_label_write_index (STB_LOCAL)
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
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095d5e0)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffff80001095d5e0-ffff80001095d8fc: nd_label_write_index (STB_LOCAL)
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
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a0ef10)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
c000000000a0ef10-c000000000a0f358: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cb772)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffe0005cb772-ffffffe0005cba64: nd_label_write_index (STB_LOCAL)
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
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817105e0)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff817105e0-ffffffff81710916: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4060)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff816e4060-ffffffff816e4396: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8174f3b0)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8174f3b0-ffffffff8174f6e6: nd_label_write_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nd_label_write_index(struct nvdimm_drvdata *ndd, int index, u32 seq, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176a830)
Location: drivers/nvdimm/label.c:638
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:del_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:init_labels
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
```
**Symbols:**

```
ffffffff8176a830-ffffffff8176ab66: nd_label_write_index (STB_LOCAL)
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
