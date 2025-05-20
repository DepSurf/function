# Function: <code>mnt_alloc_group_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b8c0)
Location: fs/namespace.c:132
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff8122b8c0-ffffffff8122b918: mnt_alloc_group_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254030)
Location: fs/namespace.c:132
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff81254030-ffffffff81254088: mnt_alloc_group_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267370)
Location: fs/namespace.c:131
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff81267370-ffffffff812673c8: mnt_alloc_group_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274bd0)
Location: fs/namespace.c:134
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff81274bd0-ffffffff81274c28: mnt_alloc_group_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297500)
Location: fs/namespace.c:134
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff81297500-ffffffff81297558: mnt_alloc_group_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mnt_alloc_group_id(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd6f0)
Location: fs/namespace.c:134
Inline: False
Direct callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff812bd6f0-ffffffff812bd748: mnt_alloc_group_id (STB_LOCAL)
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
In fs/namespace.c (ffffffff812d2c56)
Location: fs/namespace.c:118
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efdf0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813018c0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ad30)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346980)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff8134cc10)
Location: fs/namespace.c:143
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff8139ab10)
Location: fs/namespace.c:143
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff8141dad8)
Location: fs/namespace.c:144
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff814aa3c8)
Location: fs/namespace.c:161
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff814df0e8)
Location: fs/namespace.c:145
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
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
In fs/namespace.c (ffffffff81511ed8)
Location: fs/namespace.c:150
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b3f78)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592e6c)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004afdd0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277766)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9ea0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eaac0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7c90)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308fd0)
Location: fs/namespace.c:123
Inline: True
Inline callers:
  - fs/namespace.c:invent_group_ids
  - fs/namespace.c:clone_mnt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
