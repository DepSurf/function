# Function: <code>compat_copy_fs_qfilestat</code>

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
int compat_copy_fs_qfilestat(struct compat_fs_qfilestat *to, struct fs_qfilestat *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/quota.c (ffffffff813c4f80)
Location: fs/quota/quota.c:405
Inline: False
Direct callers:
  - fs/quota/quota.c:compat_copy_fs_quota_stat
  - fs/quota/quota.c:compat_copy_fs_quota_stat
```
**Symbols:**

```
ffffffff813c4f80-ffffffff813c4fc1: compat_copy_fs_qfilestat (STB_LOCAL)
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
In fs/quota/quota.c (ffffffff813cc6db)
Location: fs/quota/quota.c:406
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
In fs/quota/quota.c (ffffffff8141d99b)
Location: fs/quota/quota.c:406
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
In fs/quota/quota.c (ffffffff8149549f)
Location: fs/quota/quota.c:407
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
In fs/quota/quota.c (ffffffff8152939f)
Location: fs/quota/quota.c:407
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
In fs/quota/quota.c (ffffffff8156185f)
Location: fs/quota/quota.c:407
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
In fs/quota/quota.c (ffffffff81597f4f)
Location: fs/quota/quota.c:407
Inline: True
Inline callers:
  - fs/quota/quota.c:quota_getxstate
  - fs/quota/quota.c:quota_getxstate
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
</ul>
