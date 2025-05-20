# Function: <code>addr_to_metadata</code>

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
In mm/kfence/core.c (ffffffff8133c97f)
Location: mm/kfence/core.c:140
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813afd9e)
Location: mm/kfence/kfence.h:99
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/kfence/report.c (ffffffff813b0755)
Location: mm/kfence/kfence.h:99
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8143039e)
Location: mm/kfence/kfence.h:99
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_check_all_canary
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
```
```
In mm/kfence/report.c (ffffffff814312b5)
Location: mm/kfence/kfence.h:99
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81465d17)
Location: mm/kfence/kfence.h:107
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/kfence/report.c (ffffffff81466c35)
Location: mm/kfence/kfence.h:107
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81494f9c)
Location: mm/kfence/kfence.h:110
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:__kfence_free
  - mm/kfence/core.c:kfence_object_start
  - mm/kfence/core.c:kfence_ksize
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
  - mm/kfence/core.c:check_canary
```
```
In mm/kfence/report.c (ffffffff81495e45)
Location: mm/kfence/kfence.h:110
Inline: True
Inline callers:
  - mm/kfence/report.c:__kfence_obj_info
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
