# Function: <code>fanotify_remove_mark</code>

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
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fd900)
Location: fs/notify/fanotify/fanotify_user.c:526
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff812fd900-ffffffff812fd9f2: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e5b0)
Location: fs/notify/fanotify/fanotify_user.c:596
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8131e5b0-ffffffff8131e6ac: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813313f0)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813313f0-ffffffff813314ec: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136bc80)
Location: fs/notify/fanotify/fanotify_user.c:673
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8136bc80-ffffffff8136bd7d: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81379510)
Location: fs/notify/fanotify/fanotify_user.c:746
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81379510-ffffffff81379619: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81380080)
Location: fs/notify/fanotify/fanotify_user.c:839
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81380080-ffffffff81380185: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813ccff0)
Location: fs/notify/fanotify/fanotify_user.c:939
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813ccff0-ffffffff813cd0f5: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81456120)
Location: fs/notify/fanotify/fanotify_user.c:1030
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81456120-ffffffff81456314: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e50d0)
Location: fs/notify/fanotify/fanotify_user.c:1030
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff814e50d0-ffffffff814e52bf: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151b930)
Location: fs/notify/fanotify/fanotify_user.c:1079
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8151b930-ffffffff8151bb1f: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags, __u32 umask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ff30)
Location: fs/notify/fanotify/fanotify_user.c:1078
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8154ff30-ffffffff8155011f: fanotify_remove_mark (STB_LOCAL)
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
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee580)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffff8000103ee580-ffff8000103ee6cc: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c05c48bc)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
c05c48bc-c05c49c0: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c0000000004f6f20)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
c0000000004f6f20-c0000000004f70d4: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1cbe)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
**Symbols:**

```
ffffffe0002a1cbe-ffffffe0002a1df6: fanotify_remove_mark (STB_LOCAL)
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
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813299d0)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813299d0-ffffffff81329acc: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a570)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8131a570-ffffffff8131a66c: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813274a0)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813274a0-ffffffff8132759c: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fanotify_remove_mark(struct fsnotify_group *group, fsnotify_connp_t *connp, __u32 mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339110)
Location: fs/notify/fanotify/fanotify_user.c:604
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81339110-ffffffff8133921b: fanotify_remove_mark (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>__u32 umask</code>
</li>
</ul>
</details>
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
