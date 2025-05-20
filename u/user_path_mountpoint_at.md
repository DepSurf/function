# Function: <code>user_path_mountpoint_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121cde0)
Location: fs/namei.c:2508
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff8121cde0-ffffffff8121ce19: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81244390)
Location: fs/namei.c:2722
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81244390-ffffffff812443c9: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81257300)
Location: fs/namei.c:2686
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81257300-ffffffff81257339: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81263470)
Location: fs/namei.c:2731
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff81263470-ffffffff812634a9: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812859b0)
Location: fs/namei.c:2729
Inline: False
Direct callers:
  - fs/namespace.c:SyS_oldumount
```
**Symbols:**

```
ffffffff812859b0-ffffffff812859e9: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812acf90)
Location: fs/namei.c:2725
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812acf90-ffffffff812acfd1: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812c2090)
Location: fs/namei.c:2744
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812c2090-ffffffff812c20d1: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812de870)
Location: fs/namei.c:2742
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812de870-ffffffff812de8ad: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0380)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812f0380-ffffffff812f03bd: user_path_mountpoint_at (STB_GLOBAL)
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
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010399ad0)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffff800010399ad0-ffff800010399b2c: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0580040)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
c0580040-c0580088: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0000000004944d0)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
c0000000004944d0-c00000000049453c: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000267364)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffe000267364-ffffffe0002673b4: user_path_mountpoint_at (STB_GLOBAL)
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
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e8960)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812e8960-ffffffff812e899d: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d95a0)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812d95a0-ffffffff812d95dd: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6770)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812e6770-ffffffff812e67ad: user_path_mountpoint_at (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int user_path_mountpoint_at(int dfd, const char *name, unsigned int flags, struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f76f0)
Location: fs/namei.c:2735
Inline: False
Direct callers:
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812f76f0-ffffffff812f772d: user_path_mountpoint_at (STB_GLOBAL)
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
