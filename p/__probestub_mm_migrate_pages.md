# Function: <code>__probestub_mm_migrate_pages</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
void __probestub_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81409d00)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff81409d00-ffffffff81409d0f: __probestub_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __probestub_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, long unsigned int large_folio_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81436530)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff81436530-ffffffff8143653f: __probestub_mm_migrate_pages (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int large_folio_split</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, mode, reason</code> ➡️ <code>__data, succeeded, failed, thp_succeeded, thp_failed, thp_split, large_folio_split, mode, reason</code>
</li>
</ul>
</details>
</li>
</ul>
