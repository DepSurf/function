# Function: <code>security_path_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81456ae0)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81456ae0-ffffffff81456b2c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a98f0)
Location: security/security.c:1133
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff814a98f0-ffffffff814a993c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c6ef0)
Location: security/security.c:1135
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff814c6ef0-ffffffff814c6f3c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd0b0)
Location: security/security.c:1180
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff814cd0b0-ffffffff814cd0fc: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526230)
Location: security/security.c:1180
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff81526230-ffffffff8152627c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba670)
Location: security/security.c:1184
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff815ba670-ffffffff815ba6db: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81666020)
Location: security/security.c:1182
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff81666020-ffffffff8166608b: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e610)
Location: security/security.c:1611
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff8169e610-ffffffff8169e67b: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816daf60)
Location: security/security.c:1664
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:fanotify_find_path
```
**Symbols:**

```
ffffffff816daf60-ffffffff816dafcb: security_path_notify (STB_GLOBAL)
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
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105424a0)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffff8000105424a0-ffff800010542504: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f8448)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
c06f8448-c06f84bc: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006957c0)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
c0000000006957c0-c000000000695890: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039ede2)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
ffffffe00039ede2-ffffffe00039ee2e: security_path_notify (STB_GLOBAL)
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
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144f0c0)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8144f0c0-ffffffff8144f10c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143fb10)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8143fb10-ffffffff8143fb5c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144b160)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8144b160-ffffffff8144b1ac: security_path_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_path_notify(const struct path *path, u64 mask, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81462530)
Location: security/security.c:985
Inline: False
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_find_inode
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81462530-ffffffff8146257c: security_path_notify (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
