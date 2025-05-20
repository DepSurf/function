# Function: <code>mm_set_has_pinned_flag</code>

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
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d9d56)
Location: mm/gup.c:440
Inline: True
Inline callers:
  - mm/gup.c:pin_user_pages_locked
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
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
In mm/gup.c (ffffffff8133b309)
Location: mm/gup.c:437
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
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
In mm/gup.c (ffffffff813b2ec8)
Location: mm/gup.c:452
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
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
In mm/gup.c (ffffffff813e7b88)
Location: mm/gup.c:496
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
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
In mm/gup.c (ffffffff814127f8)
Location: mm/gup.c:496
Inline: True
Inline callers:
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:internal_get_user_pages_fast
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages_unlocked
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:get_user_pages_remote
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
  - mm/gup.c:__gup_longterm_locked
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
