# Function: <code>audit_compare_dname_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81125680)
Location: kernel/auditfilter.c:1274
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81125680-ffffffff8112570c: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d640)
Location: kernel/auditfilter.c:1274
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8112d640-ffffffff8112d6cb: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137370)
Location: kernel/auditfilter.c:1275
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81137370-ffffffff811373fb: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811388d0)
Location: kernel/auditfilter.c:1273
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811388d0-ffffffff8113895b: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811455d0)
Location: kernel/auditfilter.c:1298
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811455d0-ffffffff8114565b: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153f70)
Location: kernel/auditfilter.c:1295
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81153f70-ffffffff81153fee: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int audit_compare_dname_path(const char *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81160d30)
Location: kernel/auditfilter.c:1293
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81160d30-ffffffff81160dae: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116d3d0)
Location: kernel/auditfilter.c:1296
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8116d3d0-ffffffff8116d446: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81179270)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81179270-ffffffff811792e6: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118c2c0)
Location: kernel/auditfilter.c:1302
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8118c2c0-ffffffff8118c33b: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811894e0)
Location: kernel/auditfilter.c:1302
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811894e0-ffffffff8118955b: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8118a350)
Location: kernel/auditfilter.c:1302
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8118a350-ffffffff8118a3cb: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811b2e10)
Location: kernel/auditfilter.c:1302
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811b2e10-ffffffff811b2e8b: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811e5250)
Location: kernel/auditfilter.c:1310
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811e5250-ffffffff811e52df: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8122b2c0)
Location: kernel/auditfilter.c:1310
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8122b2c0-ffffffff8122b34f: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81241890)
Location: kernel/auditfilter.c:1310
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81241890-ffffffff8124191f: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8125b6c0)
Location: kernel/auditfilter.c:1311
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8125b6c0-ffffffff8125b74f: audit_compare_dname_path (STB_GLOBAL)
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
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffff8000101ee568)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffff8000101ee568-ffff8000101ee60c: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c042e5b8)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
c042e5b8-c042e630: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (c0000000002611d0)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
c0000000002611d0-c0000000002612c0: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffe0001626d2)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffe0001626d2-ffffffe00016275a: audit_compare_dname_path (STB_GLOBAL)
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
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81171890)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81171890-ffffffff81171906: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81164a30)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81164a30-ffffffff81164aa6: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8116f660)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8116f660-ffffffff8116f6d6: audit_compare_dname_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int audit_compare_dname_path(const struct qstr *dname, const char *path, int parentlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8117ce50)
Location: kernel/auditfilter.c:1303
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode_child
  - kernel/auditsc.c:__audit_inode_child
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8117ce50-ffffffff8117cec6: audit_compare_dname_path (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>const char *dname</code> ➡️ <code>const struct qstr *dname</code>
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
