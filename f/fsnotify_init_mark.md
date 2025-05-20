# Function: <code>fsnotify_init_mark</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, void (*free_mark)(struct fsnotify_mark *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250230)
Location: fs/notify/mark.c:490
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81250230-ffffffff81250271: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, void (*free_mark)(struct fsnotify_mark *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81278a30)
Location: fs/notify/mark.c:531
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff81278a30-ffffffff81278a71: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, void (*free_mark)(struct fsnotify_mark *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8128c660)
Location: fs/notify/mark.c:519
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff8128c660-ffffffff8128c6a1: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812994e0)
Location: fs/notify/mark.c:739
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812994e0-ffffffff81299539: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bc850)
Location: fs/notify/mark.c:738
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:SyS_inotify_add_watch
```
**Symbols:**

```
ffffffff812bc850-ffffffff812bc8a9: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e52c0)
Location: fs/notify/mark.c:744
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:alloc_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
```
**Symbols:**

```
ffffffff812e52c0-ffffffff812e531a: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812f9f30)
Location: fs/notify/mark.c:778
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff812f9f30-ffffffff812f9f8a: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131a5c0)
Location: fs/notify/mark.c:805
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8131a5c0-ffffffff8131a622: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d3e0)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8132d3e0-ffffffff8132d442: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367210)
Location: fs/notify/mark.c:810
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81367210-ffffffff8136726b: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374570)
Location: fs/notify/mark.c:810
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81374570-ffffffff813745cb: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137af20)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8137af20-ffffffff8137af7b: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7b80)
Location: fs/notify/mark.c:835
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff813c7b80-ffffffff813c7bdb: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f2b0)
Location: fs/notify/mark.c:872
Inline: True
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff8144f2b0-ffffffff8144f317: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814ddae0)
Location: fs/notify/mark.c:872
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff814ddae0-ffffffff814ddb47: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815142c0)
Location: fs/notify/mark.c:872
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff815142c0-ffffffff81514327: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81548790)
Location: fs/notify/mark.c:836
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:create_chunk
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_new_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_new_mark
```
**Symbols:**

```
ffffffff81548790-ffffffff815487f7: fsnotify_init_mark (STB_GLOBAL)
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
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9278)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__arm64_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffff8000103e9278-ffff8000103e92cc: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0b1c)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
c05c0b1c-c05c0b64: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f0580)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
c0000000004f0580-c0000000004f05fc: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029dd7e)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:__se_sys_inotify_add_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffe00029dd7e-ffffffe00029ddce: fsnotify_init_mark (STB_GLOBAL)
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
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813259c0)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff813259c0-ffffffff81325a22: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316560)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81316560-ffffffff813165c2: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323490)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81323490-ffffffff813234f2: fsnotify_init_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_init_mark(struct fsnotify_mark *mark, struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335320)
Location: fs/notify/mark.c:806
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_fsnotify.c:audit_alloc_mark
  - kernel/audit_tree.c:tag_mount
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/notify/inotify/inotify_user.c:inotify_update_watch
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
```
**Symbols:**

```
ffffffff81335320-ffffffff81335382: fsnotify_init_mark (STB_GLOBAL)
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
<code>struct fsnotify_group *group</code>
</li>
<li>
<b>Param removed. </b>
<code>void (*free_mark)(struct fsnotify_mark *)</code>
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
