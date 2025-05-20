# Function: <code>__kernfs_new_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81289740)
Location: fs/kernfs/dir.c:659
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_new_node
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff81289740-ffffffff812897f6: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812b6c00)
Location: fs/kernfs/dir.c:658
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff812b6c00-ffffffff812b6cb6: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812cc390)
Location: fs/kernfs/dir.c:608
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff812cc390-ffffffff812cc446: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812d99e0)
Location: fs/kernfs/dir.c:618
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff812d99e0-ffffffff812d9a96: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff812fe280)
Location: fs/kernfs/dir.c:620
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff812fe280-ffffffff812fe395: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8132c260)
Location: fs/kernfs/dir.c:620
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8132c260-ffffffff8132c427: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81343c50)
Location: fs/kernfs/dir.c:620
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff81343c50-ffffffff81343e17: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136bec0)
Location: fs/kernfs/dir.c:616
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8136bec0-ffffffff8136c089: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81384090)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff81384090-ffffffff81384240: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813ce330)
Location: fs/kernfs/dir.c:613
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff813ce330-ffffffff813ce4e4: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813dff60)
Location: fs/kernfs/dir.c:612
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff813dff60-ffffffff813e0114: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff813e6b10)
Location: fs/kernfs/dir.c:612
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff813e6b10-ffffffff813e6cc4: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814386b0)
Location: fs/kernfs/dir.c:571
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff814386b0-ffffffff81438864: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff814b31b0)
Location: fs/kernfs/dir.c:579
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff814b31b0-ffffffff814b33b1: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81549e20)
Location: fs/kernfs/dir.c:600
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff81549e20-ffffffff8154a021: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81581a40)
Location: fs/kernfs/dir.c:597
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_empty_dir
  - fs/kernfs/dir.c:kernfs_create_dir_ns
  - fs/kernfs/dir.c:kernfs_create_root
```
**Symbols:**

```
ffffffff81581a40-ffffffff81581c59: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815ba4e0)
Location: fs/kernfs/dir.c:601
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff815ba4e0-ffffffff815ba6f9: __kernfs_new_node (STB_LOCAL)
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
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffff800010452640)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffff800010452640-ffff800010452870: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c0614ba8)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
c0614ba8-c0614d7c: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (c00000000056a720)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
c00000000056a720-c00000000056a9d0: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffe0002e5176)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffe0002e5176-ffffffe0002e5356: __kernfs_new_node (STB_LOCAL)
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
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137c670)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8137c670-ffffffff8137c820: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8136d140)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8136d140-ffffffff8136d2f0: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8137a140)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8137a140-ffffffff8137a2f0: __kernfs_new_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct kernfs_node *__kernfs_new_node(struct kernfs_root *root, struct kernfs_node *parent, const char *name, umode_t mode, kuid_t uid, kgid_t gid, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8138d1b0)
Location: fs/kernfs/dir.c:617
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_new_node
```
**Symbols:**

```
ffffffff8138d1b0-ffffffff8138d38b: __kernfs_new_node (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>kuid_t uid</code>
</li>
<li>
<b>Param added. </b>
<code>kgid_t gid</code>
</li>
<li>
<b>Param reordered. </b>
<code>root, name, mode, flags</code> ➡️ <code>root, name, mode, uid, gid, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kernfs_node *parent</code>
</li>
<li>
<b>Param reordered. </b>
<code>root, name, mode, uid, gid, flags</code> ➡️ <code>root, parent, name, mode, uid, gid, flags</code>
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
