# Function: <code>legitimize_mnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d880)
Location: fs/namespace.c:613
Inline: True
Direct callers:
  - fs/namei.c:unlazy_walk
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8122d880-ffffffff8122d8d2: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81256070)
Location: fs/namespace.c:613
Inline: True
Direct callers:
  - fs/namei.c:unlazy_walk
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff81256070-ffffffff812560c3: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81269460)
Location: fs/namespace.c:612
Inline: True
Direct callers:
  - fs/namei.c:unlazy_walk
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff81269460-ffffffff812694b3: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276c00)
Location: fs/namespace.c:613
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff81276c00-ffffffff81276c50: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299640)
Location: fs/namespace.c:673
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff81299640-ffffffff81299690: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf4f0)
Location: fs/namespace.c:683
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812bf4f0-ffffffff812bf540: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4700)
Location: fs/namespace.c:595
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812d4700-ffffffff812d4750: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1c10)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812f1c10-ffffffff812f1c61: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813037c0)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff813037c0-ffffffff81303811: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133d70b)
Location: fs/namespace.c:592
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - fs/namei.c:unlazy_child
```
**Symbols:**

```
ffffffff8133d540-ffffffff8133d5fc: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134966f)
Location: fs/namespace.c:592
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - fs/namei.c:unlazy_child
```
**Symbols:**

```
ffffffff81349490-ffffffff81349551: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8135004f)
Location: fs/namespace.c:606
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - fs/namei.c:try_to_unlazy_next
```
**Symbols:**

```
ffffffff8134fe70-ffffffff8134ff31: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139e40f)
Location: fs/namespace.c:608
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
  - fs/namespace.c:lookup_mnt
Direct callers:
  - fs/namei.c:try_to_unlazy_next
```
**Symbols:**

```
ffffffff8139e210-ffffffff8139e2d1: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814215b2)
Location: fs/namespace.c:651
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
Direct callers:
  - fs/namei.c:try_to_unlazy_next
```
**Symbols:**

```
ffffffff81421360-ffffffff81421442: legitimize_mnt (STB_GLOBAL)
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
In fs/namespace.c (ffffffff814adae2)
Location: fs/namespace.c:762
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
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
In fs/namespace.c (ffffffff814e28c2)
Location: fs/namespace.c:655
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff815166b2)
Location: fs/namespace.c:662
Inline: True
Inline callers:
  - fs/namespace.c:lookup_mnt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b6d70)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffff8000103b6d70-ffff8000103b6df0: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595474)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
c0595474-c05954d4: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3640)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
c0000000004b3640-c0000000004b36f8: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002799f8)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffe0002799f8-ffffffe000279a54: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fbda0)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812fbda0-ffffffff812fbdf1: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ec9c0)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812ec9c0-ffffffff812eca11: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9b90)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff812f9b90-ffffffff812f9be1: legitimize_mnt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool legitimize_mnt(struct vfsmount *bastard, unsigned int seq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130aec0)
Location: fs/namespace.c:592
Inline: True
Direct callers:
  - fs/namei.c:lookup_fast
  - fs/namespace.c:lookup_mnt
```
**Symbols:**

```
ffffffff8130aec0-ffffffff8130af1b: legitimize_mnt (STB_GLOBAL)
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
