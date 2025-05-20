# Function: <code>force_swapin_readahead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void force_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811d1440)
Location: mm/madvise.c:175
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811d1440-ffffffff811d14ac: force_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void force_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811ee600)
Location: mm/madvise.c:179
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811ee600-ffffffff811ee66c: force_swapin_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void force_swapin_readahead(struct vm_area_struct *vma, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff811fef50)
Location: mm/madvise.c:179
Inline: False
Direct callers:
  - mm/madvise.c:SyS_madvise
```
**Symbols:**

```
ffffffff811fef50-ffffffff811fefbc: force_swapin_readahead (STB_LOCAL)
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
In mm/madvise.c (ffffffff81209f7e)
Location: mm/madvise.c:216
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81223164)
Location: mm/madvise.c:228
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81244d08)
Location: mm/madvise.c:228
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81259358)
Location: mm/madvise.c:228
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
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
In mm/madvise.c (ffffffff81274b8a)
Location: mm/madvise.c:228
Inline: True
Inline callers:
  - mm/madvise.c:madvise_willneed
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
