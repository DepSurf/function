# Function: <code>fuse_queue_forget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813112d0)
Location: fs/fuse/dev.c:341
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff813112d0-ffffffff81311353: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81345740)
Location: fs/fuse/dev.c:321
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81345740-ffffffff813457c8: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8135b460)
Location: fs/fuse/dev.c:321
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8135b460-ffffffff8135b4e8: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136fde0)
Location: fs/fuse/dev.c:321
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8136fde0-ffffffff8136fe68: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81394ae0)
Location: fs/fuse/dev.c:321
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81394ae0-ffffffff81394b68: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c3c00)
Location: fs/fuse/dev.c:334
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff813c3c00-ffffffff813c3c88: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dd3b0)
Location: fs/fuse/dev.c:382
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff813dd3b0-ffffffff813dd438: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81408ef0)
Location: fs/fuse/dev.c:384
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81408ef0-ffffffff81408f73: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81422b10)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81422b10-ffffffff81422b83: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81471cf0)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81471cf0-ffffffff81471d63: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148c560)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8148c560-ffffffff8148c5d3: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81491e60)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81491e60-ffffffff81491ed3: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e9950)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff814e9950-ffffffff814e99c3: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81578160)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81578160-ffffffff815781ed: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161d6f0)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8161d6f0-ffffffff8161d77d: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81655810)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81655810-ffffffff8165589d: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168ef70)
Location: fs/fuse/dev.c:236
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8168ef70-ffffffff8168effd: fuse_queue_forget (STB_GLOBAL)
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
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff8000105058b0)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffff8000105058b0-ffff800010505988: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c1c80)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
c06c1c80-c06c1d00: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c00000000064aee0)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
c00000000064aee0-c00000000064afdc: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe0003721e2)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffe0003721e2-ffffffe00037229a: fuse_queue_forget (STB_GLOBAL)
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
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141b0f0)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8141b0f0-ffffffff8141b163: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140bb70)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8140bb70-ffffffff8140bbe3: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81417290)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff81417290-ffffffff81417303: fuse_queue_forget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fuse_queue_forget(struct fuse_conn *fc, struct fuse_forget_link *forget, u64 nodeid, u64 nlookup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142e020)
Location: fs/fuse/dev.c:232
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_create_open
  - fs/fuse/dir.c:fuse_lookup_name
  - fs/fuse/dir.c:fuse_dentry_revalidate
  - fs/fuse/inode.c:fuse_evict_inode
```
**Symbols:**

```
ffffffff8142e020-ffffffff8142e091: fuse_queue_forget (STB_GLOBAL)
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
