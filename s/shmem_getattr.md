# Function: <code>shmem_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a82f0)
Location: mm/shmem.c:551
Inline: False
```
**Symbols:**

```
ffffffff811a82f0-ffffffff811a8349: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811bfba0)
Location: mm/shmem.c:945
Inline: False
```
**Symbols:**

```
ffffffff811bfba0-ffffffff811bfc00: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d0120)
Location: mm/shmem.c:951
Inline: False
```
**Symbols:**

```
ffffffff811d0120-ffffffff811d0180: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d8870)
Location: mm/shmem.c:967
Inline: False
```
**Symbols:**

```
ffffffff811d8870-ffffffff811d88da: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eddc0)
Location: mm/shmem.c:990
Inline: False
```
**Symbols:**

```
ffffffff811eddc0-ffffffff811ede2a: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120e980)
Location: mm/shmem.c:999
Inline: False
```
**Symbols:**

```
ffffffff8120e980-ffffffff8120ea1e: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81221a90)
Location: mm/shmem.c:978
Inline: False
```
**Symbols:**

```
ffffffff81221a90-ffffffff81221b2e: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81231310)
Location: mm/shmem.c:985
Inline: False
```
**Symbols:**

```
ffffffff81231310-ffffffff812313b1: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123f3d0)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffff8123f3d0-ffffffff8123f471: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126cc10)
Location: mm/shmem.c:1004
Inline: False
```
**Symbols:**

```
ffffffff8126cc10-ffffffff8126ccb1: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81277560)
Location: mm/shmem.c:1063
Inline: False
```
**Symbols:**

```
ffffffff81277560-ffffffff81277601: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127c740)
Location: mm/shmem.c:1035
Inline: False
```
**Symbols:**

```
ffffffff8127c740-ffffffff8127c7e8: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bf600)
Location: mm/shmem.c:1068
Inline: False
```
**Symbols:**

```
ffffffff812bf600-ffffffff812bf689: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81316d10)
Location: mm/shmem.c:1049
Inline: False
```
**Symbols:**

```
ffffffff81316d10-ffffffff81316dd4: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8138b720)
Location: mm/shmem.c:1048
Inline: False
```
**Symbols:**

```
ffffffff8138b720-ffffffff8138b817: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813bdb50)
Location: mm/shmem.c:1057
Inline: False
```
**Symbols:**

```
ffffffff813bdb50-ffffffff813bdc4d: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813e8440)
Location: mm/shmem.c:1120
Inline: False
```
**Symbols:**

```
ffffffff813e8440-ffffffff813e852b: shmem_getattr (STB_LOCAL)
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
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d10e8)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffff8000102d10e8-ffff8000102d1218: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fa9f0)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
c04fa9f0-c04faa6c: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000390820)
Location: mm/shmem.c:1000
Inline: True
```
**Symbols:**

```
c000000000390820-c000000000390990: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001edf2a)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffe0001edf2a-ffffffe0001edfd0: shmem_getattr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81237a20)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffff81237a20-ffffffff81237ac1: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122a8e0)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffff8122a8e0-ffffffff8122a97b: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812357c0)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffff812357c0-ffffffff81235861: shmem_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81245840)
Location: mm/shmem.c:1000
Inline: False
```
**Symbols:**

```
ffffffff81245840-ffffffff812458d8: shmem_getattr (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct path *path</code>
</li>
<li>
<b>Param added. </b>
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vfsmount *mnt</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *dentry</code>
</li>
<li>
<b>Param reordered. </b>
<code>mnt, dentry, stat</code> ➡️ <code>path, stat, request_mask, query_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>path, stat, request_mask, query_flags</code> ➡️ <code>mnt_userns, path, stat, request_mask, query_flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
