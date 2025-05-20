# Function: <code>configfs_dir_set_ready</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812dece0)
Location: fs/configfs/dir.c:319
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff812dece0-ffffffff812ded26: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81303650)
Location: fs/configfs/dir.c:319
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81303650-ffffffff81303696: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813315c0)
Location: fs/configfs/dir.c:319
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff813315c0-ffffffff81331606: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813489b0)
Location: fs/configfs/dir.c:319
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff813489b0-ffffffff813489f6: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81370f10)
Location: fs/configfs/dir.c:334
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81370f10-ffffffff81370f56: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81389390)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81389390-ffffffff813893d6: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d6820)
Location: fs/configfs/dir.c:323
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813d4530-ffffffff813d478b: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e84f0)
Location: fs/configfs/dir.c:324
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813e6250-ffffffff813e64ab: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ef081)
Location: fs/configfs/dir.c:322
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff813ece00-ffffffff813ed079: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81440f71)
Location: fs/configfs/dir.c:330
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8143ed00-ffffffff8143ef79: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bcaea)
Location: fs/configfs/dir.c:330
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff814bae30-ffffffff814bb128: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8155464a)
Location: fs/configfs/dir.c:331
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff81552750-ffffffff81552a48: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158c3ca)
Location: fs/configfs/dir.c:331
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff8158a4b0-ffffffff8158a7c7: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c50ae)
Location: fs/configfs/dir.c:331
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
```
**Symbols:**

```
ffffffff815c3180-ffffffff815c3497: configfs_dir_set_ready (STB_LOCAL)
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
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff800010459918)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffff800010459918-ffff800010459980: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061b4bc)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
c061b4bc-c061b524: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000574900)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
c000000000574900-c00000000057498c: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ea584)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffe0002ea584-ffffffe0002ea5dc: configfs_dir_set_ready (STB_LOCAL)
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
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381970)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81381970-ffffffff813819b6: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372400)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81372400-ffffffff81372446: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137f440)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff8137f440-ffffffff8137f486: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void configfs_dir_set_ready(struct configfs_dirent *sd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81392f40)
Location: fs/configfs/dir.c:323
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_register_subsystem
  - fs/configfs/dir.c:configfs_register_group
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_dir_set_ready
```
**Symbols:**

```
ffffffff81392f40-ffffffff81392f86: configfs_dir_set_ready (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
