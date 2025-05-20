# Function: <code>lookup_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d9c0)
Location: fs/namespace.c:679
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_down
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff8122d9c0-ffffffff8122da17: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812561b0)
Location: fs/namespace.c:679
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812561b0-ffffffff8125620e: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812695a0)
Location: fs/namespace.c:656
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812695a0-ffffffff812695fe: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276d30)
Location: fs/namespace.c:657
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81276d30-ffffffff81276d91: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299770)
Location: fs/namespace.c:717
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81299770-ffffffff812997d1: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf620)
Location: fs/namespace.c:727
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812bf620-ffffffff812bf683: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4830)
Location: fs/namespace.c:639
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812d4830-ffffffff812d488f: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1d40)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812f1d40-ffffffff812f1d97: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303900)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81303900-ffffffff81303957: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133d6d0)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff8133d6d0-ffffffff8133d752: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349630)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81349630-ffffffff813496b9: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350010)
Location: fs/namespace.c:650
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81350010-ffffffff81350099: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139e3d0)
Location: fs/namespace.c:652
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff8139e3d0-ffffffff8139e459: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421570)
Location: fs/namespace.c:695
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff81421570-ffffffff81421607: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814adaa0)
Location: fs/namespace.c:806
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff814adaa0-ffffffff814adb37: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e2880)
Location: fs/namespace.c:715
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
```
**Symbols:**

```
ffffffff814e2880-ffffffff814e2917: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81516670)
Location: fs/namespace.c:722
Inline: False
Direct callers:
  - fs/namei.c:follow_down_one
  - fs/namei.c:__traverse_mounts
  - fs/namespace.c:do_lock_mount
  - fs/namespace.c:do_lock_mount
```
**Symbols:**

```
ffffffff81516670-ffffffff81516707: lookup_mnt (STB_GLOBAL)
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
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b6f18)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffff8000103b6f18-ffff8000103b6f94: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05955e8)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
c05955e8-c0595678: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3880)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
c0000000004b3880-c0000000004b3934: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000279b52)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffe000279b52-ffffffe000279bc8: lookup_mnt (STB_GLOBAL)
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
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbee0)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812fbee0-ffffffff812fbf37: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ecb00)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812ecb00-ffffffff812ecb57: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9cd0)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff812f9cd0-ffffffff812f9d27: lookup_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vfsmount *lookup_mnt(const struct path *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b010)
Location: fs/namespace.c:636
Inline: False
Direct callers:
  - fs/namei.c:follow_mount
  - fs/namei.c:follow_down
  - fs/namei.c:follow_down_one
  - fs/namei.c:follow_managed
  - fs/namespace.c:lock_mount
```
**Symbols:**

```
ffffffff8130b010-ffffffff8130b071: lookup_mnt (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct path *path</code> ➡️ <code>const struct path *path</code>
</li>
</ul>
</details>
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
