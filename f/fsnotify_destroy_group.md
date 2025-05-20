# Function: <code>fsnotify_destroy_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8124fdc0)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
```
**Symbols:**

```
ffffffff8124fdc0-ffffffff8124fe04: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81278510)
Location: fs/notify/group.c:60
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81278510-ffffffff8127856c: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8128c200)
Location: fs/notify/group.c:60
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8128c200-ffffffff8128c245: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81299190)
Location: fs/notify/group.c:60
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81299190-ffffffff81299257: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812bc550)
Location: fs/notify/group.c:60
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:SyS_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812bc550-ffffffff812bc620: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812e5170)
Location: fs/notify/group.c:60
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812e5170-ffffffff812e5255: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812f9cc0)
Location: fs/notify/group.c:63
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812f9cc0-ffffffff812f9d9e: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8131a380)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8131a380-ffffffff8131a469: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8132d1a0)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8132d1a0-ffffffff8132d289: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81366f60)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81366f60-ffffffff81367032: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff813742b0)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_new_group
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff813742b0-ffffffff81374382: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8137ac10)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8137ac10-ffffffff8137ace2: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff813c78f0)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff813c78f0-ffffffff813c79c2: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8144ed10)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8144ed10-ffffffff8144ee23: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff814dd4d0)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff814dd4d0-ffffffff814dd5e3: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81513d30)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81513d30-ffffffff81513e43: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81548200)
Location: fs/notify/group.c:50
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__do_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81548200-ffffffff81548313: fsnotify_destroy_group (STB_GLOBAL)
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
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffff8000103e9038)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__arm64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffff8000103e9038-ffff8000103e916c: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (c05c06f4)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
c05c06f4-c05c07d8: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (c0000000004efbe0)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
c0000000004efbe0-c0000000004efd24: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffe00029dae4)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffe00029dae4-ffffffe00029dbfa: fsnotify_destroy_group (STB_GLOBAL)
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
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81325780)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81325780-ffffffff81325869: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81316320)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81316320-ffffffff81316409: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81323250)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81323250-ffffffff81323339: fsnotify_destroy_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_destroy_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81334fa0)
Location: fs/notify/group.c:49
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:do_inotify_init
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/inotify/inotify_user.c:inotify_release
  - fs/notify/fanotify/fanotify_user.c:__ia32_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:__x64_sys_fanotify_init
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81334fa0-ffffffff81335082: fsnotify_destroy_group (STB_GLOBAL)
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
