# Function: <code>vfs_utimes</code>

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
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81360020)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff81360020-ffffffff81360228: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81366ab0)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff81366ab0-ffffffff81366cc4: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff813b5600)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff813b5600-ffffffff813b5814: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8143a8e0)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff8143a8e0-ffffffff8143ab49: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814c8d90)
Location: fs/utimes.c:19
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff814c8d90-ffffffff814c9000: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff814fefd0)
Location: fs/utimes.c:20
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff814fefd0-ffffffff814ff23a: vfs_utimes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_utimes(const struct path *path, struct timespec64 *times);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81533c00)
Location: fs/utimes.c:20
Inline: False
Direct callers:
  - init/initramfs.c:do_copy
  - fs/utimes.c:do_utimes
  - fs/utimes.c:do_utimes
  - fs/init.c:init_utimes
```
**Symbols:**

```
ffffffff81533c00-ffffffff81533e6a: vfs_utimes (STB_GLOBAL)
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
