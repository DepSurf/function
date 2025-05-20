# Function: <code>workingset_test_recent</code>

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
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool workingset_test_recent(void *shadow, bool file, bool *workingset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:417
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff820e33dc-ffffffff820e33f8: workingset_test_recent.cold (STB_LOCAL)
ffffffff813e19b0-ffffffff813e1c44: workingset_test_recent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool workingset_test_recent(void *shadow, bool file, bool *workingset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/workingset.c (0)
Location: mm/workingset.c:417
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff821bfe3c-ffffffff821bfe54: workingset_test_recent.cold (STB_LOCAL)
ffffffff8140c0e0-ffffffff8140c486: workingset_test_recent (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
