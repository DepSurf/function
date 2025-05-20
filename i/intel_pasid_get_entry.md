# Function: <code>intel_pasid_get_entry</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff81694260)
Location: drivers/iommu/intel-pasid.c:239
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81694260-ffffffff81694357: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-pasid.c (0)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816cd473-ffffffff816cd489: intel_pasid_get_entry.cold (STB_LOCAL)
ffffffff816ccb80-ffffffff816ccc71: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816f03c0)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816f03c0-ffffffff816f04c2: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7aa0)
Location: drivers/iommu/intel/pasid.c:245
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff817a7aa0-ffffffff817a7bcd: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, u32 pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b3950)
Location: drivers/iommu/intel/pasid.c:245
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff817b3950-ffffffff817b3a6e: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817963b0)
Location: drivers/iommu/intel/pasid.c:244
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff817963b0-ffffffff817964b8: intel_pasid_get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, u32 pasid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8181e340)
Location: drivers/iommu/intel/pasid.c:244
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8181e340-ffffffff8181e448: intel_pasid_get_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8195e750)
Location: drivers/iommu/intel/pasid.c:181
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8195e750-ffffffff8195e84d: intel_pasid_get_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6120)
Location: drivers/iommu/intel/pasid.c:186
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81ac6120-ffffffff81ac624b: intel_pasid_get_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b12cf0)
Location: drivers/iommu/intel/pasid.c:186
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81b12cf0-ffffffff81b12e20: intel_pasid_get_entry.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b67b30)
Location: drivers/iommu/intel/pasid.c:129
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_dirty_tracking
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81b67b30-ffffffff81b67c60: intel_pasid_get_entry.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816b5bb0)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816b5bb0-ffffffff816b5cb2: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816937f0)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816937f0-ffffffff816938f2: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816e4080)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816e4080-ffffffff816e4182: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pasid_entry *intel_pasid_get_entry(struct device *dev, int pasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-pasid.c (ffffffff816fe750)
Location: drivers/iommu/intel-pasid.c:224
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816fe750-ffffffff816fe84f: intel_pasid_get_entry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
