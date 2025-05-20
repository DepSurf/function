# Function: <code>follow_managed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81217170)
Location: fs/namei.c:1163
Inline: False
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namei.c:walk_component
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81217170-ffffffff8121744f: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123e350)
Location: fs/namei.c:1185
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8123e350-ffffffff8123e690: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251130)
Location: fs/namei.c:1182
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81251130-ffffffff81251458: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125d5b0)
Location: fs/namei.c:1194
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8125d5b0-ffffffff8125d8cb: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127f940)
Location: fs/namei.c:1192
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8127f940-ffffffff8127fc47: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a5bb0)
Location: fs/namei.c:1179
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812a5bb0-ffffffff812a5ec5: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bad20)
Location: fs/namei.c:1220
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812bad20-ffffffff812bb032: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7790)
Location: fs/namei.c:1218
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d7790-ffffffff812d7a8b: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e92f0)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e92f0-ffffffff812e95eb: follow_managed (STB_LOCAL)
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
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010392710)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffff800010392710-ffff8000103929ec: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0578e88)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c0578e88-c0579170: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048b820)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
c00000000048b820-c00000000048bc44: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002618f4)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffe0002618f4-ffffffe000261b76: follow_managed (STB_LOCAL)
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
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e18d0)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812e18d0-ffffffff812e1bcb: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2510)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812d2510-ffffffff812d280b: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812df6e0)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812df6e0-ffffffff812df9db: follow_managed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_managed(struct path *path, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0d90)
Location: fs/namei.c:1213
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:walk_component
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff812f0d90-ffffffff812f108b: follow_managed (STB_LOCAL)
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
