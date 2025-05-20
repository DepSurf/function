# Function: <code>__audit_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81128a30)
Location: kernel/auditsc.c:1753
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_mountpoint
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_unlink
```
**Symbols:**

```
ffffffff81128a30-ffffffff81128d45: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81130bc0)
Location: kernel/auditsc.c:1752
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81130bc0-ffffffff81130ed9: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113a930)
Location: kernel/auditsc.c:1757
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff8113a930-ffffffff8113ac49: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8113bf70)
Location: kernel/auditsc.c:1766
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8113bf70-ffffffff8113c251: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81148cf0)
Location: kernel/auditsc.c:1766
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - ipc/mqueue.c:SyS_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81148cf0-ffffffff81148fd1: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1773
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81158750-ffffffff8115878b: __audit_inode.cold.20 (STB_LOCAL)
ffffffff811576c0-ffffffff81157976: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1759
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8116573f-ffffffff8116577a: __audit_inode.cold.22 (STB_LOCAL)
ffffffff811646c0-ffffffff81164976: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff811722a0-ffffffff811722db: __audit_inode.cold (STB_LOCAL)
ffffffff81171330-ffffffff81171657: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8117e150-ffffffff8117e18b: __audit_inode.cold (STB_LOCAL)
ffffffff8117d1b0-ffffffff8117d4d7: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81190510)
Location: kernel/auditsc.c:1975
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81190510-ffffffff81190727: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118d730)
Location: kernel/auditsc.c:1992
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8118d730-ffffffff8118d94c: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1989
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81bd6828-ffffffff81bd6863: __audit_inode.cold (STB_LOCAL)
ffffffff8118e570-ffffffff8118e8b3: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:2002
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81cb369a-ffffffff81cb36d5: __audit_inode.cold (STB_LOCAL)
ffffffff811b7380-ffffffff811b76c3: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:2293
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81e64487-ffffffff81e644c2: __audit_inode.cold (STB_LOCAL)
ffffffff811ea0e0-ffffffff811ea4a5: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff812302c0)
Location: kernel/auditsc.c:2271
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812302c0-ffffffff812306bd: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81246db0)
Location: kernel/auditsc.c:2268
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81246db0-ffffffff81247221: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81260c60)
Location: kernel/auditsc.c:2263
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:open_last_lookups
  - fs/namei.c:__filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:pick_link
  - ipc/mqueue.c:__do_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81260c60-ffffffff8126109b: __audit_inode (STB_GLOBAL)
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
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2018)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffff8000101f2018-ffff8000101f23b0: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c04324ec)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
c04324ec-c04328dc: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c000000000266560)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
c000000000266560-c000000000266b68: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe00016580a)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_parentat
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - ipc/mqueue.c:__se_sys_mq_open
  - ipc/mqueue.c:__se_sys_mq_open
```
**Symbols:**

```
ffffffe00016580a-ffffffe000165ac6: __audit_inode (STB_GLOBAL)
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
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81176770-ffffffff811767ab: __audit_inode.cold (STB_LOCAL)
ffffffff811757d0-ffffffff81175af7: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81169910-ffffffff8116994b: __audit_inode.cold (STB_LOCAL)
ffffffff81168970-ffffffff81168c97: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81174540-ffffffff8117457b: __audit_inode.cold (STB_LOCAL)
ffffffff811735a0-ffffffff811738c7: __audit_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __audit_inode(struct filename *name, const struct dentry *dentry, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1944
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_file
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:filename_mountpoint
  - fs/namei.c:filename_lookup
  - fs/namei.c:trailing_symlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - ipc/mqueue.c:do_mq_open
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff81181e20-ffffffff81181e59: __audit_inode.cold (STB_LOCAL)
ffffffff81180e00-ffffffff81181184: __audit_inode (STB_GLOBAL)
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
