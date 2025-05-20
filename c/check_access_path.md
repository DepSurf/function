# Function: <code>check_access_path</code>

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
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, u32 access_request);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff81538d5e)
Location: security/landlock/fs.c:230
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mkdir
Direct callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff81538680-ffffffff81538855: check_access_path.part.0 (STB_LOCAL)
ffffffff81538860-ffffffff81538886: check_access_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff815973e1)
Location: security/landlock/fs.c:230
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
Direct callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
```
**Symbols:**

```
ffffffff81596e70-ffffffff81597077: check_access_path.part.0 (STB_LOCAL)
ffffffff81cd6b78-ffffffff81cd6bc2: check_access_path.part.0.cold (STB_LOCAL)
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
In security/landlock/fs.c (ffffffff8163aeed)
Location: security/landlock/fs.c:639
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_file_open
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
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
In security/landlock/fs.c (ffffffff816f3185)
Location: security/landlock/fs.c:638
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
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
In security/landlock/fs.c (ffffffff8172d415)
Location: security/landlock/fs.c:638
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_access_path(const const struct landlock_ruleset * domain, const const struct path * path, access_mask_t access_request);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176d4e0)
Location: security/landlock/fs.c:554
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_truncate
  - security/landlock/fs.c:hook_path_rmdir
  - security/landlock/fs.c:hook_path_unlink
  - security/landlock/fs.c:hook_path_symlink
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mkdir
```
**Symbols:**

```
ffffffff8176d4e0-ffffffff8176d58a: check_access_path (STB_LOCAL)
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
