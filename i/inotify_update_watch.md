# Function: <code>inotify_update_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812524fa)
Location: fs/notify/inotify/inotify_user.c:617
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127acbd)
Location: fs/notify/inotify/inotify_user.c:617
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e86d)
Location: fs/notify/inotify/inotify_user.c:617
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b6f1)
Location: fs/notify/inotify/inotify_user.c:585
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812beb01)
Location: fs/notify/inotify/inotify_user.c:585
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812e7380)
Location: fs/notify/inotify/inotify_user.c:603
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff812e7380-ffffffff812e7566: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812fc340)
Location: fs/notify/inotify/inotify_user.c:610
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff812fc340-ffffffff812fc561: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8131ccd0)
Location: fs/notify/inotify/inotify_user.c:599
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8131ccd0-ffffffff8131ceec: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8132fb10)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8132fb10-ffffffff8132fd2c: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81369bb0)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81369bb0-ffffffff81369cc0: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376eb0)
Location: fs/notify/inotify/inotify_user.c:615
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81376eb0-ffffffff81376fdd: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8137d770)
Location: fs/notify/inotify/inotify_user.c:614
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8137d770-ffffffff8137d9d1: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813ca6b0)
Location: fs/notify/inotify/inotify_user.c:619
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff813ca6b0-ffffffff813ca911: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81451d70)
Location: fs/notify/inotify/inotify_user.c:639
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81451d70-ffffffff81451f34: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814e0af0)
Location: fs/notify/inotify/inotify_user.c:639
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff814e0af0-ffffffff814e0cb4: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff815173a0)
Location: fs/notify/inotify/inotify_user.c:639
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff815173a0-ffffffff81517564: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8154b780)
Location: fs/notify/inotify/inotify_user.c:638
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8154b780-ffffffff8154b944: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffff8000103ece90)
Location: fs/notify/inotify/inotify_user.c:608
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c05c3830)
Location: fs/notify/inotify/inotify_user.c:608
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (c0000000004f3ea0)
Location: fs/notify/inotify/inotify_user.c:608
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffe0002a0a2a)
Location: fs/notify/inotify/inotify_user.c:608
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
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
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813280f0)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff813280f0-ffffffff8132830c: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81318c90)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81318c90-ffffffff81318eac: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81325bc0)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81325bc0-ffffffff81325ddc: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inotify_update_watch(struct fsnotify_group *group, struct inode *inode, u32 arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81337a10)
Location: fs/notify/inotify/inotify_user.c:608
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81337a10-ffffffff81337c47: inotify_update_watch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
