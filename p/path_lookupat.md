# Function: <code>path_lookupat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121a5c0)
Location: fs/namei.c:2123
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8121a5c0-ffffffff8121a6c5: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81240cc0)
Location: fs/namei.c:2260
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff81240cc0-ffffffff81240dd8: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812531a0)
Location: fs/namei.c:2249
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812531a0-ffffffff81253293: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125f2e0)
Location: fs/namei.c:2285
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8125f2e0-ffffffff8125f4c9: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81281650)
Location: fs/namei.c:2283
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff81281650-ffffffff81281839: path_lookupat (STB_LOCAL)
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
In fs/namei.c (ffffffff812a8320)
Location: fs/namei.c:2270
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812a8320-ffffffff812a851e: path_lookupat.isra.45 (STB_LOCAL)
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
In fs/namei.c (ffffffff812bd3b0)
Location: fs/namei.c:2306
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812bd3b0-ffffffff812bd5c2: path_lookupat.isra.46 (STB_LOCAL)
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
In fs/namei.c (ffffffff812d9ed0)
Location: fs/namei.c:2304
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812d9ed0-ffffffff812da0f2: path_lookupat.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812eb9e0)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812eb9e0-ffffffff812ebc02: path_lookupat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324720)
Location: fs/namei.c:2321
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff81324720-ffffffff813248d1: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132ff20)
Location: fs/namei.c:2319
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:do_tmpfile
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff8132ff20-ffffffff813300c8: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813351b0)
Location: fs/namei.c:2409
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff813351b0-ffffffff81335362: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81382ee0)
Location: fs/namei.c:2437
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff81382ee0-ffffffff8138308f: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81406430)
Location: fs/namei.c:2483
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff81406430-ffffffff814065ce: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814907a0)
Location: fs/namei.c:2462
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff814907a0-ffffffff81490936: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c5fc0)
Location: fs/namei.c:2467
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff814c5fc0-ffffffff814c6162: path_lookupat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f88b0)
Location: fs/namei.c:2474
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff814f88b0-ffffffff814f8a52: path_lookupat (STB_LOCAL)
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
In fs/namei.c (ffff800010395180)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffff800010395180-ffff80001039538c: path_lookupat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057d568)
Location: fs/namei.c:2297
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
c057d568-c057d780: path_lookupat (STB_LOCAL)
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
In fs/namei.c (c000000000490d10)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
c000000000490d10-c000000000490fb0: path_lookupat.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int path_lookupat(struct nameidata *nd, unsigned int flags, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000263a26)
Location: fs/namei.c:2297
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffe000263a26-ffffffe000263bf4: path_lookupat (STB_LOCAL)
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
In fs/namei.c (ffffffff812e3fc0)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812e3fc0-ffffffff812e41e2: path_lookupat.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812d4c00)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812d4c00-ffffffff812d4e22: path_lookupat.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812e1dd0)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812e1dd0-ffffffff812e1ff2: path_lookupat.isra.0 (STB_LOCAL)
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
In fs/namei.c (ffffffff812f4ee0)
Location: fs/namei.c:2297
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
  - fs/namei.c:filename_lookup
```
**Symbols:**

```
ffffffff812f4ee0-ffffffff812f5102: path_lookupat.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
