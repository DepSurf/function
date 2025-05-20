# Function: <code>unhash_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122bed0)
Location: fs/namespace.c:813
Inline: False
Direct callers:
  - fs/namespace.c:umount_tree
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8122bed0-ffffffff8122bf79: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254640)
Location: fs/namespace.c:813
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff81254640-ffffffff812546e9: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267b80)
Location: fs/namespace.c:814
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff81267b80-ffffffff81267c29: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812751b0)
Location: fs/namespace.c:815
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff812751b0-ffffffff81275259: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297a70)
Location: fs/namespace.c:882
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff81297a70-ffffffff81297b19: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812be0c0)
Location: fs/namespace.c:892
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff812be0c0-ffffffff812be163: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d33d0)
Location: fs/namespace.c:804
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
```
**Symbols:**

```
ffffffff812d33d0-ffffffff812d3473: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ef6e0)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812ef6e0-ffffffff812ef779: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813011b0)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff813011b0-ffffffff81301249: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134095e)
Location: fs/namespace.c:828
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8133a420-ffffffff8133a4b9: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c9ee)
Location: fs/namespace.c:828
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81346110-ffffffff813461a9: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813535bd)
Location: fs/namespace.c:835
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8134c450-ffffffff8134c4e9: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a1a0d)
Location: fs/namespace.c:844
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8139a2a0-ffffffff8139a339: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81425419)
Location: fs/namespace.c:880
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff8141cde0-ffffffff8141ce83: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b1b99)
Location: fs/namespace.c:991
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff814a9090-ffffffff814a9133: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e6be8)
Location: fs/namespace.c:900
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff814ddfd0-ffffffff814de073: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151aa28)
Location: fs/namespace.c:888
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff81510a20-ffffffff81510ac3: unhash_mnt (STB_LOCAL)
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
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b3a68)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffff8000103b3a68-ffff8000103b3aec: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592614)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:umount_mnt
```
**Symbols:**

```
c0592614-c05926b0: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004af6c0)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:mntput_no_expire
  - fs/namespace.c:umount_mnt
```
**Symbols:**

```
c0000000004af6c0-c0000000004af758: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277154)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffe000277154-ffffffe0002771b4: unhash_mnt (STB_LOCAL)
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
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9790)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812f9790-ffffffff812f9829: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea3b0)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812ea3b0-ffffffff812ea449: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7580)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff812f7580-ffffffff812f7619: unhash_mnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mountpoint *unhash_mnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813087c0)
Location: fs/namespace.c:812
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:__detach_mounts
  - fs/namespace.c:umount_tree
  - fs/namespace.c:mntput_no_expire
```
**Symbols:**

```
ffffffff813087c0-ffffffff81308859: unhash_mnt (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct mountpoint *</code>
</li>
</ul>
</details>
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
