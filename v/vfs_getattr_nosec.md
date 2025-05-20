# Function: <code>vfs_getattr_nosec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_getattr_nosec(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812112d0)
Location: fs/stat.c:52
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812112d0-ffffffff8121130a: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_getattr_nosec(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81237d80)
Location: fs/stat.c:52
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81237d80-ffffffff81237db7: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_getattr_nosec(struct path *path, struct kstat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124aa40)
Location: fs/stat.c:52
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8124aa40-ffffffff8124aa77: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812566a0)
Location: fs/stat.c:68
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812566a0-ffffffff8125671e: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812788e0)
Location: fs/stat.c:69
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812788e0-ffffffff81278961: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8129f220)
Location: fs/stat.c:69
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8129f220-ffffffff8129f2a1: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812b4200)
Location: fs/stat.c:69
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812b4200-ffffffff812b4281: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d0f40)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812d0f40-ffffffff812d0fe9: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e2ad0)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812e2ad0-ffffffff812e2b79: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81319dd0)
Location: fs/stat.c:67
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_statx_fd
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81319dd0-ffffffff81319e8a: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81325460)
Location: fs/stat.c:67
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81325460-ffffffff8132551a: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8132b590)
Location: fs/stat.c:75
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff8132b590-ffffffff8132b65b: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81378d00)
Location: fs/stat.c:93
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff81378d00-ffffffff81378dcb: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff813f8140)
Location: fs/stat.c:93
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff813f8140-ffffffff813f8234: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814815f0)
Location: fs/stat.c:97
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff814815f0-ffffffff81481703: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814b61c0)
Location: fs/stat.c:98
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/exportfs/expfs.c:get_name
  - security/integrity/ima/ima_main.c:ima_check_last_writer
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814b61c0-ffffffff814b6307: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff814e8510)
Location: fs/stat.c:105
Inline: False
Direct callers:
  - fs/stat.c:vfs_statx
  - fs/stat.c:vfs_fstat
  - fs/ecryptfs/inode.c:ecryptfs_getattr
  - fs/exportfs/expfs.c:get_name
  - security/integrity/ima/ima_main.c:ima_check_last_writer
  - security/integrity/ima/ima_api.c:ima_collect_measurement
```
**Symbols:**

```
ffffffff814e8510-ffffffff814e860f: vfs_getattr_nosec (STB_GLOBAL)
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
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffff80001038a410)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffff80001038a410-ffff80001038a550: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c0572698)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
c0572698-c0572744: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (c000000000481650)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
c000000000481650-c000000000481760: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffe00025c400)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffe00025c400-ffffffe00025c4a0: vfs_getattr_nosec (STB_GLOBAL)
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
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812db0b0)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812db0b0-ffffffff812db159: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812cbd30)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812cbd30-ffffffff812cbdd9: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812d8ec0)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812d8ec0-ffffffff812d8f69: vfs_getattr_nosec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_getattr_nosec(const struct path *path, struct kstat *stat, u32 request_mask, unsigned int query_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812e9dd0)
Location: fs/stat.c:64
Inline: False
Direct callers:
  - fs/stat.c:vfs_getattr
  - fs/exportfs/expfs.c:get_name
```
**Symbols:**

```
ffffffff812e9dd0-ffffffff812e9e79: vfs_getattr_nosec (STB_GLOBAL)
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
<code>u32 request_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int query_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
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
