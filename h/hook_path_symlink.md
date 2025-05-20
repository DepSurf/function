# Function: <code>hook_path_symlink</code>

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
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538c90)
Location: security/landlock/fs.c:619
Inline: False
```
**Symbols:**

```
ffffffff81538c90-ffffffff81538cd7: hook_path_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81597250)
Location: security/landlock/fs.c:619
Inline: False
```
**Symbols:**

```
ffffffff81597250-ffffffff81597297: hook_path_symlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1124
Inline: False
```
**Symbols:**

```
ffffffff8163bbf0-ffffffff8163bda0: hook_path_symlink (STB_LOCAL)
ffffffff81e89d9d-ffffffff81e89dcf: hook_path_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1139
Inline: False
```
**Symbols:**

```
ffffffff816f3440-ffffffff816f3608: hook_path_symlink (STB_LOCAL)
ffffffff82075228-ffffffff8207525a: hook_path_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1139
Inline: False
```
**Symbols:**

```
ffffffff8172d4f0-ffffffff8172d5ef: hook_path_symlink (STB_LOCAL)
ffffffff820f4d86-ffffffff820f4da7: hook_path_symlink.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_path_symlink(const const struct path * dir, const struct dentry * dentry, const const char * old_name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176df00)
Location: security/landlock/fs.c:1055
Inline: False
```
**Symbols:**

```
ffffffff8176df00-ffffffff8176df39: hook_path_symlink (STB_LOCAL)
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
