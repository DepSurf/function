# Function: <code>filename_mountpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121c440)
Location: fs/namei.c:2473
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff8121c440-ffffffff8121c588: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812438c0)
Location: fs/namei.c:2687
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812438c0-ffffffff81243a08: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81256840)
Location: fs/namei.c:2651
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff81256840-ffffffff81256988: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812629e0)
Location: fs/namei.c:2696
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812629e0-ffffffff81262b2d: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81285230)
Location: fs/namei.c:2694
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff81285230-ffffffff8128537d: filename_mountpoint (STB_LOCAL)
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
In fs/namei.c (ffffffff812ac4be)
Location: fs/namei.c:2690
Inline: True
Inline callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812ac370-ffffffff812ac4a0: filename_mountpoint.part.60 (STB_LOCAL)
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
In fs/namei.c (ffffffff812c15be)
Location: fs/namei.c:2709
Inline: True
Inline callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812c1470-ffffffff812c15a0: filename_mountpoint.part.61 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dd9e0)
Location: fs/namei.c:2707
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812dd9e0-ffffffff812ddb37: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ef510)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812ef510-ffffffff812ef655: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010398ca8)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffff800010398ca8-ffff800010398de8: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057f354)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
c057f354-c057f4a4: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000493250)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
c000000000493250-c000000000493404: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026684c)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffe00026684c-ffffffe000266930: filename_mountpoint (STB_LOCAL)
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
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7af0)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812e7af0-ffffffff812e7c35: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8730)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812d8730-ffffffff812d8875: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5900)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812e5900-ffffffff812e5a45: filename_mountpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filename_mountpoint(int dfd, struct filename *name, struct path *path, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f6880)
Location: fs/namei.c:2700
Inline: False
Direct callers:
  - fs/namei.c:kern_path_mountpoint
  - fs/namei.c:user_path_mountpoint_at
```
**Symbols:**

```
ffffffff812f6880-ffffffff812f69c5: filename_mountpoint (STB_LOCAL)
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
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
