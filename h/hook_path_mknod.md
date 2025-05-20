# Function: <code>hook_path_mknod</code>

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
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff81538a90)
Location: security/landlock/fs.c:607
Inline: False
```
**Symbols:**

```
ffffffff81538a90-ffffffff81538b57: hook_path_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff815973f0)
Location: security/landlock/fs.c:607
Inline: False
```
**Symbols:**

```
ffffffff815973f0-ffffffff815974b5: hook_path_mknod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1112
Inline: False
```
**Symbols:**

```
ffffffff8163bda0-ffffffff8163c015: hook_path_mknod (STB_LOCAL)
ffffffff81e89dcf-ffffffff81e89e09: hook_path_mknod.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1127
Inline: False
```
**Symbols:**

```
ffffffff816f2350-ffffffff816f25e5: hook_path_mknod (STB_LOCAL)
ffffffff820750c9-ffffffff82075105: hook_path_mknod.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (0)
Location: security/landlock/fs.c:1127
Inline: False
```
**Symbols:**

```
ffffffff8172c7a0-ffffffff8172ca27: hook_path_mknod (STB_LOCAL)
ffffffff820f4c87-ffffffff820f4cc3: hook_path_mknod.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hook_path_mknod(const const struct path * dir, const struct dentry * dentry, const umode_t mode, const unsigned int dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/landlock/fs.c (ffffffff8176d5f0)
Location: security/landlock/fs.c:1044
Inline: False
```
**Symbols:**

```
ffffffff8176d5f0-ffffffff8176d639: hook_path_mknod (STB_LOCAL)
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
