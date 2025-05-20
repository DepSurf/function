# Function: <code>path_parent_directory</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123d7a0)
Location: fs/namei.c:1436
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123d7a0-ffffffff8123d7f2: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250540)
Location: fs/namei.c:1432
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81250540-ffffffff81250592: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125c790)
Location: fs/namei.c:1444
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125c790-ffffffff8125c7e7: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127ead0)
Location: fs/namei.c:1442
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8127ead0-ffffffff8127eb0b: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6110)
Location: fs/namei.c:1429
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812a6110-ffffffff812a6168: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb360)
Location: fs/namei.c:1470
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812bb360-ffffffff812bb3b8: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7fa0)
Location: fs/namei.c:1468
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d7fa0-ffffffff812d7ffb: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9b10)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e9b10-ffffffff812e9b6b: path_parent_directory (STB_LOCAL)
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
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393088)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffff800010393088-ffff80001039311c: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0579680)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
c0579680-c05796cc: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048c750)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
c00000000048c750-c00000000048c80c: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002620e4)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffe0002620e4-ffffffe000262150: path_parent_directory (STB_LOCAL)
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
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e20f0)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e20f0-ffffffff812e214b: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2d30)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d2d30-ffffffff812d2d8b: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dff00)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812dff00-ffffffff812dff5b: path_parent_directory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int path_parent_directory(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f16a0)
Location: fs/namei.c:1463
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_pts
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812f16a0-ffffffff812f16fb: path_parent_directory (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
