# Function: <code>current_check_refer_path</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:811
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff8163b100-ffffffff8163b667: current_check_refer_path (STB_LOCAL)
ffffffff81e89cba-ffffffff81e89d07: current_check_refer_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:813
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff816f28f0-ffffffff816f2ea9: current_check_refer_path (STB_LOCAL)
ffffffff8207514b-ffffffff820751a3: current_check_refer_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:813
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff8172cd50-ffffffff8172d31e: current_check_refer_path (STB_LOCAL)
ffffffff820f4d0d-ffffffff820f4d65: current_check_refer_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int current_check_refer_path(const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const bool removable, const bool exchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176db30)
Location: security/landlock/fs.c:731
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff8176db30-ffffffff8176de01: current_check_refer_path (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
