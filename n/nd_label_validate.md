# Function: <code>nd_label_validate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159f0c0)
Location: drivers/nvdimm/label.c:64
Inline: False
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
**Symbols:**

```
ffffffff8159f0c0-ffffffff8159f511: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f50f0)
Location: drivers/nvdimm/label.c:64
Inline: False
Direct callers:
  - drivers/nvdimm/dimm.c:nvdimm_probe
```
**Symbols:**

```
ffffffff815f50f0-ffffffff815f5545: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81622db0)
Location: drivers/nvdimm/label.c:64
Inline: False
```
**Symbols:**

```
ffffffff81622db0-ffffffff81623205: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816379e0)
Location: drivers/nvdimm/label.c:219
Inline: False
```
**Symbols:**

```
ffffffff816379e0-ffffffff81637f17: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a0200)
Location: drivers/nvdimm/label.c:221
Inline: False
```
**Symbols:**

```
ffffffff816a0200-ffffffff816a061b: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dc520)
Location: drivers/nvdimm/label.c:230
Inline: False
```
**Symbols:**

```
ffffffff816dc520-ffffffff816dc916: nd_label_validate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816fe879)
Location: drivers/nvdimm/label.c:238
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81738a12)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175c712)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181bf3d)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182af8d)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180e26d)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8189887d)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e2799)
Location: drivers/nvdimm/label.c:240
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5e3e4)
Location: drivers/nvdimm/label.c:240
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb19a4)
Location: drivers/nvdimm/label.c:240
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c05e94)
Location: drivers/nvdimm/label.c:240
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095de40)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a0fb08)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
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
In drivers/nvdimm/label.c (ffffffe0005cbed4)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81710e02)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e4882)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8174fbd2)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b052)
Location: drivers/nvdimm/label.c:232
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
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
</ul>
