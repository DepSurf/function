# Function: <code>__pmem_label_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815a06cf)
Location: drivers/nvdimm/label.c:493
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f6683)
Location: drivers/nvdimm/label.c:493
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81624592)
Location: drivers/nvdimm/label.c:493
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81639527)
Location: drivers/nvdimm/label.c:615
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
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
In drivers/nvdimm/label.c (ffffffff816a1bf7)
Location: drivers/nvdimm/label.c:617
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dd0e0)
Location: drivers/nvdimm/label.c:626
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff816dd0e0-ffffffff816dd63b: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ff430)
Location: drivers/nvdimm/label.c:756
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff816ff430-ffffffff816ff994: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817391d0)
Location: drivers/nvdimm/label.c:764
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff817391d0-ffffffff8173977e: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175cf20)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8175cf20-ffffffff8175d4ce: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181c850)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8181c850-ffffffff8181ce05: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182b930)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8182b930-ffffffff8182be61: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180ec50)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8180ec50-ffffffff8180f180: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:814
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81899220-ffffffff8189970d: __pmem_label_update (STB_LOCAL)
ffffffff81d0b492-ffffffff81d0b4a7: __pmem_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:873
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff819e3110-ffffffff819e39a5: __pmem_label_update (STB_LOCAL)
ffffffff81ed404a-ffffffff81ed42fb: __pmem_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:873
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81b5ed80-ffffffff81b5f5e4: __pmem_label_update (STB_LOCAL)
ffffffff8209b0a3-ffffffff8209b396: __pmem_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:873
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81bb2320-ffffffff81bb2b80: __pmem_label_update (STB_LOCAL)
ffffffff8211bf64-ffffffff8211c265: __pmem_label_update.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/label.c (0)
Location: drivers/nvdimm/label.c:873
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81c06810-ffffffff81c07070: __pmem_label_update (STB_LOCAL)
ffffffff821f9deb-ffffffff821fa0ec: __pmem_label_update.cold (STB_LOCAL)
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
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095e728)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffff80001095e728-ffff80001095ec1c: __pmem_label_update (STB_LOCAL)
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
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a10790)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
c000000000a10790-c000000000a10fa0: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005cc63a)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffe0005cc63a-ffffffe0005cca7a: __pmem_label_update (STB_LOCAL)
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
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81711610)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff81711610-ffffffff81711bbe: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e5090)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff816e5090-ffffffff816e563e: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817503e0)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff817503e0-ffffffff8175098e: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __pmem_label_update(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_namespace_pmem *nspm, int pos, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176b860)
Location: drivers/nvdimm/label.c:759
Inline: False
Direct callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
```
**Symbols:**

```
ffffffff8176b860-ffffffff8176be0e: __pmem_label_update (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int flags</code>
</li>
</ul>
</details>
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
