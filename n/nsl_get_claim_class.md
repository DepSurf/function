# Function: <code>nsl_get_claim_class</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8189a470)
Location: drivers/nvdimm/label.c:806
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8189a470-ffffffff8189a529: nsl_get_claim_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:859
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff81ed434d-ffffffff81ed4393: nsl_get_claim_class.cold (STB_LOCAL)
ffffffff819e3b00-ffffffff819e3d10: nsl_get_claim_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:859
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8209b3e8-ffffffff8209b42e: nsl_get_claim_class.cold (STB_LOCAL)
ffffffff81b5f770-ffffffff81b5f980: nsl_get_claim_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:859
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff8211c2b7-ffffffff8211c2fd: nsl_get_claim_class.cold (STB_LOCAL)
ffffffff81bb2d00-ffffffff81bb2f19: nsl_get_claim_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum nvdimm_claim_class nsl_get_claim_class(struct nvdimm_drvdata *ndd, struct nd_namespace_label *nd_label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:859
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
```
**Symbols:**

```
ffffffff821fa13e-ffffffff821fa184: nsl_get_claim_class.cold (STB_LOCAL)
ffffffff81c071f0-ffffffff81c07409: nsl_get_claim_class (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
