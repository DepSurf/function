# Function: <code>merge_dpa</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159c99d)
Location: drivers/nvdimm/namespace_devs.c:684
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f28c1)
Location: drivers/nvdimm/namespace_devs.c:681
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816200ea)
Location: drivers/nvdimm/namespace_devs.c:752
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81634bb9)
Location: drivers/nvdimm/namespace_devs.c:771
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169d539)
Location: drivers/nvdimm/namespace_devs.c:771
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816da184)
Location: drivers/nvdimm/namespace_devs.c:771
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fc121)
Location: drivers/nvdimm/namespace_devs.c:774
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8173600d)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81759d96)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81817140)
Location: drivers/nvdimm/namespace_devs.c:746
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81817140-ffffffff8181727c: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81826270)
Location: drivers/nvdimm/namespace_devs.c:746
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81826270-ffffffff818263ac: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818095f0)
Location: drivers/nvdimm/namespace_devs.c:746
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff818095f0-ffffffff81809711: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81893ab0)
Location: drivers/nvdimm/namespace_devs.c:746
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:grow_dpa_allocation
```
**Symbols:**

```
ffffffff81893ab0-ffffffff81893bce: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819dd9e0)
Location: drivers/nvdimm/namespace_devs.c:576
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff819dd9e0-ffffffff819ddb12: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b59230)
Location: drivers/nvdimm/namespace_devs.c:573
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81b59230-ffffffff81b59362: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81bac790)
Location: drivers/nvdimm/namespace_devs.c:573
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81bac790-ffffffff81bac8c5: merge_dpa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int merge_dpa(struct nd_region *nd_region, struct nd_mapping *nd_mapping, struct nd_label_id *label_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c00ad0)
Location: drivers/nvdimm/namespace_devs.c:578
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81c00ad0-ffffffff81c00c05: merge_dpa (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffff80001095b558)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (c000000000a0c0ec)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005c9a7c)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170e486)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e1f06)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174d256)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff817686d6)
Location: drivers/nvdimm/namespace_devs.c:766
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
