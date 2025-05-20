# Function: <code>follow_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812170d0)
Location: fs/namei.c:1055
Inline: True
Direct callers:
  - fs/namei.c:follow_dotdot
```
**Symbols:**

```
ffffffff812170d0-ffffffff81217168: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123e2b0)
Location: fs/namei.c:1071
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123e2b0-ffffffff8123e344: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251090)
Location: fs/namei.c:1071
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81251090-ffffffff81251124: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125cfd0)
Location: fs/namei.c:1083
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125cfd0-ffffffff8125d06d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127e570)
Location: fs/namei.c:1084
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff8127e570-ffffffff8127e60d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6e50)
Location: fs/namei.c:1071
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812a6e50-ffffffff812a6ee9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bc070)
Location: fs/namei.c:1112
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812bc070-ffffffff812bc109: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8c30)
Location: fs/namei.c:1110
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812d8c30-ffffffff812d8cc9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ea740)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812ea740-ffffffff812ea7d9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813223e0)
Location: fs/namei.c:1102
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff813223e0-ffffffff8132247d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d9b0)
Location: fs/namei.c:1102
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff8132d9b0-ffffffff8132da4d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333e80)
Location: fs/namei.c:1187
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81333e80-ffffffff81333f1d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813817d0)
Location: fs/namei.c:1215
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff813817d0-ffffffff8138186d: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813ffb20)
Location: fs/namei.c:1259
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
  - security/landlock/fs.c:check_access_path_dual
```
**Symbols:**

```
ffffffff813ffb20-ffffffff813ffbc0: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489b10)
Location: fs/namei.c:1267
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff81489b10-ffffffff81489bb0: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814beb00)
Location: fs/namei.c:1270
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff814beb00-ffffffff814beba0: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f0f80)
Location: fs/namei.c:1273
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mntget
  - security/landlock/fs.c:is_access_to_paths_allowed
```
**Symbols:**

```
ffffffff814f0f80-ffffffff814f1020: follow_up (STB_GLOBAL)
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
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393878)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffff800010393878-ffff800010393988: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a098)
Location: fs/namei.c:1105
Inline: True
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
c057a098-c057a158: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d4b0)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
c00000000048d4b0-c00000000048d610: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002627f4)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffe0002627f4-ffffffe000262914: follow_up (STB_GLOBAL)
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
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2d20)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812e2d20-ffffffff812e2db9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3960)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812d3960-ffffffff812d39f9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0b30)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812e0b30-ffffffff812e0bc9: follow_up (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int follow_up(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eff00)
Location: fs/namei.c:1105
Inline: False
Direct callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812eff00-ffffffff812eff94: follow_up (STB_GLOBAL)
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
