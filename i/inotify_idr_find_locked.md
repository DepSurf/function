# Function: <code>inotify_idr_find_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81252080)
Location: fs/notify/inotify/inotify_user.c:366
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
```
**Symbols:**

```
ffffffff81252080-ffffffff812520e4: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127a840)
Location: fs/notify/inotify/inotify_user.c:366
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8127a840-ffffffff8127a8a4: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e3f0)
Location: fs/notify/inotify/inotify_user.c:366
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8128e3f0-ffffffff8128e454: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b2e0)
Location: fs/notify/inotify/inotify_user.c:364
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8129b2e0-ffffffff8129b329: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812be6f0)
Location: fs/notify/inotify/inotify_user.c:364
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff812be6f0-ffffffff812be739: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812e6fe0)
Location: fs/notify/inotify/inotify_user.c:378
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff812e6fe0-ffffffff812e7025: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812fbbd0)
Location: fs/notify/inotify/inotify_user.c:379
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff812fbbd0-ffffffff812fbc15: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8131c530)
Location: fs/notify/inotify/inotify_user.c:368
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8131c530-ffffffff8131c57c: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8132f320)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8132f320-ffffffff8132f36c: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81368f60)
Location: fs/notify/inotify/inotify_user.c:377
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff81368f60-ffffffff81368fae: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376240)
Location: fs/notify/inotify/inotify_user.c:388
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff81376240-ffffffff8137628e: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8137cbe0)
Location: fs/notify/inotify/inotify_user.c:387
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff8137cbe0-ffffffff8137cc2e: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813ca404)
Location: fs/notify/inotify/inotify_user.c:392
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814519c5)
Location: fs/notify/inotify/inotify_user.c:415
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814e0705)
Location: fs/notify/inotify/inotify_user.c:415
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81516fb5)
Location: fs/notify/inotify/inotify_user.c:415
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8154b3a5)
Location: fs/notify/inotify/inotify_user.c:414
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
  - fs/notify/inotify/inotify_user.c:inotify_idr_find
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
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffff8000103ebe78)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffff8000103ebe78-ffff8000103ebed8: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c05c2ee8)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
c05c2ee8-c05c2f40: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c0000000004f3210)
Location: fs/notify/inotify/inotify_user.c:377
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
c0000000004f3210-c0000000004f3290: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0042)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffe0002a0042-ffffffe0002a009a: inotify_idr_find_locked (STB_LOCAL)
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
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81327900)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff81327900-ffffffff8132794c: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813184a0)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff813184a0-ffffffff813184ec: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813253d0)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff813253d0-ffffffff8132541c: inotify_idr_find_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct inotify_inode_mark *inotify_idr_find_locked(struct fsnotify_group *group, int wd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81337770)
Location: fs/notify/inotify/inotify_user.c:377
Inline: True
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_rm_watch
  - fs/notify/inotify/inotify_user.c:inotify_remove_from_idr
```
**Symbols:**

```
ffffffff81337770-ffffffff813377bc: inotify_idr_find_locked (STB_LOCAL)
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
