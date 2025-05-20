# Function: <code>copy_translation_tables</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81fab1f0)
Location: drivers/iommu/intel-iommu.c:2991
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
In drivers/iommu/intel-iommu.c (ffffffff81fd7d60)
Location: drivers/iommu/intel-iommu.c:3035
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
In drivers/iommu/intel-iommu.c (ffffffff820159c0)
Location: drivers/iommu/intel-iommu.c:3112
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
In drivers/iommu/intel-iommu.c (ffffffff820f7676)
Location: drivers/iommu/intel-iommu.c:3120
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
In drivers/iommu/intel-iommu.c (ffffffff82700d57)
Location: drivers/iommu/intel-iommu.c:3144
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
In drivers/iommu/intel-iommu.c (ffffffff8272aa75)
Location: drivers/iommu/intel-iommu.c:3200
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
In drivers/iommu/intel-iommu.c (ffffffff828e334d)
Location: drivers/iommu/intel-iommu.c:3204
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816cbf22)
Location: drivers/iommu/intel-iommu.c:3092
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816cbf22-ffffffff816cc2f4: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ef7e4)
Location: drivers/iommu/intel-iommu.c:3103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816ef7e4-ffffffff816efbb6: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a7192)
Location: drivers/iommu/intel/iommu.c:2988
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817a7192-ffffffff817a736f: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81c0c8f8)
Location: drivers/iommu/intel/iommu.c:3002
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81c0c8f8-ffffffff81c0cad0: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81bfe07a)
Location: drivers/iommu/intel/iommu.c:3042
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81bfe07a-ffffffff81bfe252: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81cffde0)
Location: drivers/iommu/intel/iommu.c:3035
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81cffde0-ffffffff81cfffb8: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ec84df)
Location: drivers/iommu/intel/iommu.c:2815
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ec84df-ffffffff81ec86f2: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac3970)
Location: drivers/iommu/intel/iommu.c:2723
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ac3970-ffffffff81ac3bc4: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0f470)
Location: drivers/iommu/intel/iommu.c:2687
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b0f470-ffffffff81b0f6e3: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b63d60)
Location: drivers/iommu/intel/iommu.c:2552
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b63d60-ffffffff81b63fd3: copy_translation_tables (STB_LOCAL)
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
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b4fd4)
Location: drivers/iommu/intel-iommu.c:3103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b4fd4-ffffffff816b539c: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81692c14)
Location: drivers/iommu/intel-iommu.c:3103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81692c14-ffffffff81692fe6: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816e34a4)
Location: drivers/iommu/intel-iommu.c:3103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e34a4-ffffffff816e3876: copy_translation_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_translation_tables(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fdb34)
Location: drivers/iommu/intel-iommu.c:3103
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816fdb34-ffffffff816fdf06: copy_translation_tables (STB_LOCAL)
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
