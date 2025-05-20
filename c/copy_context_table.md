# Function: <code>copy_context_table</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81fab29d)
Location: drivers/iommu/intel-iommu.c:2889
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff81fd7e22)
Location: drivers/iommu/intel-iommu.c:2933
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82015a82)
Location: drivers/iommu/intel-iommu.c:3010
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff820f7730)
Location: drivers/iommu/intel-iommu.c:3018
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82700e11)
Location: drivers/iommu/intel-iommu.c:3042
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff8272ab35)
Location: drivers/iommu/intel-iommu.c:3098
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff828e340d)
Location: drivers/iommu/intel-iommu.c:3102
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff816cbfeb)
Location: drivers/iommu/intel-iommu.c:2990
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
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
In drivers/iommu/intel-iommu.c (ffffffff816ef8ad)
Location: drivers/iommu/intel-iommu.c:3001
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a6f71)
Location: drivers/iommu/intel/iommu.c:2886
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff817a6f71-ffffffff817a7192: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81c0c6d7)
Location: drivers/iommu/intel/iommu.c:2900
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81c0c6d7-ffffffff81c0c8f8: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81bfde69)
Location: drivers/iommu/intel/iommu.c:2940
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81bfde69-ffffffff81bfe07a: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81cffbc2)
Location: drivers/iommu/intel/iommu.c:2933
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81cffbc2-ffffffff81cffde0: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ec8282)
Location: drivers/iommu/intel/iommu.c:2713
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81ec8282-ffffffff81ec84df: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac3680)
Location: drivers/iommu/intel/iommu.c:2639
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81ac3680-ffffffff81ac3953: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0f170)
Location: drivers/iommu/intel/iommu.c:2603
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81b0f170-ffffffff81b0f455: copy_context_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_context_table(struct intel_iommu *iommu, struct root_entry *old_re, struct context_entry **tbl, int bus, bool ext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b63a60)
Location: drivers/iommu/intel/iommu.c:2468
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:copy_translation_tables
```
**Symbols:**

```
ffffffff81b63a60-ffffffff81b63d45: copy_context_table (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b5093)
Location: drivers/iommu/intel-iommu.c:3001
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
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
In drivers/iommu/intel-iommu.c (ffffffff81692cdd)
Location: drivers/iommu/intel-iommu.c:3001
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
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
In drivers/iommu/intel-iommu.c (ffffffff816e356d)
Location: drivers/iommu/intel-iommu.c:3001
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
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
In drivers/iommu/intel-iommu.c (ffffffff816fdbfd)
Location: drivers/iommu/intel-iommu.c:3001
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:copy_translation_tables
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
