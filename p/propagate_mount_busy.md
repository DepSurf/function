# Function: <code>propagate_mount_busy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8123d1f0)
Location: fs/pnode.c:337
Inline: False
Direct callers:
  - fs/namespace.c:may_umount
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff8123d1f0-ffffffff8123d309: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812652c0)
Location: fs/pnode.c:345
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812652c0-ffffffff812653df: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812786f0)
Location: fs/pnode.c:358
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812786f0-ffffffff81278856: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81285a20)
Location: fs/pnode.c:376
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff81285a20-ffffffff81285b88: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812a84a0)
Location: fs/pnode.c:376
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812a84a0-ffffffff812a8608: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812cf040)
Location: fs/pnode.c:376
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812cf040-ffffffff812cf197: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812e43b0)
Location: fs/pnode.c:377
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812e43b0-ffffffff812e4507: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81302ba0)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff81302ba0-ffffffff81302cfe: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81315c20)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff81315c20-ffffffff81315d7e: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8134f5f0)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8134f5f0-ffffffff8134f788: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8135c4b0)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:shrink_submounts
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8135c4b0-ffffffff8135c5a0: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81362f70)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff81362f70-ffffffff81363060: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff813b1770)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff813b1770-ffffffff813b1860: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81436700)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff81436700-ffffffff814367f9: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff814c4740)
Location: fs/pnode.c:369
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff814c4740-ffffffff814c4839: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff814f9bc0)
Location: fs/pnode.c:407
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff814f9bc0-ffffffff814f9cb9: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8152e420)
Location: fs/pnode.c:407
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8152e420-ffffffff8152e519: propagate_mount_busy (STB_GLOBAL)
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
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffff8000103cc668)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffff8000103cc668-ffff8000103cc7c4: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (c05a81ec)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
c05a81ec-c05a8350: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (c0000000004cddc0)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
c0000000004cddc0-c0000000004cdfc8: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffe000289b5e)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffe000289b5e-ffffffe000289c78: propagate_mount_busy (STB_GLOBAL)
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
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8130e200)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8130e200-ffffffff8130e35e: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff812fee10)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff812fee10-ffffffff812fef6e: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8130bff0)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8130bff0-ffffffff8130c14e: propagate_mount_busy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int propagate_mount_busy(struct mount *mnt, int refcnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8131d820)
Location: fs/pnode.c:370
Inline: False
Direct callers:
  - fs/namespace.c:mark_mounts_for_expiry
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:ksys_umount
  - fs/namespace.c:may_umount
```
**Symbols:**

```
ffffffff8131d820-ffffffff8131d97e: propagate_mount_busy (STB_GLOBAL)
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
