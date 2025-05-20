# Function: <code>nd_label_active_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159f730)
Location: drivers/nvdimm/label.c:321
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8159f730-ffffffff8159f841: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f5750)
Location: drivers/nvdimm/label.c:321
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff815f5750-ffffffff815f585a: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81623410)
Location: drivers/nvdimm/label.c:321
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81623410-ffffffff8162351a: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81638150)
Location: drivers/nvdimm/label.c:402
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81638150-ffffffff8163825e: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a0850)
Location: drivers/nvdimm/label.c:404
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816a0850-ffffffff816a095e: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dcb60)
Location: drivers/nvdimm/label.c:413
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816dcb60-ffffffff816dcc5c: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816feeb0)
Location: drivers/nvdimm/label.c:543
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816feeb0-ffffffff816fefac: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81738c40)
Location: drivers/nvdimm/label.c:540
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81738c40-ffffffff81738d40: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175c940)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8175c940-ffffffff8175ca55: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff8181dce5-ffffffff8181dd98: nd_label_active_count.cold (STB_LOCAL)
ffffffff8181c170-ffffffff8181c2f8: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff81c15cc9-ffffffff81c15d7c: nd_label_active_count.cold (STB_LOCAL)
ffffffff8182b1c0-ffffffff8182b348: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff81c07a22-ffffffff81c07ad5: nd_label_active_count.cold (STB_LOCAL)
ffffffff8180e4a0-ffffffff8180e643: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:551
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff81d0b3bd-ffffffff81d0b3df: nd_label_active_count.cold (STB_LOCAL)
ffffffff81898ab0-ffffffff81898c45: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:556
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff81ed3ec0-ffffffff81ed3f69: nd_label_active_count.cold (STB_LOCAL)
ffffffff819e2980-ffffffff819e2b2c: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:556
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff8209afd7-ffffffff8209b063: nd_label_active_count.cold (STB_LOCAL)
ffffffff81b5e5e0-ffffffff81b5e70d: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:556
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff8211bebf-ffffffff8211bf47: nd_label_active_count.cold (STB_LOCAL)
ffffffff81bb1b90-ffffffff81bb1cbd: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:556
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
```
**Symbols:**

```
ffffffff821f9d46-ffffffff821f9dce: nd_label_active_count.cold (STB_LOCAL)
ffffffff81c06080-ffffffff81c061ad: nd_label_active_count (STB_GLOBAL)
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
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e080)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffff80001095e080-ffff80001095e1d8: nd_label_active_count (STB_GLOBAL)
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
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a0fe30)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
c000000000a0fe30-c000000000a10044: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc08a)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffe0005cc08a-ffffffe0005cc1c0: nd_label_active_count (STB_GLOBAL)
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
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81711030)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff81711030-ffffffff81711145: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4ab0)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff816e4ab0-ffffffff816e4bc5: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8174fe00)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8174fe00-ffffffff8174ff15: nd_label_active_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nd_label_active_count(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b280)
Location: drivers/nvdimm/label.c:535
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
```
**Symbols:**

```
ffffffff8176b280-ffffffff8176b395: nd_label_active_count (STB_GLOBAL)
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
