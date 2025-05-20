# Function: <code>lookup_one_len</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218070)
Location: fs/namei.c:2287
Inline: False
Direct callers:
  - fs/quota/dquot.c:dquot_quota_on_mount
  - fs/kernfs/mount.c:kernfs_node_dentry
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
  - security/inode.c:securityfs_create_file
```
**Symbols:**

```
ffffffff81218070-ffffffff812181a1: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f050)
Location: fs/namei.c:2426
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8123f050-ffffffff8123f185: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251e20)
Location: fs/namei.c:2415
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff81251e20-ffffffff81251f55: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125dc80)
Location: fs/namei.c:2460
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aafs_create
```
**Symbols:**

```
ffffffff8125dc80-ffffffff8125dd90: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127ffe0)
Location: fs/namei.c:2458
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - fs/debugfs/inode.c:debugfs_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8127ffe0-ffffffff812800fa: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7c50)
Location: fs/namei.c:2506
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812a7c50-ffffffff812a7cd4: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bccf0)
Location: fs/namei.c:2530
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812bccf0-ffffffff812bcd74: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d9800)
Location: fs/namei.c:2528
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812d9800-ffffffff812d9886: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eb310)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812eb310-ffffffff812eb396: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81323f80)
Location: fs/namei.c:2549
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff81323f80-ffffffff81324002: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f580)
Location: fs/namei.c:2547
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_iter_link_pin_kernel
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff8132f580-ffffffff8132f602: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334c40)
Location: fs/namei.c:2637
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81334c40-ffffffff81334cc2: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813825a0)
Location: fs/namei.c:2673
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff813825a0-ffffffff81382631: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401ae0)
Location: fs/namei.c:2719
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81401ae0-ffffffff81401b8e: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148bc10)
Location: fs/namei.c:2698
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_rename
  - fs/tracefs/inode.c:start_creating
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff8148bc10-ffffffff8148bcbe: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c0710)
Location: fs/namei.c:2729
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814c0710-ffffffff814c07be: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f2bf0)
Location: fs/namei.c:2746
Inline: False
Direct callers:
  - fs/debugfs/inode.c:debugfs_rename
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814f2bf0-ffffffff814f2c9e: lookup_one_len (STB_GLOBAL)
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
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010394a88)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffff800010394a88-ffff800010394b3c: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057aa30)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c057aa30-c057ab18: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d9b0)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c00000000048d9b0-c00000000048da70: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000263502)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffe000263502-ffffffe000263570: lookup_one_len (STB_GLOBAL)
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
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e38f0)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e38f0-ffffffff812e3976: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d4530)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812d4530-ffffffff812d45b6: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e1700)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e1700-ffffffff812e1786: lookup_one_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *lookup_one_len(const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f2650)
Location: fs/namei.c:2521
Inline: False
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/debugfs/inode.c:start_creating
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f2650-ffffffff812f26d6: lookup_one_len (STB_GLOBAL)
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
