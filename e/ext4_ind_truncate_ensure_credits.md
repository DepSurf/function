# Function: <code>ext4_ind_truncate_ensure_credits</code>

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
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff813ef880)
Location: fs/ext4/indirect.c:713
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff813ef880-ffffffff813efa7d: ext4_ind_truncate_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff81401fd0)
Location: fs/ext4/indirect.c:714
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff81401fd0-ffffffff814021d9: ext4_ind_truncate_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/indirect.c (ffffffff814083d0)
Location: fs/ext4/indirect.c:714
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff814083d0-ffffffff814085d5: ext4_ind_truncate_ensure_credits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (0)
Location: fs/ext4/indirect.c:716
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff8145ae00-ffffffff8145b038: ext4_ind_truncate_ensure_credits (STB_LOCAL)
ffffffff81cca554-ffffffff81cca59b: ext4_ind_truncate_ensure_credits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (0)
Location: fs/ext4/indirect.c:716
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff814d8b80-ffffffff814d8dc2: ext4_ind_truncate_ensure_credits (STB_LOCAL)
ffffffff81e7d276-ffffffff81e7d2bd: ext4_ind_truncate_ensure_credits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (0)
Location: fs/ext4/indirect.c:723
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff81571990-ffffffff81571bd2: ext4_ind_truncate_ensure_credits (STB_LOCAL)
ffffffff8206d833-ffffffff8206d87a: ext4_ind_truncate_ensure_credits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (0)
Location: fs/ext4/indirect.c:731
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff815a9720-ffffffff815a9962: ext4_ind_truncate_ensure_credits (STB_LOCAL)
ffffffff820ed4d0-ffffffff820ed517: ext4_ind_truncate_ensure_credits.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_ind_truncate_ensure_credits(handle_t *handle, struct inode *inode, struct buffer_head *bh, int revoke_creds);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/indirect.c (0)
Location: fs/ext4/indirect.c:731
Inline: False
Direct callers:
  - fs/ext4/indirect.c:ext4_free_branches
  - fs/ext4/indirect.c:ext4_clear_blocks
```
**Symbols:**

```
ffffffff815e24d0-ffffffff815e2710: ext4_ind_truncate_ensure_credits (STB_LOCAL)
ffffffff821ca5fb-ffffffff821ca642: ext4_ind_truncate_ensure_credits.cold (STB_LOCAL)
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
