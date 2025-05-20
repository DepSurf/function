# Function: <code>grow_dpa_allocation</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff8159c811)
Location: drivers/nvdimm/namespace_devs.c:789
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f2884)
Location: drivers/nvdimm/namespace_devs.c:786
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
In drivers/nvdimm/namespace_devs.c (ffffffff816200ad)
Location: drivers/nvdimm/namespace_devs.c:857
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
In drivers/nvdimm/namespace_devs.c (ffffffff81634b72)
Location: drivers/nvdimm/namespace_devs.c:876
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
In drivers/nvdimm/namespace_devs.c (ffffffff8169d4f2)
Location: drivers/nvdimm/namespace_devs.c:876
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
In drivers/nvdimm/namespace_devs.c (ffffffff816da094)
Location: drivers/nvdimm/namespace_devs.c:876
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fc031)
Location: drivers/nvdimm/namespace_devs.c:879
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
In drivers/nvdimm/namespace_devs.c (ffffffff81735f14)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffff81759c9d)
Location: drivers/nvdimm/namespace_devs.c:871
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
int grow_dpa_allocation(struct nd_region *nd_region, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818195e0)
Location: drivers/nvdimm/namespace_devs.c:851
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff818195e0-ffffffff81819797: grow_dpa_allocation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int grow_dpa_allocation(struct nd_region *nd_region, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81828700)
Location: drivers/nvdimm/namespace_devs.c:851
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81828700-ffffffff818288b7: grow_dpa_allocation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int grow_dpa_allocation(struct nd_region *nd_region, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8180b920)
Location: drivers/nvdimm/namespace_devs.c:851
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff8180b920-ffffffff8180bad5: grow_dpa_allocation (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int grow_dpa_allocation(struct nd_region *nd_region, struct nd_label_id *label_id, resource_size_t n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/namespace_devs.c:851
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
```
**Symbols:**

```
ffffffff81895f40-ffffffff81896101: grow_dpa_allocation (STB_LOCAL)
ffffffff81d0b26f-ffffffff81d0b283: grow_dpa_allocation.cold (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff819df663)
Location: drivers/nvdimm/namespace_devs.c:668
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5aba2)
Location: drivers/nvdimm/namespace_devs.c:665
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81bae404)
Location: drivers/nvdimm/namespace_devs.c:665
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c02774)
Location: drivers/nvdimm/namespace_devs.c:672
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:__size_store
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
In drivers/nvdimm/namespace_devs.c (ffff80001095b478)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (c000000000a0bfa4)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffe0005c9a3e)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffff8170e38d)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffff816e1e0d)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffff8174d15d)
Location: drivers/nvdimm/namespace_devs.c:871
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
In drivers/nvdimm/namespace_devs.c (ffffffff817685dd)
Location: drivers/nvdimm/namespace_devs.c:871
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
</ul>
