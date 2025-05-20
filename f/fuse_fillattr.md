# Function: <code>fuse_fillattr</code>

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
In fs/fuse/dir.c (ffffffff8131327e)
Location: fs/fuse/dir.c:825
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff813477f5)
Location: fs/fuse/dir.c:829
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8135d11a)
Location: fs/fuse/dir.c:842
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff81371b0a)
Location: fs/fuse/dir.c:842
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff813967fe)
Location: fs/fuse/dir.c:842
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff813c53b4)
Location: fs/fuse/dir.c:843
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff813de554)
Location: fs/fuse/dir.c:840
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff81409a7b)
Location: fs/fuse/dir.c:827
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff814241d4)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_fillattr(struct inode *inode, struct fuse_attr *attr, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81472170)
Location: fs/fuse/dir.c:884
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
**Symbols:**

```
ffffffff81472170-ffffffff814722b5: fuse_fillattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_fillattr(struct inode *inode, struct fuse_attr *attr, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148ca40)
Location: fs/fuse/dir.c:984
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
**Symbols:**

```
ffffffff8148ca40-ffffffff8148cb88: fuse_fillattr (STB_LOCAL)
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
In fs/fuse/dir.c (ffffffff814939f7)
Location: fs/fuse/dir.c:1001
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff814eae57)
Location: fs/fuse/dir.c:949
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff81579985)
Location: fs/fuse/dir.c:1038
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8161f025)
Location: fs/fuse/dir.c:1061
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8165744a)
Location: fs/fuse/dir.c:1127
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fuse_fillattr(struct inode *inode, struct fuse_attr *attr, struct kstat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dir.c (0)
Location: fs/fuse/dir.c:1124
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_do_getattr
  - fs/fuse/dir.c:fuse_do_statx
```
**Symbols:**

```
ffffffff8168f5d0-ffffffff8168f6df: fuse_fillattr (STB_LOCAL)
ffffffff821cf598-ffffffff821cf5b6: fuse_fillattr.cold (STB_LOCAL)
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
In fs/fuse/dir.c (ffff800010507944)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (c06c380c)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (c00000000064d024)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffe0003737ba)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8141c7b4)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8140d234)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff81418954)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
In fs/fuse/dir.c (ffffffff8142f6c4)
Location: fs/fuse/dir.c:884
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_do_getattr
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
</ul>
