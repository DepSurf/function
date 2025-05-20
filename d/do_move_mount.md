# Function: <code>do_move_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122f0ce)
Location: fs/namespace.c:2235
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81257873)
Location: fs/namespace.c:2238
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126ad03)
Location: fs/namespace.c:2357
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8127847a)
Location: fs/namespace.c:2299
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129ac97)
Location: fs/namespace.c:2364
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c1055)
Location: fs/namespace.c:2395
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d62eb)
Location: fs/namespace.c:2365
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812f3c40)
Location: fs/namespace.c:2576
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812f3c40-ffffffff812f3f81: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff813057f0)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff813057f0-ffffffff81305b31: do_move_mount.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133f3d0)
Location: fs/namespace.c:2666
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8133f3d0-ffffffff8133f70e: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134b430)
Location: fs/namespace.c:2672
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff8134b430-ffffffff8134b76e: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351cd0)
Location: fs/namespace.c:2705
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff81351cd0-ffffffff81352020: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a0040)
Location: fs/namespace.c:2779
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff813a0040-ffffffff813a0390: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814236c0)
Location: fs/namespace.c:2822
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814236c0-ffffffff81423c47: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814afe20)
Location: fs/namespace.c:2927
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814afe20-ffffffff814b03a7: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path, bool beneath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e4e60)
Location: fs/namespace.c:3104
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814e4e60-ffffffff814e54ec: do_move_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path, bool beneath);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81518c90)
Location: fs/namespace.c:3115
Inline: False
Direct callers:
  - fs/namespace.c:__do_sys_move_mount
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff81518c90-ffffffff8151931f: do_move_mount (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b8f20)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__arm64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffff8000103b8f20-ffff8000103b9370: do_move_mount.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_move_mount(struct path *old_path, struct path *new_path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0596894)
Location: fs/namespace.c:2607
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0596894-c0596c70: do_move_mount (STB_LOCAL)
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
In fs/namespace.c (c0000000004b6080)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
c0000000004b6080-c0000000004b65ec: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffe00027b2a4)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__se_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffe00027b2a4-ffffffe00027b584: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812fddd0)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fddd0-ffffffff812fe111: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812ee9f0)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812ee9f0-ffffffff812eed31: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff812fbbc0)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff812fbbc0-ffffffff812fbf01: do_move_mount.isra.0 (STB_LOCAL)
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
In fs/namespace.c (ffffffff8130cee0)
Location: fs/namespace.c:2607
Inline: True
Direct callers:
  - fs/namespace.c:__ia32_sys_move_mount
  - fs/namespace.c:__x64_sys_move_mount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8130cee0-ffffffff8130d26f: do_move_mount.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool beneath</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
