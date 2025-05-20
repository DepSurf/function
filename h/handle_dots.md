# Function: <code>handle_dots</code>

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
In fs/namei.c (ffffffff8121943a)
Location: fs/namei.c:1655
Inline: True
Inline callers:
  - fs/namei.c:walk_component
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81241db4)
Location: fs/namei.c:1681
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff81254c95)
Location: fs/namei.c:1677
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff81260cf0)
Location: fs/namei.c:1679
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812833d8)
Location: fs/namei.c:1677
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812aa803)
Location: fs/namei.c:1664
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
In fs/namei.c (ffffffff812bf8a7)
Location: fs/namei.c:1705
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dccd6)
Location: fs/namei.c:1703
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ee80e)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff813260cc)
Location: fs/namei.c:1796
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff813233e0-ffffffff813234d0: handle_dots.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff8133158a)
Location: fs/namei.c:1792
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8132e980-ffffffff8132ea70: handle_dots.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81337f4a)
Location: fs/namei.c:1878
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81334070-ffffffff813343e0: handle_dots.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff813859e5)
Location: fs/namei.c:1906
Inline: True
Inline callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff813819c0-ffffffff81381d30: handle_dots.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *handle_dots(struct nameidata *nd, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81405670)
Location: fs/namei.c:1952
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81405670-ffffffff81405a50: handle_dots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *handle_dots(struct nameidata *nd, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148faf0)
Location: fs/namei.c:1938
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8148faf0-ffffffff8148fd71: handle_dots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *handle_dots(struct nameidata *nd, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c4dd0)
Location: fs/namei.c:1943
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814c4dd0-ffffffff814c5179: handle_dots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *handle_dots(struct nameidata *nd, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f75b0)
Location: fs/namei.c:1950
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff814f75b0-ffffffff814f7959: handle_dots (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397f68)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057e574)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000491ef0)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000265dd2)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6dee)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d7a2e)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4bfe)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f5b7e)
Location: fs/namei.c:1698
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/namei.c:walk_component
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
