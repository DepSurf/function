# Function: <code>empty_dir_getattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int empty_dir_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81233830)
Location: fs/libfs.c:1115
Inline: False
```
**Symbols:**

```
ffffffff81233830-ffffffff81233849: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int empty_dir_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125bff0)
Location: fs/libfs.c:1139
Inline: False
```
**Symbols:**

```
ffffffff8125bff0-ffffffff8125c009: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int empty_dir_getattr(struct vfsmount *mnt, struct dentry *dentry, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126f560)
Location: fs/libfs.c:1146
Inline: False
```
**Symbols:**

```
ffffffff8126f560-ffffffff8126f579: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127cd40)
Location: fs/libfs.c:1151
Inline: False
```
**Symbols:**

```
ffffffff8127cd40-ffffffff8127cd5a: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129f7e0)
Location: fs/libfs.c:1151
Inline: False
```
**Symbols:**

```
ffffffff8129f7e0-ffffffff8129f7fa: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6240)
Location: fs/libfs.c:1190
Inline: False
```
**Symbols:**

```
ffffffff812c6240-ffffffff812c625a: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812db440)
Location: fs/libfs.c:1190
Inline: False
```
**Symbols:**

```
ffffffff812db440-ffffffff812db45a: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f9a80)
Location: fs/libfs.c:1223
Inline: False
```
**Symbols:**

```
ffffffff812f9a80-ffffffff812f9a9a: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130b6b0)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff8130b6b0-ffffffff8130b6ca: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81344eb0)
Location: fs/libfs.c:1299
Inline: False
```
**Symbols:**

```
ffffffff81344eb0-ffffffff81344eca: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813511a0)
Location: fs/libfs.c:1303
Inline: False
```
**Symbols:**

```
ffffffff813511a0-ffffffff813511ba: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int empty_dir_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81357ea0)
Location: fs/libfs.c:1301
Inline: False
```
**Symbols:**

```
ffffffff81357ea0-ffffffff81357ec1: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int empty_dir_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a62c0)
Location: fs/libfs.c:1285
Inline: False
```
**Symbols:**

```
ffffffff813a62c0-ffffffff813a62e1: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int empty_dir_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142a740)
Location: fs/libfs.c:1301
Inline: False
```
**Symbols:**

```
ffffffff8142a740-ffffffff8142a76b: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int empty_dir_getattr(struct user_namespace *mnt_userns, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b7a90)
Location: fs/libfs.c:1318
Inline: False
```
**Symbols:**

```
ffffffff814b7a90-ffffffff814b7abb: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int empty_dir_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ec8e0)
Location: fs/libfs.c:1313
Inline: False
```
**Symbols:**

```
ffffffff814ec8e0-ffffffff814ec90b: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int empty_dir_getattr(struct mnt_idmap *idmap, const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81520820)
Location: fs/libfs.c:1624
Inline: False
```
**Symbols:**

```
ffffffff81520820-ffffffff81520858: empty_dir_getattr (STB_LOCAL)
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
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103bfc70)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffff8000103bfc70-ffff8000103bfcac: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059c9d4)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
c059c9d4-c059c9fc: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004be5f0)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
c0000000004be5f0-c0000000004be630: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe0002804a8)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffe0002804a8-ffffffe0002804e0: empty_dir_getattr (STB_LOCAL)
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
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81303c90)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81303c90-ffffffff81303caa: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f48b0)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff812f48b0-ffffffff812f48ca: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81301a80)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81301a80-ffffffff81301a9a: empty_dir_getattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int empty_dir_getattr(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81312e50)
Location: fs/libfs.c:1263
Inline: False
```
**Symbols:**

```
ffffffff81312e50-ffffffff81312e6a: empty_dir_getattr (STB_LOCAL)
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
