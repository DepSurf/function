# Function: <code>new_fragment</code>

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
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81371150)
Location: fs/configfs/dir.c:154
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81371150-ffffffff813711a3: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813895d0)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813895d0-ffffffff81389623: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d6975)
Location: fs/configfs/dir.c:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e865c)
Location: fs/configfs/dir.c:153
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813eef6c)
Location: fs/configfs/dir.c:151
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81440e2c)
Location: fs/configfs/dir.c:159
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bc99c)
Location: fs/configfs/dir.c:159
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815544fc)
Location: fs/configfs/dir.c:159
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
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
In fs/configfs/dir.c (ffffffff8158c27c)
Location: fs/configfs/dir.c:159
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c29d0)
Location: fs/configfs/dir.c:159
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff815c29d0-ffffffff815c2a5b: new_fragment (STB_LOCAL)
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
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff800010459bd0)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffff800010459bd0-ffff800010459c30: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061bd10)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c061bd10-c061bd74: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000575630)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
c000000000575630-c0000000005756b8: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ea8f6)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffe0002ea8f6-ffffffe0002ea956: new_fragment (STB_LOCAL)
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
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381bb0)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81381bb0-ffffffff81381c03: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372640)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81372640-ffffffff81372693: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137f680)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8137f680-ffffffff8137f6d3: new_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct configfs_fragment *new_fragment();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81393620)
Location: fs/configfs/dir.c:153
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81393620-ffffffff81393673: new_fragment (STB_LOCAL)
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
