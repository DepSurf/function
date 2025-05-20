# Function: <code>is_access_to_paths_allowed</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:485
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff816f1190-ffffffff816f233e: is_access_to_paths_allowed (STB_LOCAL)
ffffffff82074f99-ffffffff820750c9: is_access_to_paths_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:485
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff8172b600-ffffffff8172c787: is_access_to_paths_allowed (STB_LOCAL)
ffffffff820f4b63-ffffffff820f4c87: is_access_to_paths_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_access_to_paths_allowed(const const struct landlock_ruleset * domain, const const struct path * path, const access_mask_t access_request_parent1, const layer_mask_t[15] * layer_masks_parent1, const const struct dentry * dentry_child1, const access_mask_t access_request_parent2, const layer_mask_t[15] * layer_masks_parent2, const const struct dentry * dentry_child2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176cdb0)
Location: security/landlock/fs.c:396
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:check_access_path
```
**Symbols:**

```
ffffffff8176cdb0-ffffffff8176d4cb: is_access_to_paths_allowed (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
