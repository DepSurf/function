# Function: <code>__nd_label_validate</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81637a0a)
Location: drivers/nvdimm/label.c:75
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a024c)
Location: drivers/nvdimm/label.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_validate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dc573)
Location: drivers/nvdimm/label.c:91
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_validate
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
In drivers/nvdimm/label.c (ffffffff816fe8ae)
Location: drivers/nvdimm/label.c:92
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_data_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81737d50-ffffffff817381e2: __nd_label_validate (STB_LOCAL)
ffffffff8173a5d8-ffffffff8173a5ef: __nd_label_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175ba20)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8175ba20-ffffffff8175beb2: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181b220)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8181b220-ffffffff8181b6aa: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182a280)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8182a280-ffffffff8182a70a: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180d550)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8180d550-ffffffff8180d9d2: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81897b50-ffffffff81897fcf: __nd_label_validate (STB_LOCAL)
ffffffff81d0b340-ffffffff81d0b39d: __nd_label_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:94
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff819e1940-ffffffff819e1e70: __nd_label_validate (STB_LOCAL)
ffffffff81ed3db6-ffffffff81ed3e1d: __nd_label_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:94
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81b5d5d0-ffffffff81b5da75: __nd_label_validate (STB_LOCAL)
ffffffff8209aed7-ffffffff8209af34: __nd_label_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:94
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81bb0b90-ffffffff81bb1033: __nd_label_validate (STB_LOCAL)
ffffffff8211bdeb-ffffffff8211be48: __nd_label_validate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:94
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81c05050-ffffffff81c054f3: __nd_label_validate (STB_LOCAL)
ffffffff821f9c72-ffffffff821f9ccf: __nd_label_validate.cold (STB_LOCAL)
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
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095d158)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffff80001095d158-ffff80001095d58c: __nd_label_validate (STB_LOCAL)
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
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a0e900)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
c000000000a0e900-c000000000a0eeac: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cb352)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffe0005cb352-ffffffe0005cb772: __nd_label_validate (STB_LOCAL)
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
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81710110)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff81710110-ffffffff817105a2: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e3b90)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff816e3b90-ffffffff816e4022: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8174eee0)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8174eee0-ffffffff8174f372: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __nd_label_validate(struct nvdimm_drvdata *ndd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176a360)
Location: drivers/nvdimm/label.c:86
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_label_data_init
  - drivers/nvdimm/label.c:nd_label_data_init
```
**Symbols:**

```
ffffffff8176a360-ffffffff8176a7f2: __nd_label_validate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
