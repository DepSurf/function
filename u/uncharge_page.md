# Function: <code>uncharge_page</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125f2c0)
Location: mm/memcontrol.c:5658
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff8125f2c0-ffffffff8125f3c4: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81283780)
Location: mm/memcontrol.c:5726
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff81283780-ffffffff8128387f: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812972f0)
Location: mm/memcontrol.c:6057
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812972f0-ffffffff812973f8: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2e00)
Location: mm/memcontrol.c:6349
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812b2e00-ffffffff812b2f1d: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c48d0)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812c48d0-ffffffff812c49ef: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f9930)
Location: mm/memcontrol.c:6560
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812f9930-ffffffff812f9a02: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813056b0)
Location: mm/memcontrol.c:6818
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff813056b0-ffffffff813057bb: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130cce0)
Location: mm/memcontrol.c:6678
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff8130cce0-ffffffff8130cea9: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357650)
Location: mm/memcontrol.c:6862
Inline: False
Direct callers:
  - mm/memcontrol.c:__mem_cgroup_uncharge_list
  - mm/memcontrol.c:__mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff81357650-ffffffff8135783e: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103674f8)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffff8000103674f8-ffff800010367648: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0558c6c)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
c0558c6c-c0558d8c: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000454ad0)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
c000000000454ad0-c000000000454ca8: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002456c6)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffe0002456c6-ffffffe0002457bc: uncharge_page (STB_LOCAL)
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
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bceb0)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812bceb0-ffffffff812bcfcf: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812adff0)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812adff0-ffffffff812ae10f: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bacc0)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812bacc0-ffffffff812baddf: uncharge_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uncharge_page(struct page *page, struct uncharge_gather *ug);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cb410)
Location: mm/memcontrol.c:6689
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff812cb410-ffffffff812cb52f: uncharge_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
