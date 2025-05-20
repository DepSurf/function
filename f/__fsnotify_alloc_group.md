# Function: <code>__fsnotify_alloc_group</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fsnotify_group *__fsnotify_alloc_group(const struct fsnotify_ops *ops, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8137aa50)
Location: fs/notify/group.c:114
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_alloc_user_group
  - fs/notify/group.c:fsnotify_alloc_group
```
**Symbols:**

```
ffffffff8137aa50-ffffffff8137aafc: __fsnotify_alloc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fsnotify_group *__fsnotify_alloc_group(const struct fsnotify_ops *ops, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff813c7710)
Location: fs/notify/group.c:115
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_alloc_user_group
  - fs/notify/group.c:fsnotify_alloc_group
```
**Symbols:**

```
ffffffff813c7710-ffffffff813c77dd: __fsnotify_alloc_group (STB_LOCAL)
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
In fs/notify/group.c (0)
Location: fs/notify/group.c:114
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
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
In fs/notify/group.c (0)
Location: fs/notify/group.c:114
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
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
In fs/notify/group.c (0)
Location: fs/notify/group.c:114
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
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
In fs/notify/group.c (ffffffff81547faf)
Location: fs/notify/group.c:114
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
