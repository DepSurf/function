# Function: <code>mnt_change_mountpoint</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81269830)
Location: fs/namespace.c:878
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81269830-ffffffff8126991a: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276fd0)
Location: fs/namespace.c:879
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81276fd0-ffffffff812770ba: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299a10)
Location: fs/namespace.c:946
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81299a10-ffffffff81299afa: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf8b0)
Location: fs/namespace.c:956
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812bf8b0-ffffffff812bf994: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4ab0)
Location: fs/namespace.c:868
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812d4ab0-ffffffff812d4b94: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f1f90)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812f1f90-ffffffff812f2046: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303b50)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81303b50-ffffffff81303c06: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133d950)
Location: fs/namespace.c:882
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff8133d950-ffffffff8133da50: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813498b0)
Location: fs/namespace.c:882
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff813498b0-ffffffff813499b0: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350290)
Location: fs/namespace.c:889
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81350290-ffffffff81350393: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139e650)
Location: fs/namespace.c:898
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff8139e650-ffffffff8139e753: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421830)
Location: fs/namespace.c:934
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81421830-ffffffff81421944: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814adda0)
Location: fs/namespace.c:1045
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff814adda0-ffffffff814adeb4: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e2c60)
Location: fs/namespace.c:1008
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff814e2c60-ffffffff814e2d2e: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81516a50)
Location: fs/namespace.c:996
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_recursive_mnt
  - fs/namespace.c:attach_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff81516a50-ffffffff81516b1e: mnt_change_mountpoint (STB_GLOBAL)
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
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b71c0)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffff8000103b71c0-ffff8000103b72a4: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595864)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
c0595864-c0595950: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3c50)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
c0000000004b3c50-c0000000004b3d84: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000279dc4)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffe000279dc4-ffffffe000279e8a: mnt_change_mountpoint (STB_GLOBAL)
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
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc130)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812fc130-ffffffff812fc1e6: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ecd50)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812ecd50-ffffffff812ece06: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9f20)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff812f9f20-ffffffff812f9fd6: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mnt_change_mountpoint(struct mount *parent, struct mountpoint *mp, struct mount *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b270)
Location: fs/namespace.c:866
Inline: False
Direct callers:
  - fs/namespace.c:attach_recursive_mnt
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff8130b270-ffffffff8130b326: mnt_change_mountpoint (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
