# Function: <code>PageBalloon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a3554)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/vmscan.c:reclaim_clean_pages_from_list
```
```
In mm/compaction.c (ffffffff811b5eb5)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
```
```
In mm/migrate.c (ffffffff811f137e)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/migrate.c:putback_movable_pages
  - mm/migrate.c:migrate_pages
  - mm/migrate.c:migrate_pages
```
```
In mm/balloon_compaction.c (ffffffff81207527)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - mm/balloon_compaction.c:balloon_page_isolate
  - mm/balloon_compaction.c:balloon_page_putback
  - mm/balloon_compaction.c:balloon_page_migrate
```
```
In fs/proc/page.c (ffffffff81288124)
Location: include/linux/page-flags.h:535
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff812b54f7)
Location: include/linux/page-flags.h:653
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff812cad58)
Location: include/linux/page-flags.h:669
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff812d81e8)
Location: include/linux/page-flags.h:672
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff812fc8e8)
Location: include/linux/page-flags.h:673
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff8132a4ee)
Location: include/linux/page-flags.h:689
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
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
In fs/proc/page.c (ffffffff81341811)
Location: include/linux/page-flags.h:712
Inline: True
Inline callers:
  - fs/proc/page.c:stable_page_flags
```
</details>
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
