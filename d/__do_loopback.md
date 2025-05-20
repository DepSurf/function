# Function: <code>__do_loopback</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffff812f2960)
Location: fs/namespace.c:2253
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812f2960-ffffffff812f2a3c: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff81304520)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81304520-ffffffff813045fc: __do_loopback.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133e0f0)
Location: fs/namespace.c:2314
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8133e0f0-ffffffff8133e1cd: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134a150)
Location: fs/namespace.c:2320
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8134a150-ffffffff8134a22d: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350b40)
Location: fs/namespace.c:2349
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
```
**Symbols:**

```
ffffffff81350b40-ffffffff81350c1d: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139ef00)
Location: fs/namespace.c:2351
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:__do_sys_open_tree
```
**Symbols:**

```
ffffffff8139ef00-ffffffff8139efdd: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814221b0)
Location: fs/namespace.c:2392
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff814221b0-ffffffff814222a1: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae7e0)
Location: fs/namespace.c:2497
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff814ae7e0-ffffffff814ae8d1: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e3740)
Location: fs/namespace.c:2575
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff814e3740-ffffffff814e3831: __do_loopback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81517490)
Location: fs/namespace.c:2581
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff81517490-ffffffff81517581: __do_loopback (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b7e38)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__arm64_sys_open_tree
```
**Symbols:**

```
ffff8000103b7e38-ffff8000103b7f4c: __do_loopback.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mount *__do_loopback(struct path *old_path, int recurse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595fb0)
Location: fs/namespace.c:2256
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
c0595fb0-c05960ac: __do_loopback (STB_LOCAL)
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
In fs/namespace.c (c0000000004b4b60)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
c0000000004b4b60-c0000000004b4cf0: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffe00027a7d0)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:__se_sys_open_tree
```
**Symbols:**

```
ffffffe00027a7d0-ffffffe00027a8ae: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812fcb00)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812fcb00-ffffffff812fcbdc: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812ed720)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812ed720-ffffffff812ed7fc: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812fa8f0)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff812fa8f0-ffffffff812fa9cc: __do_loopback.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff8130bc20)
Location: fs/namespace.c:2256
Inline: True
Direct callers:
  - fs/namespace.c:do_mount
  - fs/namespace.c:open_detached_copy
```
**Symbols:**

```
ffffffff8130bc20-ffffffff8130bcfc: __do_loopback.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
