# Function: <code>statfs_by_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812419d0)
Location: fs/statfs.c:49
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812419d0-ffffffff81241a5a: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81269d10)
Location: fs/statfs.c:49
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff81269d10-ffffffff81269d9a: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8127ccc0)
Location: fs/statfs.c:49
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff8127ccc0-ffffffff8127cd4a: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8128a1d0)
Location: fs/statfs.c:52
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff8128a1d0-ffffffff8128a255: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812acd10)
Location: fs/statfs.c:53
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812acd10-ffffffff812acd9b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812d4c90)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812d4c90-ffffffff812d4d1b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff812ea060)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
```
**Symbols:**

```
ffffffff812ea060-ffffffff812ea0eb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81308a60)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81308a60-ffffffff81308aeb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8131bad0)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff8131bad0-ffffffff8131bb5b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81355430)
Location: fs/statfs.c:53
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81355430-ffffffff813554bb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81361d50)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81361d50-ffffffff81361ddb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81368830)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81368830-ffffffff813688bb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813b7530)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff813b7530-ffffffff813b75bb: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff8143cbe0)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff8143cbe0-ffffffff8143cc83: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff814cb350)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff814cb350-ffffffff814cb3f3: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81501590)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81501590-ffffffff81501633: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff815361e0)
Location: fs/statfs.c:55
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:fd_statfs
  - fs/statfs.c:user_statfs
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff815361e0-ffffffff81536283: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffff8000103d2ec8)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffff8000103d2ec8-ffff8000103d2f60: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c05ad848)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
c05ad848-c05ad8d4: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (c0000000004d5d70)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
c0000000004d5d70-c0000000004d5e38: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffe00028e06c)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffe00028e06c-ffffffe00028e0d8: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813140b0)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff813140b0-ffffffff8131413b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81304cc0)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81304cc0-ffffffff81304d4b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff81311ea0)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff81311ea0-ffffffff81311f2b: statfs_by_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int statfs_by_dentry(struct dentry *dentry, struct kstatfs *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/statfs.c (ffffffff813236e0)
Location: fs/statfs.c:53
Inline: True
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/statfs.c:vfs_get_fsid
```
**Symbols:**

```
ffffffff813236e0-ffffffff8132376b: statfs_by_dentry (STB_LOCAL)
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
