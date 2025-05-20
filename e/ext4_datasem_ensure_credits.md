# Function: <code>ext4_datasem_ensure_credits</code>

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
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813dfeb0)
Location: fs/ext4/extents.c:117
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813dfeb0-ffffffff813dff51: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f1770)
Location: fs/ext4/extents.c:117
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813f1770-ffffffff813f1811: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f7bf0)
Location: fs/ext4/extents.c:117
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813f7bf0-ffffffff813f7c91: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144a0d0)
Location: fs/ext4/extents.c:117
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8144a0d0-ffffffff8144a171: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c6820)
Location: fs/ext4/extents.c:117
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff814c6820-ffffffff814c68d0: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8155ee10)
Location: fs/ext4/extents.c:136
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8155ee10-ffffffff8155eec0: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81596bd0)
Location: fs/ext4/extents.c:136
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff81596bd0-ffffffff81596c80: ext4_datasem_ensure_credits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_datasem_ensure_credits(handle_t *handle, struct inode *inode, int check_cred, int restart_cred, int revoke_cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815cf880)
Location: fs/ext4/extents.c:136
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_shift_path_extents
  - fs/ext4/extents.c:ext4_ext_rm_leaf
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff815cf880-ffffffff815cf92e: ext4_datasem_ensure_credits (STB_GLOBAL)
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
