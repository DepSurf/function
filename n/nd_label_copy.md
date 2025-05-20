# Function: <code>nd_label_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159e9c0)
Location: drivers/nvdimm/label.c:192
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__blk_label_update
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8159e9c0-ffffffff8159e9ff: nd_label_copy.part.6 (STB_LOCAL)
ffffffff8159f520-ffffffff8159f53b: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f5ef8)
Location: drivers/nvdimm/label.c:192
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff815f4a30-ffffffff815f4a6f: nd_label_copy.part.6 (STB_LOCAL)
ffffffff815f5550-ffffffff815f556b: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81623c93)
Location: drivers/nvdimm/label.c:192
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff81622700-ffffffff8162273f: nd_label_copy.part.8 (STB_LOCAL)
ffffffff81623210-ffffffff8162322b: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81638d8d)
Location: drivers/nvdimm/label.c:242
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816373f0-ffffffff8163743a: nd_label_copy.part.11 (STB_LOCAL)
ffffffff81637f20-ffffffff81637f3c: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a14da)
Location: drivers/nvdimm/label.c:244
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff8169fd80-ffffffff8169fdaa: nd_label_copy.part.10 (STB_LOCAL)
ffffffff816a0620-ffffffff816a063c: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ddc2e)
Location: drivers/nvdimm/label.c:253
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
```
**Symbols:**

```
ffffffff816dc060-ffffffff816dc08a: nd_label_copy.part.12 (STB_LOCAL)
ffffffff816dc920-ffffffff816dc93b: nd_label_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816fff8e)
Location: drivers/nvdimm/label.c:261
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff816fe050-ffffffff816fe07a: nd_label_copy.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81739c4e)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff817381f0-ffffffff8173821c: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175d99e)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8175bec0-ffffffff8175beec: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181b6b0)
Location: drivers/nvdimm/label.c:255
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8181b6b0-ffffffff8181b6e7: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182a710)
Location: drivers/nvdimm/label.c:255
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8182a710-ffffffff8182a747: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180d9e0)
Location: drivers/nvdimm/label.c:255
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8180d9e0-ffffffff8180da17: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81897fd0)
Location: drivers/nvdimm/label.c:255
Inline: True
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81897fd0-ffffffff81898007: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e1e70)
Location: drivers/nvdimm/label.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff819e1e70-ffffffff819e1ebd: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5da90)
Location: drivers/nvdimm/label.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81b5da90-ffffffff81b5dadd: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb1050)
Location: drivers/nvdimm/label.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81bb1050-ffffffff81bb109d: nd_label_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nd_label_copy(struct nvdimm_drvdata *ndd, struct nd_namespace_index *dst, struct nd_namespace_index *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c05510)
Location: drivers/nvdimm/label.c:263
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81c05510-ffffffff81c0555d: nd_label_copy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095f0e4)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffff80001095d590-ffff80001095d5dc: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a117bc)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
c000000000a0eeb0-c000000000a0ef04: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cce44)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8171208e)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff817105b0-ffffffff817105dc: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e5b0e)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff816e4030-ffffffff816e405c: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81750e5e)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8174f380-ffffffff8174f3ac: nd_label_copy.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176c2de)
Location: drivers/nvdimm/label.c:255
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
Direct callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_write_index
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8176a800-ffffffff8176a82c: nd_label_copy.part.0 (STB_LOCAL)
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
