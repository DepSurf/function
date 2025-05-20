# Function: <code>__traceiter_mm_migrate_pages</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ecb70)
Location: include/trace/events/migrate.h:46
Inline: False
```
**Symbols:**

```
ffffffff812ecb70-ffffffff812ecbe5: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f2d20)
Location: include/trace/events/migrate.h:47
Inline: False
```
**Symbols:**

```
ffffffff812f2d20-ffffffff812f2d93: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133d210)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff8133d210-ffffffff8133d283: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135a320)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff8135a320-ffffffff8135a3b5: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d4df0)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff813d4df0-ffffffff813d4e85: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81409c50)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff81409c50-ffffffff81409ce5: __traceiter_mm_migrate_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_mm_migrate_pages(void *__data, long unsigned int succeeded, long unsigned int failed, long unsigned int thp_succeeded, long unsigned int thp_failed, long unsigned int thp_split, long unsigned int large_folio_split, enum migrate_mode mode, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81436480)
Location: include/trace/events/migrate.h:48
Inline: False
```
**Symbols:**

```
ffffffff81436480-ffffffff8143651f: __traceiter_mm_migrate_pages (STB_GLOBAL)
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
