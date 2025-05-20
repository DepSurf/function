# Function: <code>devtmpfs_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff81553270)
Location: drivers/base/devtmpfs.c:347
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff81553270-ffffffff815532de: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff815a5260)
Location: drivers/base/devtmpfs.c:347
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff815a5260-ffffffff815a52c4: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff815d3a10)
Location: drivers/base/devtmpfs.c:347
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff815d3a10-ffffffff815d3a74: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff815e8590)
Location: drivers/base/devtmpfs.c:348
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff815e8590-ffffffff815e85f4: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff8164f910)
Location: drivers/base/devtmpfs.c:349
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff8164f910-ffffffff8164f974: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:349
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff8168b30e-ffffffff8168b332: devtmpfs_mount.cold.7 (STB_LOCAL)
ffffffff8168b2c0-ffffffff8168b30e: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:350
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff816ab53e-ffffffff816ab562: devtmpfs_mount.cold.7 (STB_LOCAL)
ffffffff816ab4f0-ffffffff816ab53e: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:350
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff816e50f5-ffffffff816e5119: devtmpfs_mount.cold (STB_LOCAL)
ffffffff816e50a0-ffffffff816e50f5: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff817093d5-ffffffff817093f9: devtmpfs_mount.cold (STB_LOCAL)
ffffffff81709380-ffffffff817093d5: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff82d1edaa)
Location: drivers/base/devtmpfs.c:352
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff82d1edaa-ffffffff82d1ee17: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff8300cc56)
Location: drivers/base/devtmpfs.c:353
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff8300cc56-ffffffff8300ccc2: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83217ab5)
Location: drivers/base/devtmpfs.c:356
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff83217ab5-ffffffff83217b21: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff833014cb)
Location: drivers/base/devtmpfs.c:363
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff833014cb-ffffffff83301537: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff834ba31f)
Location: drivers/base/devtmpfs.c:367
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff834ba31f-ffffffff834ba392: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83ef7a20)
Location: drivers/base/devtmpfs.c:367
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff83ef7a20-ffffffff83ef7aac: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff8371d5c0)
Location: drivers/base/devtmpfs.c:360
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff8371d5c0-ffffffff8371d64c: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devtmpfs_mount();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffff83951130)
Location: drivers/base/devtmpfs.c:360
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff83951130-ffffffff839511bc: devtmpfs_mount (STB_GLOBAL)
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
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffff8000108f7118)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffff8000108f7118-ffff8000108f71a0: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (c09e3100)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
c09e3100-c09e3194: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (c000000000992850)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
c000000000992850-c000000000992908: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devtmpfs.c (ffffffe000587f4c)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffe000587f4c-ffffffe000587fc8: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff816ceb25-ffffffff816ceb49: devtmpfs_mount.cold (STB_LOCAL)
ffffffff816cead0-ffffffff816ceb25: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff816a9e55-ffffffff816a9e79: devtmpfs_mount.cold (STB_LOCAL)
ffffffff816a9e00-ffffffff816a9e55: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff816fd095-ffffffff816fd0b9: devtmpfs_mount.cold (STB_LOCAL)
ffffffff816fd040-ffffffff816fd095: devtmpfs_mount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devtmpfs_mount(const char *mntdir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/devtmpfs.c (0)
Location: drivers/base/devtmpfs.c:362
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
```
**Symbols:**

```
ffffffff81717925-ffffffff81717949: devtmpfs_mount.cold (STB_LOCAL)
ffffffff817178d0-ffffffff81717925: devtmpfs_mount (STB_GLOBAL)
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
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const char *mntdir</code>
</li>
</ul>
</details>
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
