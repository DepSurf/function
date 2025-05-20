# Function: <code>kobj_to_node_hstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811d9a80)
Location: mm/hugetlb.c:2509
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff811d9a80-ffffffff811d9aee: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811f7cc0)
Location: mm/hugetlb.c:2560
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff811f7cc0-ffffffff811f7d2c: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81208670)
Location: mm/hugetlb.c:2666
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81208670-ffffffff812086dc: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81213ca0)
Location: mm/hugetlb.c:2644
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81213ca0-ffffffff81213d11: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8122e870)
Location: mm/hugetlb.c:2652
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8122e870-ffffffff8122e8e0: kobj_to_node_hstate (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2654
Inline: True
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:2648
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81280bb0)
Location: mm/hugetlb.c:2716
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81280bb0-ffffffff81280bff: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812905c0)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812905c0-ffffffff8129060f: kobj_to_node_hstate (STB_LOCAL)
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3116
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3072
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3237
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3522
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3907
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4064
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4094
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4352
Inline: True
Inline callers:
  - mm/hugetlb.c:kobj_to_hstate
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
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff80001032d758)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffff80001032d758-ffff80001032d7e8: kobj_to_node_hstate (STB_LOCAL)
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
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c0000000004052e0)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
c0000000004052e0-c000000000405380: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (ffffffe00022bdec)
Location: mm/hugetlb.c:2932
Inline: True
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store
  - mm/hugetlb.c:nr_hugepages_show
```
**Symbols:**

```
ffffffe00022bdec-ffffffe00022be00: kobj_to_node_hstate.isra.0 (STB_LOCAL)
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
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81288ba0)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff81288ba0-ffffffff81288bef: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127aa40)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff8127aa40-ffffffff8127aa8f: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812869b0)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812869b0-ffffffff812869ff: kobj_to_node_hstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct hstate *kobj_to_node_hstate(struct kobject *kobj, int *nidp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812967a0)
Location: mm/hugetlb.c:2833
Inline: False
Direct callers:
  - mm/hugetlb.c:surplus_hugepages_show
  - mm/hugetlb.c:resv_hugepages_show
  - mm/hugetlb.c:free_hugepages_show
  - mm/hugetlb.c:nr_overcommit_hugepages_store
  - mm/hugetlb.c:nr_overcommit_hugepages_show
  - mm/hugetlb.c:nr_hugepages_store_common
```
**Symbols:**

```
ffffffff812967a0-ffffffff812967ef: kobj_to_node_hstate (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
