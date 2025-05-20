# Function: <code>__mnt_is_readonly</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8122bd60)
Location: fs/namespace.c:274
Inline: True
Inline callers:
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:do_mount
Direct callers:
  - fs/open.c:SyS_access
  - fs/namespace.c:__mnt_want_write
  - fs/namespace.c:do_mount
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8122bd60-ffffffff8122bd76: __mnt_is_readonly.part.8 (STB_LOCAL)
ffffffff8122bd80-ffffffff8122bd9c: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812577a7)
Location: fs/namespace.c:274
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:SyS_access
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812544c0-ffffffff812544d6: __mnt_is_readonly.part.8 (STB_LOCAL)
ffffffff812544e0-ffffffff812544fc: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8126ac37)
Location: fs/namespace.c:273
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:SyS_access
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81267a00-ffffffff81267a16: __mnt_is_readonly.part.10 (STB_LOCAL)
ffffffff81267a20-ffffffff81267a3c: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812783db)
Location: fs/namespace.c:274
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:SyS_access
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812750b0-ffffffff812750c6: __mnt_is_readonly.part.10 (STB_LOCAL)
ffffffff812750d0-ffffffff812750ec: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff8129ae11)
Location: fs/namespace.c:274
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:SyS_access
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81297970-ffffffff81297986: __mnt_is_readonly.part.13 (STB_LOCAL)
ffffffff81297990-ffffffff812979ac: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c0f00)
Location: fs/namespace.c:274
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812bdc40-ffffffff812bdc61: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d61df)
Location: fs/namespace.c:249
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812d2590-ffffffff812d25b1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f4965)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812ef5e0-ffffffff812ef601: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81306507)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff813010b0-ffffffff813010d1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133c074)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8133a320-ffffffff8133a341: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347f14)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_reconfigure_mnt
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81346010-ffffffff81346031: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81352903)
Location: fs/namespace.c:267
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8134c3d0-ffffffff8134c3f1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a0d14)
Location: fs/namespace.c:268
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8139a220-ffffffff8139a241: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814246e1)
Location: fs/namespace.c:269
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff8141cdb0-ffffffff8141cdd7: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b0e49)
Location: fs/namespace.c:384
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff814a9050-ffffffff814a9077: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e5e89)
Location: fs/namespace.c:270
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff814ddf90-ffffffff814ddfb7: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81519cb9)
Location: fs/namespace.c:275
Inline: True
Inline callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_get_write_access
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff815109e0-ffffffff81510a07: __mnt_is_readonly (STB_GLOBAL)
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
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b9aa4)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffff8000103b3968-ffff8000103b39b0: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05975dc)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
c0592494-c05924c4: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b70d0)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
c0000000004af5d0-c0000000004af608: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027bd6a)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffe000276fe4-ffffffe000277014: __mnt_is_readonly (STB_GLOBAL)
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
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812feae7)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812f9690-ffffffff812f96b1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef707)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812ea2b0-ffffffff812ea2d1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc8d7)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff812f7480-ffffffff812f74a1: __mnt_is_readonly (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool __mnt_is_readonly(struct vfsmount *mnt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130dc37)
Location: fs/namespace.c:246
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:mnt_warn_timestamp_expiry
  - fs/namespace.c:mnt_clone_write
  - fs/namespace.c:__mnt_want_write
Direct callers:
  - fs/open.c:do_faccessat
  - fs/proc_namespace.c:show_vfsmnt
```
**Symbols:**

```
ffffffff81308710-ffffffff81308731: __mnt_is_readonly (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
