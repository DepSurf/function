# Function: <code>may_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int may_open(struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81216fe0)
Location: fs/namei.c:2671
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81216fe0-ffffffff812170c7: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int may_open(struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123e1b0)
Location: fs/namei.c:2898
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8123e1b0-ffffffff8123e2b0: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250f90)
Location: fs/namei.c:2862
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81250f90-ffffffff81251090: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125ced0)
Location: fs/namei.c:2907
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8125ced0-ffffffff8125cfd0: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f2e0)
Location: fs/namei.c:2905
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8127f2e0-ffffffff8127f3e0: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812a8f90)
Location: fs/namei.c:2927
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812a8f90-ffffffff812a9080: may_open.isra.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812be830)
Location: fs/namei.c:2946
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812be830-ffffffff812be920: may_open.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812db460)
Location: fs/namei.c:2944
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812db460-ffffffff812db540: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812ecf70)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812ecf70-ffffffff812ed050: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813237f0)
Location: fs/namei.c:2839
Inline: False
Direct callers:
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff813237f0-ffffffff813238e0: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132ed90)
Location: fs/namei.c:2837
Inline: False
Direct callers:
  - fs/namei.c:do_tmpfile
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8132ed90-ffffffff8132eedd: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_open(struct user_namespace *mnt_userns, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81336570)
Location: fs/namei.c:2946
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81336570-ffffffff813366d9: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_open(struct user_namespace *mnt_userns, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81383f50)
Location: fs/namei.c:3015
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81383f50-ffffffff813840b9: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_open(struct user_namespace *mnt_userns, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402c50)
Location: fs/namei.c:3111
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_open
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff81402c50-ffffffff81402dec: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_open(struct user_namespace *mnt_userns, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148cdf0)
Location: fs/namei.c:3149
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff8148cdf0-ffffffff8148cf8c: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_open(struct mnt_idmap *idmap, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c0c70)
Location: fs/namei.c:3228
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff814c0c70-ffffffff814c0dca: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_open(struct mnt_idmap *idmap, const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3130)
Location: fs/namei.c:3236
Inline: False
Direct callers:
  - fs/namei.c:vfs_tmpfile
  - fs/namei.c:do_open
  - fs/namei.c:do_open
```
**Symbols:**

```
ffffffff814f3130-ffffffff814f328a: may_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffff800010396778)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffff800010396778-ffff800010396894: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int may_open(const struct path *path, int acc_mode, int flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579ea8)
Location: fs/namei.c:2937
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
c0579ea8-c0579fbc: may_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (c00000000048c520)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
c00000000048c520-c00000000048c6cc: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffe000264b9c)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffe000264b9c-ffffffe000264c96: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e5550)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812e5550-ffffffff812e5630: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812d6190)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812d6190-ffffffff812d6270: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e3360)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812e3360-ffffffff812e3440: may_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812f1580)
Location: fs/namei.c:2937
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_last
  - fs/namei.c:lookup_open
```
**Symbols:**

```
ffffffff812f1580-ffffffff812f1660: may_open.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>path, acc_mode, flag</code> ➡️ <code>mnt_userns, path, acc_mode, flag</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
