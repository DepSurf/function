# Function: <code>fanotify_find_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812536e0)
Location: fs/notify/fanotify/fanotify_user.c:439
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812536e0-ffffffff81253828: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8127bce0)
Location: fs/notify/fanotify/fanotify_user.c:452
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8127bce0-ffffffff8127be21: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8128f890)
Location: fs/notify/fanotify/fanotify_user.c:452
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8128f890-ffffffff8128f9d1: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8129c870)
Location: fs/notify/fanotify/fanotify_user.c:458
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff8129c870-ffffffff8129c9b4: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812bfce0)
Location: fs/notify/fanotify/fanotify_user.c:453
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:compat_SyS_fanotify_mark
```
**Symbols:**

```
ffffffff812bfce0-ffffffff812bfe24: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812e88f3)
Location: fs/notify/fanotify/fanotify_user.c:453
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff812fdce2)
Location: fs/notify/fanotify/fanotify_user.c:460
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e8ca)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813316d7)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8136af20)
Location: fs/notify/fanotify/fanotify_user.c:599
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8136af20-ffffffff8136b0a2: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813787b0)
Location: fs/notify/fanotify/fanotify_user.c:665
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813787b0-ffffffff81378932: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8137f760)
Location: fs/notify/fanotify/fanotify_user.c:758
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8137f760-ffffffff8137f8e8: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff813cc720)
Location: fs/notify/fanotify/fanotify_user.c:858
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff813cc720-ffffffff813cc8a5: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81454ef0)
Location: fs/notify/fanotify/fanotify_user.c:948
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff81454ef0-ffffffff814550a7: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff814e3e40)
Location: fs/notify/fanotify/fanotify_user.c:948
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff814e3e40-ffffffff814e3ff2: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8151a830)
Location: fs/notify/fanotify/fanotify_user.c:997
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8151a830-ffffffff8151a9e4: fanotify_find_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fanotify_find_path(int dfd, const char *filename, struct path *path, unsigned int flags, __u64 mask, unsigned int obj_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8154ee30)
Location: fs/notify/fanotify/fanotify_user.c:996
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
**Symbols:**

```
ffffffff8154ee30-ffffffff8154efe4: fanotify_find_path (STB_LOCAL)
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
In fs/notify/fanotify/fanotify_user.c (ffff8000103eea9c)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (c05c5b00)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (c0000000004f7394)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a29b6)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:__se_sys_fanotify_mark
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329cb7)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131a857)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81327787)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81339ba7)
Location: fs/notify/fanotify/fanotify_user.c:530
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:do_fanotify_mark
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
