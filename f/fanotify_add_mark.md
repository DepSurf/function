# Function: <code>fanotify_add_mark</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fda00)
Location: fs/notify/fanotify/fanotify_user.c:624
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812fda00-ffffffff812fdb45: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e450)
Location: fs/notify/fanotify/fanotify_user.c:695
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8131e450-ffffffff8131e5a6: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81331290)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81331290-ffffffff813313e6: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136be90)
Location: fs/notify/fanotify/fanotify_user.c:772
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8136be90-ffffffff8136bfe6: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379730)
Location: fs/notify/fanotify/fanotify_user.c:846
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81379730-ffffffff81379886: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813802a0)
Location: fs/notify/fanotify/fanotify_user.c:953
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813802a0-ffffffff81380439: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cd100)
Location: fs/notify/fanotify/fanotify_user.c:1053
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813cd100-ffffffff813cd299: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int obj_type, __u32 mask, unsigned int fan_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456520)
Location: fs/notify/fanotify/fanotify_user.c:1190
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81456520-ffffffff81456880: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int obj_type, __u32 mask, unsigned int fan_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e54e0)
Location: fs/notify/fanotify/fanotify_user.c:1230
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff814e54e0-ffffffff814e58e9: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int obj_type, __u32 mask, unsigned int fan_flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151bfa0)
Location: fs/notify/fanotify/fanotify_user.c:1279
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8151bfa0-ffffffff8151c3ce: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int obj_type, __u32 mask, unsigned int fan_flags, struct fan_fsid *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff815505a0)
Location: fs/notify/fanotify/fanotify_user.c:1346
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff815505a0-ffffffff81550900: fanotify_add_mark (STB_LOCAL)
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
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee6d0)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffff8000103ee6d0-ffff8000103ee8a8: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c05c4744)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
c05c4744-c05c48bc: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c0000000004f6ce0)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
c0000000004f6ce0-c0000000004f6f1c: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1b2a)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
ffffffe0002a1b2a-ffffffe0002a1cbe: fanotify_add_mark (STB_LOCAL)
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
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329870)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81329870-ffffffff813299c6: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a410)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8131a410-ffffffff8131a566: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81327340)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81327340-ffffffff81327496: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fanotify_add_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, unsigned int type, __u32 mask, unsigned int flags, __kernel_fsid_t *fsid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81338fb0)
Location: fs/notify/fanotify/fanotify_user.c:703
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81338fb0-ffffffff81339110: fanotify_add_mark (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__kernel_fsid_t *fsid</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int obj_type</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int fan_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int type</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>__kernel_fsid_t *fsid</code> ➡️ <code>struct fan_fsid *fsid</code>
</li>
</ul>
</details>
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
