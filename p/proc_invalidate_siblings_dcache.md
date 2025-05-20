# Function: <code>proc_invalidate_siblings_dcache</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813b9e50)
Location: fs/proc/inode.c:113
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff813b9e50-ffffffff813b9f79: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813cb8e0)
Location: fs/proc/inode.c:113
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff813cb8e0-ffffffff813cba18: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813d28d0)
Location: fs/proc/inode.c:113
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff813d28d0-ffffffff813d2a08: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81423e20)
Location: fs/proc/inode.c:113
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff81423e20-ffffffff81423f58: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8149c970)
Location: fs/proc/inode.c:113
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff8149c970-ffffffff8149cad9: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81531370)
Location: fs/proc/inode.c:111
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff81531370-ffffffff815314d9: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81569520)
Location: fs/proc/inode.c:111
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff81569520-ffffffff815696a4: proc_invalidate_siblings_dcache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void proc_invalidate_siblings_dcache(struct hlist_head *inodes, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff815a1b40)
Location: fs/proc/inode.c:108
Inline: False
Direct callers:
  - fs/proc/base.c:proc_flush_pid
  - fs/proc/proc_sysctl.c:drop_sysctl_table
```
**Symbols:**

```
ffffffff815a1b40-ffffffff815a1cc4: proc_invalidate_siblings_dcache (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
