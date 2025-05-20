# Function: <code>lock_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122da20)
Location: fs/namespace.c:1953
Inline: False
Direct callers:
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:SyS_pivot_root
```
**Symbols:**

```
ffffffff8122da20-ffffffff8122dbd6: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256210)
Location: fs/namespace.c:1962
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff81256210-ffffffff812563c9: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81269600)
Location: fs/namespace.c:2079
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff81269600-ffffffff812696f5: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276da0)
Location: fs/namespace.c:2021
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff81276da0-ffffffff81276e95: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812997e0)
Location: fs/namespace.c:2086
Inline: False
Direct callers:
  - fs/namespace.c:SyS_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812997e0-ffffffff812998d5: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf690)
Location: fs/namespace.c:2117
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812bf690-ffffffff812bf78b: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4890)
Location: fs/namespace.c:2041
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812d4890-ffffffff812d498b: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1da0)
Location: fs/namespace.c:2135
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812f1da0-ffffffff812f1e8f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303960)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff81303960-ffffffff81303a4f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133d760)
Location: fs/namespace.c:2196
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff8133d760-ffffffff8133d84f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813496c0)
Location: fs/namespace.c:2202
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount_fc
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff813496c0-ffffffff813497af: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813500a0)
Location: fs/namespace.c:2244
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff813500a0-ffffffff8135018f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139e460)
Location: fs/namespace.c:2246
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff8139e460-ffffffff8139e54f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421610)
Location: fs/namespace.c:2287
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff81421610-ffffffff81421713: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814adb50)
Location: fs/namespace.c:2392
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
ffffffff814adb50-ffffffff814adc53: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e6ac9)
Location: fs/namespace.c:2494
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151a909)
Location: fs/namespace.c:2500
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_pivot_root
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
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
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b6f98)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffff8000103b6f98-ffff8000103b7088: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595678)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
  - fs/namespace.c:do_move_mount
```
**Symbols:**

```
c0595678-c0595750: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3940)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
c0000000004b3940-c0000000004b3a9c: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000279bc8)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffe000279bc8-ffffffe000279cb4: lock_mount (STB_LOCAL)
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
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbf40)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812fbf40-ffffffff812fc02f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ecb60)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812ecb60-ffffffff812ecc4f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9d30)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff812f9d30-ffffffff812f9e1f: lock_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mountpoint *lock_mount(struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b080)
Location: fs/namespace.c:2138
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_pivot_root
  - fs/namespace.c:__x64_sys_pivot_root
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_add_mount
```
**Symbols:**

```
ffffffff8130b080-ffffffff8130b16f: lock_mount (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
