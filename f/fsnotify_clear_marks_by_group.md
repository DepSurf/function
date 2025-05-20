# Function: <code>fsnotify_clear_marks_by_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81250b80)
Location: fs/notify/mark.c:470
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
```
**Symbols:**

```
ffffffff81250b80-ffffffff81250b95: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299ed0)
Location: fs/notify/mark.c:654
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff81299ed0-ffffffff81299ff8: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bd2a0)
Location: fs/notify/mark.c:653
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812bd2a0-ffffffff812bd3c8: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5ec0)
Location: fs/notify/mark.c:659
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812e5ec0-ffffffff812e5fe4: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812faaa0)
Location: fs/notify/mark.c:692
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812faaa0-ffffffff812fabc4: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131b2d0)
Location: fs/notify/mark.c:719
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8131b2d0-ffffffff8131b403: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132e0e0)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8132e0e0-ffffffff8132e213: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367f80)
Location: fs/notify/mark.c:724
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81367f80-ffffffff813680b3: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813752f0)
Location: fs/notify/mark.c:724
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813752f0-ffffffff81375423: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137bc90)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8137bc90-ffffffff8137bdc3: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (0)
Location: fs/notify/mark.c:749
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81cc54db-ffffffff81cc5506: fsnotify_clear_marks_by_group.cold (STB_LOCAL)
ffffffff813c8a90-ffffffff813c8bdc: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81450190)
Location: fs/notify/mark.c:786
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81450190-ffffffff8145038d: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814deb40)
Location: fs/notify/mark.c:786
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff814deb40-ffffffff814ded3d: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81515380)
Location: fs/notify/mark.c:786
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81515380-ffffffff81515590: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int obj_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81549740)
Location: fs/notify/mark.c:750
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81549740-ffffffff81549950: fsnotify_clear_marks_by_group (STB_GLOBAL)
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
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103ea710)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffff8000103ea710-ffff8000103ea85c: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c1ad0)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
c05c1ad0-c05c1c10: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f18f0)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
c0000000004f18f0-c0000000004f1ac4: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029eeca)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
ffffffe00029eeca-ffffffe00029efd0: fsnotify_clear_marks_by_group (STB_GLOBAL)
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
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813266c0)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813266c0-ffffffff813267f3: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81317260)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81317260-ffffffff81317393: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81324190)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81324190-ffffffff813242c3: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsnotify_clear_marks_by_group(struct fsnotify_group *group, unsigned int type_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335ee0)
Location: fs/notify/mark.c:720
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81335ee0-ffffffff81336013: fsnotify_clear_marks_by_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int type_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type_mask</code>
</li>
</ul>
</details>
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
