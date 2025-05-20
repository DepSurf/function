# Function: <code>hook_path_rename</code>

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
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538920)
Location: security/landlock/fs.c:579
Inline: False
```
**Symbols:**

```
ffffffff81538920-ffffffff81538a29: hook_path_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81597080)
Location: security/landlock/fs.c:579
Inline: False
```
**Symbols:**

```
ffffffff81597080-ffffffff81597193: hook_path_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8163b670)
Location: security/landlock/fs.c:1095
Inline: False
```
**Symbols:**

```
ffffffff8163b670-ffffffff8163b6a4: hook_path_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff816f2ec0)
Location: security/landlock/fs.c:1110
Inline: False
```
**Symbols:**

```
ffffffff816f2ec0-ffffffff816f2ef4: hook_path_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8172d330)
Location: security/landlock/fs.c:1110
Inline: False
```
**Symbols:**

```
ffffffff8172d330-ffffffff8172d364: hook_path_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_path_rename(const const struct path * old_dir, const struct dentry * old_dentry, const const struct path * new_dir, const struct dentry * new_dentry, const unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176de20)
Location: security/landlock/fs.c:1027
Inline: False
```
**Symbols:**

```
ffffffff8176de20-ffffffff8176de54: hook_path_rename (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const unsigned int flags</code>
</li>
</ul>
</details>
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
