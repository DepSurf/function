# Function: <code>__nvdimm_setup_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f864a)
Location: drivers/nvdimm/pfn_devs.c:516
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff816268ba)
Location: drivers/nvdimm/pfn_devs.c:516
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff8163bd36)
Location: drivers/nvdimm/pfn_devs.c:524
Inline: True
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
In drivers/nvdimm/pfn_devs.c (ffffffff816a4996)
Location: drivers/nvdimm/pfn_devs.c:545
Inline: True
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
In drivers/nvdimm/pfn_devs.c (ffffffff816e09df)
Location: drivers/nvdimm/pfn_devs.c:544
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff81702f5f)
Location: drivers/nvdimm/pfn_devs.c:603
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff8173ce78)
Location: drivers/nvdimm/pfn_devs.c:609
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff81760c78)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:673
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff818203e0-ffffffff81820585: __nvdimm_setup_pfn (STB_LOCAL)
ffffffff8182107a-ffffffff81821092: __nvdimm_setup_pfn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:673
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8182f310-ffffffff8182f479: __nvdimm_setup_pfn (STB_LOCAL)
ffffffff81c15fce-ffffffff81c15fe6: __nvdimm_setup_pfn.cold (STB_LOCAL)
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
In drivers/nvdimm/pfn_devs.c (ffffffff81812ad7)
Location: drivers/nvdimm/pfn_devs.c:673
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff8189d167)
Location: drivers/nvdimm/pfn_devs.c:673
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff819e6a76)
Location: drivers/nvdimm/pfn_devs.c:675
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b627d0)
Location: drivers/nvdimm/pfn_devs.c:677
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81b627d0-ffffffff81b62954: __nvdimm_setup_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb5db0)
Location: drivers/nvdimm/pfn_devs.c:677
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81bb5db0-ffffffff81bb5f34: __nvdimm_setup_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a390)
Location: drivers/nvdimm/pfn_devs.c:682
Inline: False
Direct callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81c0a390-ffffffff81c0a524: __nvdimm_setup_pfn (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a16410)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/nvdimm/pfn_devs.c (ffffffff81715368)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff816e8de8)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff81754138)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
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
In drivers/nvdimm/pfn_devs.c (ffffffff8176f5a8)
Location: drivers/nvdimm/pfn_devs.c:663
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
