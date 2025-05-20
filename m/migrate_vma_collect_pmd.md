# Function: <code>migrate_vma_collect_pmd</code>

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
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124b100)
Location: mm/migrate.c:2178
Inline: False
```
**Symbols:**

```
ffffffff8124b100-ffffffff8124ba50: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8126dd10)
Location: mm/migrate.c:2190
Inline: False
```
**Symbols:**

```
ffffffff8126dd10-ffffffff8126e657: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff81282b80)
Location: mm/migrate.c:2170
Inline: False
```
**Symbols:**

```
ffffffff81282b80-ffffffff812834e5: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ae620)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
ffffffff812ae620-ffffffff812aef61: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e3c80)
Location: mm/migrate.c:2196
Inline: False
```
**Symbols:**

```
ffffffff812e3c80-ffffffff812e46ea: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ef9e0)
Location: mm/migrate.c:2356
Inline: False
```
**Symbols:**

```
ffffffff812ef9e0-ffffffff812f03c4: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f5360)
Location: mm/migrate.c:2319
Inline: False
```
**Symbols:**

```
ffffffff812f5360-ffffffff812f5d41: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133f960)
Location: mm/migrate.c:2248
Inline: False
```
**Symbols:**

```
ffffffff8133f960-ffffffff8134030b: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff813b6dc0)
Location: mm/migrate_device.c:56
Inline: False
```
**Symbols:**

```
ffffffff813b6dc0-ffffffff813b7bc5: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate_device.c (0)
Location: mm/migrate_device.c:57
Inline: False
```
**Symbols:**

```
ffffffff81438920-ffffffff8143988d: migrate_vma_collect_pmd (STB_LOCAL)
ffffffff82067a4d-ffffffff82067ac7: migrate_vma_collect_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate_device.c (0)
Location: mm/migrate_device.c:57
Inline: False
```
**Symbols:**

```
ffffffff8146f030-ffffffff8146fd13: migrate_vma_collect_pmd (STB_LOCAL)
ffffffff820e73d4-ffffffff820e7430: migrate_vma_collect_pmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/migrate_device.c (0)
Location: mm/migrate_device.c:57
Inline: False
```
**Symbols:**

```
ffffffff8149db30-ffffffff8149e66d: migrate_vma_collect_pmd (STB_LOCAL)
ffffffff821c4021-ffffffff821c40c3: migrate_vma_collect_pmd.cold (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000434340)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
c000000000434340-c000000000435264: migrate_vma_collect_pmd (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a6c00)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
ffffffff812a6c00-ffffffff812a7541: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812986a0)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
ffffffff812986a0-ffffffff81298f92: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812a4a10)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
ffffffff812a4a10-ffffffff812a5351: migrate_vma_collect_pmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_vma_collect_pmd(pmd_t *pmdp, long unsigned int start, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812b5560)
Location: mm/migrate.c:2188
Inline: False
```
**Symbols:**

```
ffffffff812b5560-ffffffff812b5ea7: migrate_vma_collect_pmd (STB_LOCAL)
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
