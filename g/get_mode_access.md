# Function: <code>get_mode_access</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538ac0)
Location: security/landlock/fs.c:519
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
  - security/landlock/fs.c:hook_path_link
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
In security/landlock/fs.c (ffffffff81597422)
Location: security/landlock/fs.c:519
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:hook_path_rename
  - security/landlock/fs.c:hook_path_link
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
In security/landlock/fs.c (ffffffff8163bdf7)
Location: security/landlock/fs.c:661
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/fs.c (ffffffff816f23a7)
Location: security/landlock/fs.c:662
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
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
In security/landlock/fs.c (ffffffff8172c7f7)
Location: security/landlock/fs.c:662
Inline: True
Inline callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
access_mask_t get_mode_access(const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176c6b0)
Location: security/landlock/fs.c:578
Inline: False
Direct callers:
  - security/landlock/fs.c:hook_path_mknod
  - security/landlock/fs.c:current_check_refer_path
  - security/landlock/fs.c:current_check_refer_path
```
**Symbols:**

```
ffffffff8176c6b0-ffffffff8176c73c: get_mode_access (STB_LOCAL)
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
