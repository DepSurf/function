# Function: <code>hook_path_mkdir</code>

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
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538c40)
Location: security/landlock/fs.c:601
Inline: False
```
**Symbols:**

```
ffffffff81538c40-ffffffff81538c87: hook_path_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81597200)
Location: security/landlock/fs.c:601
Inline: False
```
**Symbols:**

```
ffffffff81597200-ffffffff81597247: hook_path_mkdir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1106
Inline: False
```
**Symbols:**

```
ffffffff8163b890-ffffffff8163ba40: hook_path_mkdir (STB_LOCAL)
ffffffff81e89d39-ffffffff81e89d6b: hook_path_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1121
Inline: False
```
**Symbols:**

```
ffffffff816f3260-ffffffff816f3428: hook_path_mkdir (STB_LOCAL)
ffffffff820751f6-ffffffff82075228: hook_path_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1121
Inline: False
```
**Symbols:**

```
ffffffff8172d820-ffffffff8172d91f: hook_path_mkdir (STB_LOCAL)
ffffffff820f4de9-ffffffff820f4e0a: hook_path_mkdir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_path_mkdir(const const struct path * dir, const struct dentry * dentry, const umode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176deb0)
Location: security/landlock/fs.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8176deb0-ffffffff8176dee9: hook_path_mkdir (STB_LOCAL)
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
