# Function: <code>inotify_find_inode</code>

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
In fs/notify/inotify/inotify_user.c (ffffffff8125246d)
Location: fs/notify/inotify/inotify_user.c:332
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
In fs/notify/inotify/inotify_user.c (ffffffff8127ac2d)
Location: fs/notify/inotify/inotify_user.c:332
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
In fs/notify/inotify/inotify_user.c (ffffffff8128e7dd)
Location: fs/notify/inotify/inotify_user.c:332
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
In fs/notify/inotify/inotify_user.c (ffffffff8129b65d)
Location: fs/notify/inotify/inotify_user.c:330
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
In fs/notify/inotify/inotify_user.c (ffffffff812bea6d)
Location: fs/notify/inotify/inotify_user.c:330
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
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812e6f80)
Location: fs/notify/inotify/inotify_user.c:344
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff812e6f80-ffffffff812e6fda: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812fbb70)
Location: fs/notify/inotify/inotify_user.c:345
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff812fbb70-ffffffff812fbbca: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8131c4d0)
Location: fs/notify/inotify/inotify_user.c:334
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8131c4d0-ffffffff8131c52e: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8132f2a0)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8132f2a0-ffffffff8132f318: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81369420)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81369420-ffffffff81369498: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376700)
Location: fs/notify/inotify/inotify_user.c:346
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81376700-ffffffff81376778: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8137cff0)
Location: fs/notify/inotify/inotify_user.c:345
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8137cff0-ffffffff8137d070: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813c9ea0)
Location: fs/notify/inotify/inotify_user.c:350
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff813c9ea0-ffffffff813c9f20: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81451f40)
Location: fs/notify/inotify/inotify_user.c:373
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81451f40-ffffffff81451fd9: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff814e0cd0)
Location: fs/notify/inotify/inotify_user.c:373
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff814e0cd0-ffffffff814e0d76: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81517580)
Location: fs/notify/inotify/inotify_user.c:373
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81517580-ffffffff81517619: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8154b960)
Location: fs/notify/inotify/inotify_user.c:372
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff8154b960-ffffffff8154b9f9: inotify_find_inode (STB_LOCAL)
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
In fs/notify/inotify/inotify_user.c (ffff8000103ecdf8)
Location: fs/notify/inotify/inotify_user.c:335
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
In fs/notify/inotify/inotify_user.c (c05c3790)
Location: fs/notify/inotify/inotify_user.c:335
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
In fs/notify/inotify/inotify_user.c (c0000000004f3db4)
Location: fs/notify/inotify/inotify_user.c:335
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
In fs/notify/inotify/inotify_user.c (ffffffe0002a09b8)
Location: fs/notify/inotify/inotify_user.c:335
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
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81327880)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81327880-ffffffff813278f8: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81318420)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81318420-ffffffff81318498: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81325350)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff81325350-ffffffff813253c8: inotify_find_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int inotify_find_inode(const char *dirname, struct path *path, unsigned int flags, __u64 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff813376f0)
Location: fs/notify/inotify/inotify_user.c:335
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__ia32_sys_inotify_add_watch
  - fs/notify/inotify/inotify_user.c:__x64_sys_inotify_add_watch
```
**Symbols:**

```
ffffffff813376f0-ffffffff81337768: inotify_find_inode (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u64 mask</code>
</li>
</ul>
</details>
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
