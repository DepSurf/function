# Function: <code>__fget_files_rcu</code>

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
In fs/file.c (ffffffff813982b5)
Location: fs/file.c:845
Inline: True
Inline callers:
  - fs/file.c:__fget_files
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
In fs/file.c (ffffffff8141af19)
Location: fs/file.c:854
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814a6ea2)
Location: fs/file.c:854
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff814dbe82)
Location: fs/file.c:855
Inline: True
Inline callers:
  - fs/file.c:__fget_light
  - fs/file.c:fget_task
  - fs/file.c:fget_raw
  - fs/file.c:fget
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
In fs/file.c (ffffffff8150edba)
Location: fs/file.c:955
Inline: True
Inline callers:
  - fs/file.c:__ia32_sys_dup
  - fs/file.c:__x64_sys_dup
  - fs/file.c:__ia32_sys_dup2
  - fs/file.c:__x64_sys_dup2
  - fs/file.c:__fdget_pos
  - fs/file.c:__fdget_raw
  - fs/file.c:task_lookup_next_fdget_rcu
  - fs/file.c:task_lookup_fdget_rcu
  - fs/file.c:lookup_fdget_rcu
  - fs/file.c:fget_task
  - fs/file.c:fget
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
