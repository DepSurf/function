# Function: <code>ecryptfs_get_lower_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813039a0)
Location: fs/ecryptfs/main.c:137
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_setattr
```
**Symbols:**

```
ffffffff813039a0-ffffffff81303a7d: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81337960)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81337960-ffffffff81337a3b: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8134d730)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8134d730-ffffffff8134d80b: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff813622d0)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813622d0-ffffffff8136238b: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81386f50)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81386f50-ffffffff8138700b: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813b5eb4-ffffffff813b5ee4: ecryptfs_get_lower_file.cold.10 (STB_LOCAL)
ffffffff813b5c40-ffffffff813b5cd3: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:136
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813cf419-ffffffff813cf449: ecryptfs_get_lower_file.cold.10 (STB_LOCAL)
ffffffff813cf1c0-ffffffff813cf253: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813f9fe4-ffffffff813fa015: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff813f9d80-ffffffff813f9e15: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81413eb4-ffffffff81413ee5: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff81413c50-ffffffff81413ce5: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff814620e2-ffffffff81462113: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff81461df0-ffffffff81461e85: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup_interpose
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81bee358-ffffffff81bee389: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff8147d960-ffffffff8147d9f5: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81be03e3-ffffffff81be0414: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff81483520-ffffffff814835b5: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81cd0b38-ffffffff81cd0b69: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff814daca0-ffffffff814dad35: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81e83d7c-ffffffff81e83da7: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff81568620-ffffffff815686bf: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8160bf00)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff8160bf00-ffffffff8160bfcd: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff81643de0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff81643de0-ffffffff81643eb1: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffff8167d370)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_initialize_file
```
**Symbols:**

```
ffffffff8167d370-ffffffff8167d447: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffff8000104f5130)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffff8000104f5130-ffff8000104f5218: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c06b2a08)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:truncate_upper
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
c06b2a08-c06b2b0c: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (c000000000635a60)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
c000000000635a60-c000000000635ba8: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/main.c (ffffffe0003641a6)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffe0003641a6-ffffffe000364250: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8140c494-ffffffff8140c4c5: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff8140c230-ffffffff8140c2c5: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813fcf14-ffffffff813fcf45: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff813fccb0-ffffffff813fcd45: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81409814-ffffffff81409845: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff814095b0-ffffffff81409645: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_get_lower_file(struct dentry *dentry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/main.c (0)
Location: fs/ecryptfs/main.c:122
Inline: False
Direct callers:
  - fs/ecryptfs/file.c:ecryptfs_open
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8141f4d4-ffffffff8141f505: ecryptfs_get_lower_file.cold (STB_LOCAL)
ffffffff8141f270-ffffffff8141f305: ecryptfs_get_lower_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
