# Function: <code>fs_validate_description</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8130b550)
Location: fs/fs_parser.c:346
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff8130b550-ffffffff8130b73d: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8131e550)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff8131e550-ffffffff8131e73d: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:365
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff8135854f-ffffffff8135856a: fs_validate_description.cold (STB_LOCAL)
ffffffff81358440-ffffffff813584c9: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:365
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81bea9e3-ffffffff81bea9fe: fs_validate_description.cold (STB_LOCAL)
ffffffff81364e60-ffffffff81364ee9: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:365
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81bdc9f6-ffffffff81bdca11: fs_validate_description.cold (STB_LOCAL)
ffffffff8136b8b0-ffffffff8136b939: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:364
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81cc42d8-ffffffff81cc42f3: fs_validate_description.cold (STB_LOCAL)
ffffffff813ba580-ffffffff813ba609: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:379
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81e76bde-ffffffff81e76bf9: fs_validate_description.cold (STB_LOCAL)
ffffffff81440270-ffffffff81440300: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff814cf0f0)
Location: fs/fs_parser.c:380
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff814cf0f0-ffffffff814cf199: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81505370)
Location: fs/fs_parser.c:380
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81505370-ffffffff81505419: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fs_validate_description(const char *name, const struct fs_parameter_spec *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff8153a030)
Location: fs/fs_parser.c:380
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff8153a030-ffffffff8153a0d9: fs_validate_description (STB_GLOBAL)
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
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffff8000103d681c)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffff8000103d681c-ffff8000103d6a60: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05b0408)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
c05b0408-c05b0668: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c0000000004da990)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
c0000000004da990-c0000000004dac58: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffe00029045e)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffe00029045e-ffffffe000290640: fs_validate_description (STB_GLOBAL)
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
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81316b30)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81316b30-ffffffff81316d1d: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81307720)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81307720-ffffffff8130790d: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/filesystems.c (0)
Location: include/linux/fs_parser.h:105
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/fs_parser.h:105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool fs_validate_description(const struct fs_parameter_description *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81326170)
Location: fs/fs_parser.c:360
Inline: False
Direct callers:
  - fs/filesystems.c:register_filesystem
  - security/selinux/hooks.c:selinux_init
```
**Symbols:**

```
ffffffff81326170-ffffffff8132635d: fs_validate_description (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *name</code>
</li>
<li>
<b>Param reordered. </b>
<code>desc</code> ➡️ <code>name, desc</code>
</li>
<li>
<b>Param type changed. </b>
<code>const struct fs_parameter_description *desc</code> ➡️ <code>const struct fs_parameter_spec *desc</code>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
