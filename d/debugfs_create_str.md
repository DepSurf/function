# Function: <code>debugfs_create_str</code>

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
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6b80)
Location: fs/debugfs/file.c:951
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
**Symbols:**

```
ffffffff814a6b80-ffffffff814a6bce: debugfs_create_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fece0)
Location: fs/debugfs/file.c:936
Inline: False
Direct callers:
  - kernel/sched/debug.c:update_sched_domain_debugfs
```
**Symbols:**

```
ffffffff814fece0-ffffffff814fed2e: debugfs_create_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158fc40)
Location: fs/debugfs/file.c:936
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8158fc40-ffffffff8158fcbd: debugfs_create_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81636f50)
Location: fs/debugfs/file.c:952
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_sched_domain_debugfs
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff81636f50-ffffffff81636fcd: debugfs_create_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166eeb0)
Location: fs/debugfs/file.c:944
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff8166eeb0-ffffffff8166ef2d: debugfs_create_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void debugfs_create_str(const char *name, umode_t mode, struct dentry *parent, char **value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a99b0)
Location: fs/debugfs/file.c:1080
Inline: False
Direct callers:
  - drivers/opp/debugfs.c:opp_debug_create_one
```
**Symbols:**

```
ffffffff816a99b0-ffffffff816a9a2d: debugfs_create_str (STB_GLOBAL)
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
