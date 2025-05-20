# Function: <code>debugfs_create_automount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, struct vfsmount * (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8131d500)
Location: fs/debugfs/inode.c:445
Inline: False
```
**Symbols:**

```
ffffffff8131d500-ffffffff8131d588: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, struct vfsmount * (*f)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81352840)
Location: fs/debugfs/inode.c:505
Inline: False
```
**Symbols:**

```
ffffffff81352840-ffffffff8135294c: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff81368af0)
Location: fs/debugfs/inode.c:505
Inline: False
```
**Symbols:**

```
ffffffff81368af0-ffffffff81368bfc: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff8137d180)
Location: fs/debugfs/inode.c:539
Inline: False
```
**Symbols:**

```
ffffffff8137d180-ffffffff8137d28c: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813a2090)
Location: fs/debugfs/inode.c:542
Inline: False
```
**Symbols:**

```
ffffffff813a2090-ffffffff813a219c: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813d12e0)
Location: fs/debugfs/inode.c:565
Inline: False
```
**Symbols:**

```
ffffffff813d12e0-ffffffff813d13de: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffff813ebb80)
Location: fs/debugfs/inode.c:568
Inline: False
```
**Symbols:**

```
ffffffff813ebb80-ffffffff813ebc89: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:584
Inline: False
```
**Symbols:**

```
ffffffff81418023-ffffffff81418042: debugfs_create_automount.cold (STB_LOCAL)
ffffffff81417c70-ffffffff81417d73: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffff81431ee3-ffffffff81431f02: debugfs_create_automount.cold (STB_LOCAL)
ffffffff81431b30-ffffffff81431c33: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:575
Inline: False
```
**Symbols:**

```
ffffffff81481b1b-ffffffff81481b3a: debugfs_create_automount.cold (STB_LOCAL)
ffffffff81481420-ffffffff81481537: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:595
Inline: False
```
**Symbols:**

```
ffffffff81bef88e-ffffffff81bef8ad: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8149eeb0-ffffffff8149f024: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:599
Inline: False
```
**Symbols:**

```
ffffffff81be1937-ffffffff81be1956: debugfs_create_automount.cold (STB_LOCAL)
ffffffff814a4e90-ffffffff814a5004: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:599
Inline: False
```
**Symbols:**

```
ffffffff81cd2536-ffffffff81cd2570: debugfs_create_automount.cold (STB_LOCAL)
ffffffff814fcfa0-ffffffff814fd133: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:609
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
```
**Symbols:**

```
ffffffff81e8567c-ffffffff81e856b6: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8158d7e0-ffffffff8158d975: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:632
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
```
**Symbols:**

```
ffffffff82072a6a-ffffffff82072a85: debugfs_create_automount.cold (STB_LOCAL)
ffffffff816346f0-ffffffff816348d4: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:632
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
```
**Symbols:**

```
ffffffff820f26ce-ffffffff820f26e9: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8166ca00-ffffffff8166cbe4: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:639
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_init_dentry
```
**Symbols:**

```
ffffffff821cf964-ffffffff821cf97f: debugfs_create_automount.cold (STB_LOCAL)
ffffffff816a6f20-ffffffff816a718e: debugfs_create_automount (STB_GLOBAL)
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
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffff800010516880)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffff800010516880-ffff8000105169a4: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c06d1650)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
c06d1650-c06d1774: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (c00000000065f830)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
c00000000065f830-c00000000065f9b8: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/inode.c (ffffffe00037ff98)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffe00037ff98-ffffffe0003800a2: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffff8142a4c3-ffffffff8142a4e2: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8142a110-ffffffff8142a213: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffff8141af43-ffffffff8141af62: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8141ab90-ffffffff8141ac93: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffff81426663-ffffffff81426682: debugfs_create_automount.cold (STB_LOCAL)
ffffffff814262b0-ffffffff814263b3: debugfs_create_automount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dentry *debugfs_create_automount(const char *name, struct dentry *parent, debugfs_automount_t f, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/inode.c (0)
Location: fs/debugfs/inode.c:586
Inline: False
```
**Symbols:**

```
ffffffff8143d523-ffffffff8143d542: debugfs_create_automount.cold (STB_LOCAL)
ffffffff8143d170-ffffffff8143d273: debugfs_create_automount (STB_GLOBAL)
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
<code>struct vfsmount * (*f)(void *)</code> ➡️ <code>debugfs_automount_t f</code>
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
