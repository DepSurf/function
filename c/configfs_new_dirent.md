# Function: <code>configfs_new_dirent</code>

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
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812dee40)
Location: fs/configfs/dir.c:172
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff812dee40-ffffffff812def15: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813037b0)
Location: fs/configfs/dir.c:172
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff813037b0-ffffffff81303885: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81332400)
Location: fs/configfs/dir.c:172
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81332400-ffffffff813324d5: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81349840)
Location: fs/configfs/dir.c:172
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81349840-ffffffff81349915: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81371640)
Location: fs/configfs/dir.c:183
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81371640-ffffffff81371738: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81389a90)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81389a90-ffffffff81389b78: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d4ca0)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff813d4ca0-ffffffff813d4d88: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e69c0)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff813e69c0-ffffffff813e6aa8: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ed740)
Location: fs/configfs/dir.c:180
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff813ed740-ffffffff813ed828: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8143fcb0)
Location: fs/configfs/dir.c:188
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff8143fcb0-ffffffff8143fd98: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814ba3c0)
Location: fs/configfs/dir.c:188
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff814ba3c0-ffffffff814ba4c0: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81551c20)
Location: fs/configfs/dir.c:188
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81551c20-ffffffff81551d20: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81589960)
Location: fs/configfs/dir.c:188
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81589960-ffffffff81589a60: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c2580)
Location: fs/configfs/dir.c:188
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff815c2580-ffffffff815c2680: configfs_new_dirent (STB_LOCAL)
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
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045a550)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffff80001045a550-ffff80001045a6a0: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061b6e0)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
c061b6e0-c061b7f0: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000574a20)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
c000000000574a20-c000000000574be8: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002eb8f2)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffe0002eb8f2-ffffffe0002eba42: configfs_new_dirent (STB_LOCAL)
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
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81382070)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81382070-ffffffff81382158: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372b00)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81372b00-ffffffff81372be8: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8137fb40)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff8137fb40-ffffffff8137fc28: configfs_new_dirent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct configfs_dirent *configfs_new_dirent(struct configfs_dirent *parent_sd, void *element, int type, struct configfs_fragment *frag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81393090)
Location: fs/configfs/dir.c:182
Inline: False
Direct callers:
  - fs/configfs/dir.c:configfs_dir_open
  - fs/configfs/dir.c:configfs_make_dirent
```
**Symbols:**

```
ffffffff81393090-ffffffff8139317b: configfs_new_dirent (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct configfs_fragment *frag</code>
</li>
</ul>
</details>
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
