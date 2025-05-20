# Function: <code>is_valid_gup_flags</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_valid_gup_flags(unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812953c5)
Location: mm/gup.c:1679
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
Direct callers:
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff812914d0-ffffffff812914fc: is_valid_gup_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_valid_gup_flags(unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129ad35)
Location: mm/gup.c:1745
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
Direct callers:
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
```
**Symbols:**

```
ffffffff812969f0-ffffffff81296a1c: is_valid_gup_flags (STB_LOCAL)
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
In mm/gup.c (ffffffff812db705)
Location: mm/gup.c:1833
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
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
In mm/gup.c (ffffffff8133b405)
Location: mm/gup.c:2022
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
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
In mm/gup.c (ffffffff813b2f65)
Location: mm/gup.c:2096
Inline: True
Inline callers:
  - mm/gup.c:get_user_pages_fast
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
