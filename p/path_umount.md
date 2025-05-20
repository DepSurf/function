# Function: <code>path_umount</code>

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
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349b70)
Location: fs/namespace.c:1738
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff81349b70-ffffffff81349c31: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350560)
Location: fs/namespace.c:1753
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff81350560-ffffffff81350621: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139e920)
Location: fs/namespace.c:1754
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff8139e920-ffffffff8139e9e1: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421b60)
Location: fs/namespace.c:1795
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff81421b60-ffffffff81421c29: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae120)
Location: fs/namespace.c:1900
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff814ae120-ffffffff814ae1e9: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e30c0)
Location: fs/namespace.c:1887
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff814e30c0-ffffffff814e3189: path_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int path_umount(struct path *path, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81516e10)
Location: fs/namespace.c:1889
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
  - fs/init.c:init_umount
```
**Symbols:**

```
ffffffff81516e10-ffffffff81516ed9: path_umount (STB_GLOBAL)
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
