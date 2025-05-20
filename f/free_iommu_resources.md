# Function: <code>free_iommu_resources</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f4b20)
Location: drivers/iommu/amd_iommu_init.c:2112
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff820f4b20-ffffffff820f4cb7: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826fe1e0)
Location: drivers/iommu/amd_iommu_init.c:2286
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff826fe1e0-ffffffff826fe377: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff827284a0)
Location: drivers/iommu/amd_iommu_init.c:2287
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff827284a0-ffffffff82728637: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e07cd)
Location: drivers/iommu/amd_iommu_init.c:2322
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu_init.c:amd_iommu_init
  - drivers/iommu/amd_iommu_init.c:iommu_go_to_state
```
**Symbols:**

```
ffffffff828e07cd-ffffffff828e0964: free_iommu_resources (STB_LOCAL)
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
In drivers/iommu/amd_iommu_init.c (ffffffff828fce8a)
Location: drivers/iommu/amd_iommu_init.c:2398
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82905e62)
Location: drivers/iommu/amd_iommu_init.c:2418
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff82d1b145)
Location: drivers/iommu/amd/init.c:2388
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff82d1b145-ffffffff82d1b2c9: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83008ee8)
Location: drivers/iommu/amd/init.c:2592
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff83008ee8-ffffffff83009099: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff83213a18)
Location: drivers/iommu/amd/init.c:2545
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff83213a18-ffffffff83213bc9: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff832fccb6)
Location: drivers/iommu/amd/init.c:2577
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff832fccb6-ffffffff832fce67: free_iommu_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_iommu_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff834b589a)
Location: drivers/iommu/amd/init.c:2591
Inline: False
Direct callers:
  - drivers/iommu/amd/init.c:state_next
```
**Symbols:**

```
ffffffff834b589a-ffffffff834b5a30: free_iommu_resources (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff83ef3e2f)
Location: drivers/iommu/amd/init.c:2872
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
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
In drivers/iommu/amd/init.c (ffffffff837199df)
Location: drivers/iommu/amd/init.c:2940
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
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
In drivers/iommu/amd/init.c (ffffffff8394d4df)
Location: drivers/iommu/amd/init.c:2958
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff828ed649)
Location: drivers/iommu/amd_iommu_init.c:2418
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff828e4ad6)
Location: drivers/iommu/amd_iommu_init.c:2418
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82901185)
Location: drivers/iommu/amd_iommu_init.c:2418
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
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
In drivers/iommu/amd_iommu_init.c (ffffffff82906ec4)
Location: drivers/iommu/amd_iommu_init.c:2418
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:state_next
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
