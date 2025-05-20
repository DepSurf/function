# Function: <code>agp_find_private</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8151b662)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_controller_make_current
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
```
**Symbols:**

```
ffffffff8151bcd0-ffffffff8151bcff: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8156f314)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
ffffffff8156ea10-ffffffff8156ea3b: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8159b9d4)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
ffffffff8159b0d0-ffffffff8159b0fb: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff815af866)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
ffffffff815af130-ffffffff815af15b: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816163d6)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
ffffffff81615ca0-ffffffff81615ccb: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816501c3)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8164fa10-ffffffff8164fa3b: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8166e35f)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8166dbc0-ffffffff8166dbeb: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816a3a43)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816a3760-ffffffff816a3786: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816c6c7f)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816c64f0-ffffffff816c6516: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8177a8a1)
Location: drivers/char/agp/frontend.c:213
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_controller_release_current
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
ffffffff8177aef0-ffffffff8177af16: agp_find_private (STB_GLOBAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (c000000000953750)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
```
**Symbols:**

```
c000000000953280-c0000000009532d0: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8168c6cf)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff8168bf40-ffffffff8168bf66: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff8166a0cf)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff81669940-ffffffff81669966: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816ba93f)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816ba1b0-ffffffff816ba1d6: agp_find_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct agp_file_private *agp_find_private(pid_t pid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/agp/frontend.c (ffffffff816d4f0f)
Location: drivers/char/agp/frontend.c:215
Inline: True
Inline callers:
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_ioctl
  - drivers/char/agp/frontend.c:agp_release
  - drivers/char/agp/frontend.c:agp_controller_make_current
Direct callers:
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
  - drivers/char/agp/compat_ioctl.c:compat_agp_ioctl
```
**Symbols:**

```
ffffffff816d4780-ffffffff816d47a6: agp_find_private (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
