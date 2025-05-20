# Function: <code>nsblk_add_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159d7a0)
Location: drivers/nvdimm/namespace_devs.c:1682
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8159d7a0-ffffffff8159d877: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff815f3780)
Location: drivers/nvdimm/namespace_devs.c:1724
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff815f3780-ffffffff815f3857: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816215a0)
Location: drivers/nvdimm/namespace_devs.c:1824
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816215a0-ffffffff81621677: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81635fd0)
Location: drivers/nvdimm/namespace_devs.c:2001
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81635fd0-ffffffff816360ac: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169e3d0)
Location: drivers/nvdimm/namespace_devs.c:2010
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8169e3d0-ffffffff8169e4ac: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816da810)
Location: drivers/nvdimm/namespace_devs.c:2004
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816da810-ffffffff816da8e7: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816fc7a0)
Location: drivers/nvdimm/namespace_devs.c:2030
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816fc7a0-ffffffff816fc877: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81736850)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81736850-ffffffff8173692c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8175a5e0)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8175a5e0-ffffffff8175a6bc: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8181a130)
Location: drivers/nvdimm/namespace_devs.c:2080
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8181a130-ffffffff8181a20c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81829250)
Location: drivers/nvdimm/namespace_devs.c:2080
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81829250-ffffffff8182932c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180c460)
Location: drivers/nvdimm/namespace_devs.c:2080
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8180c460-ffffffff8180c53c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81896a90)
Location: drivers/nvdimm/namespace_devs.c:2073
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81896a90-ffffffff81896b6c: nsblk_add_resource (STB_GLOBAL)
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
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffff80001095bdb0)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffff80001095bdb0-ffff80001095be94: nsblk_add_resource (STB_GLOBAL)
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
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a0cea0)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
c000000000a0cea0-c000000000a0d198: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005ca2ae)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffe0005ca2ae-ffffffe0005ca34c: nsblk_add_resource (STB_GLOBAL)
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
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170ecd0)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8170ecd0-ffffffff8170edac: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816e2750)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff816e2750-ffffffff816e282c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174daa0)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff8174daa0-ffffffff8174db7c: nsblk_add_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct resource *nsblk_add_resource(struct nd_region *nd_region, struct nvdimm_drvdata *ndd, struct nd_namespace_blk *nsblk, resource_size_t start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81768f20)
Location: drivers/nvdimm/namespace_devs.c:2037
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/label.c:__blk_label_update
```
**Symbols:**

```
ffffffff81768f20-ffffffff81768ffc: nsblk_add_resource (STB_GLOBAL)
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
