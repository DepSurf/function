# Function: <code>init_chroot</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff82feda96)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfsd
```
**Symbols:**

```
ffffffff82feda96-ffffffff82fedb55: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff831f82af)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff831f82af-ffffffff831f836a: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff832df228)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff832df228-ffffffff832df2e3: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83494df6)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83494df6-ffffffff83494ece: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83ec9760)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83ec9760-ffffffff83ec9852: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff836ee7c0)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff836ee7c0-ffffffff836ee8a8: init_chroot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_chroot(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/init.c (ffffffff83921810)
Location: fs/init.c:59
Inline: False
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - drivers/base/devtmpfs.c:devtmpfs_setup
```
**Symbols:**

```
ffffffff83921810-ffffffff839218f8: init_chroot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
