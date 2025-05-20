# Function: <code>step_into</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81254d75)
Location: fs/namei.c:1732
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
In fs/namei.c (ffffffff81260dce)
Location: fs/namei.c:1742
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
In fs/namei.c (ffffffff812834b7)
Location: fs/namei.c:1740
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
In fs/namei.c (ffffffff812aa5f0)
Location: fs/namei.c:1727
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
In fs/namei.c (ffffffff812bf783)
Location: fs/namei.c:1768
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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dc9e7)
Location: fs/namei.c:1766
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffff812ee536)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry, struct inode *inode, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81323180)
Location: fs/namei.c:1686
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81323180-ffffffff813233df: step_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry, struct inode *inode, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132e720)
Location: fs/namei.c:1682
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8132e720-ffffffff8132e97e: step_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry, struct inode *inode, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333af0)
Location: fs/namei.c:1768
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81333af0-ffffffff81333e72: step_into (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry, struct inode *inode, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1796
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81381420-ffffffff813817cc: step_into (STB_LOCAL)
ffffffff81cc3a72-ffffffff81cc3a97: step_into.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry, struct inode *inode, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1842
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff81404dd0-ffffffff814051b7: step_into (STB_LOCAL)
ffffffff81e7628f-ffffffff81e762b8: step_into.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1826
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff8148f270-ffffffff8148f5fb: step_into (STB_LOCAL)
ffffffff82068899-ffffffff820688ae: step_into.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1831
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff814c4a30-ffffffff814c4dbe: step_into (STB_LOCAL)
ffffffff820e8194-ffffffff820e81a9: step_into.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const char *step_into(struct nameidata *nd, int flags, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:1838
Inline: False
Direct callers:
  - fs/namei.c:open_last_lookups
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_lookupat
  - fs/namei.c:walk_component
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff814f7210-ffffffff814f759e: step_into (STB_LOCAL)
ffffffff821c4ed1-ffffffff821c4ee6: step_into.cold (STB_LOCAL)
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
In fs/namei.c (ffff800010397d28)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (c057e2f4)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (c000000000491d30)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffe000265bec)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffff812e6b16)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffff812d7756)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffff812e4926)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
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
In fs/namei.c (ffffffff812f58a6)
Location: fs/namei.c:1759
Inline: True
Inline callers:
  - fs/namei.c:do_last
  - fs/namei.c:path_mountpoint
  - fs/namei.c:walk_component
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
