# Function: <code>__blk_label_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159fd00)
Location: drivers/nvdimm/label.c:606
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8159fd00-ffffffff815a0602: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f5ce0)
Location: drivers/nvdimm/label.c:606
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff815f5ce0-ffffffff815f65cc: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81623a60)
Location: drivers/nvdimm/label.c:622
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff81623a60-ffffffff816244ab: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816387b0)
Location: drivers/nvdimm/label.c:761
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff816387b0-ffffffff816393a1: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a0eb0)
Location: drivers/nvdimm/label.c:763
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff816a0eb0-ffffffff816a1a74: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dd6d0)
Location: drivers/nvdimm/label.c:772
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff816dd6d0-ffffffff816de210: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ffa30)
Location: drivers/nvdimm/label.c:902
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff816ffa30-ffffffff81700562: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:902
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff81739810-ffffffff8173a336: __blk_label_update (STB_LOCAL)
ffffffff8173a658-ffffffff8173a6a0: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8175d560-ffffffff8175e0ac: __blk_label_update (STB_LOCAL)
ffffffff8175e348-ffffffff8175e36d: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8181cea0-ffffffff8181da4c: __blk_label_update (STB_LOCAL)
ffffffff8181de3b-ffffffff8181de62: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8182bf00-ffffffff8182cb6a: __blk_label_update (STB_LOCAL)
ffffffff81c15e1f-ffffffff81c15e44: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8180f210-ffffffff8180febc: __blk_label_update (STB_LOCAL)
ffffffff81c07b88-ffffffff81c07bad: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:994
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff818997a0-ffffffff8189a409: __blk_label_update (STB_LOCAL)
ffffffff81d0b4a7-ffffffff81d0b4cc: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095ecd0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffff80001095ecd0-ffff80001095f6a0: __blk_label_update (STB_LOCAL)
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
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a11090)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
c000000000a11090-c000000000a12048: __blk_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005ccb16)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffe0005ccb16-ffffffe0005cd402: __blk_label_update (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff81711c50-ffffffff8171279c: __blk_label_update (STB_LOCAL)
ffffffff81712a38-ffffffff81712a5d: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff816e56d0-ffffffff816e621c: __blk_label_update (STB_LOCAL)
ffffffff816e64b8-ffffffff816e64dd: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff81750a20-ffffffff8175156c: __blk_label_update (STB_LOCAL)
ffffffff81751808-ffffffff8175182d: __blk_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __blk_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_blk *nsblk, int num_labels);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:897
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_blk_namespace_label_update
```
**Symbols:**

```
ffffffff8176bea0-ffffffff8176c9ec: __blk_label_update (STB_LOCAL)
ffffffff8176cc88-ffffffff8176ccad: __blk_label_update.cold (STB_LOCAL)
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
