# Function: <code>wp_clean_pmd_entry</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff8130c820)
Location: mm/mapping_dirty_helpers.c:123
Inline: False
```
**Symbols:**

```
ffffffff8130c820-ffffffff8130c9a0: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff81318760)
Location: mm/mapping_dirty_helpers.c:125
Inline: False
```
**Symbols:**

```
ffffffff81318760-ffffffff813188e0: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff8131e950)
Location: mm/mapping_dirty_helpers.c:125
Inline: False
```
**Symbols:**

```
ffffffff8131e950-ffffffff8131ead0: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff8136bd30)
Location: mm/mapping_dirty_helpers.c:125
Inline: False
```
**Symbols:**

```
ffffffff8136bd30-ffffffff8136beb0: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff813e9f40)
Location: mm/mapping_dirty_helpers.c:126
Inline: False
```
**Symbols:**

```
ffffffff813e9f40-ffffffff813ea0c7: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff81471fe0)
Location: mm/mapping_dirty_helpers.c:126
Inline: False
```
**Symbols:**

```
ffffffff81471fe0-ffffffff81472167: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff814a6910)
Location: mm/mapping_dirty_helpers.c:126
Inline: False
```
**Symbols:**

```
ffffffff814a6910-ffffffff814a69ac: wp_clean_pmd_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wp_clean_pmd_entry(pmd_t *pmd, long unsigned int addr, long unsigned int end, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mapping_dirty_helpers.c (ffffffff814d7990)
Location: mm/mapping_dirty_helpers.c:126
Inline: False
```
**Symbols:**

```
ffffffff814d7990-ffffffff814d7a61: wp_clean_pmd_entry (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
