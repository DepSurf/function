# Function: <code>memtype_check_conflict</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode *newtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (0)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
```
**Symbols:**

```
ffffffff81090c10-ffffffff81090cdc: memtype_check_conflict (STB_LOCAL)
ffffffff810912ce-ffffffff8109135b: memtype_check_conflict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int memtype_check_conflict(u64 start, u64 end, enum page_cache_mode reqtype, enum page_cache_mode *newtype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (0)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
```
**Symbols:**

```
ffffffff810905d0-ffffffff8109069c: memtype_check_conflict (STB_LOCAL)
ffffffff81bd9bf8-ffffffff81bd9c85: memtype_check_conflict.cold (STB_LOCAL)
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091577)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a10f7)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b51b7)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d0018)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3637)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
In arch/x86/mm/pat/memtype_interval.c (ffffffff810dbdc7)
Location: arch/x86/mm/pat/memtype_interval.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
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
</ul>
