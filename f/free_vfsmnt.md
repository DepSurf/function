# Function: <code>free_vfsmnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122b9e0)
Location: fs/namespace.c:579
Inline: False
Direct callers:
  - fs/namespace.c:delayed_free_vfsmnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff8122b9e0-ffffffff8122ba14: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254150)
Location: fs/namespace.c:579
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81254150-ffffffff81254184: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81267490)
Location: fs/namespace.c:578
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81267490-ffffffff812674c4: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81274ce0)
Location: fs/namespace.c:579
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81274ce0-ffffffff81274d14: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297610)
Location: fs/namespace.c:639
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81297610-ffffffff81297644: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bd800)
Location: fs/namespace.c:640
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812bd800-ffffffff812bd834: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2ca0)
Location: fs/namespace.c:552
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812d2ca0-ffffffff812d2cd4: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efe40)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812efe40-ffffffff812efe77: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301910)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81301910-ffffffff81301947: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133bf77)
Location: fs/namespace.c:549
Inline: True
Inline callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81347e17)
Location: fs/namespace.c:549
Inline: True
Inline callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cda0)
Location: fs/namespace.c:558
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff8134cda0-ffffffff8134ce1f: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139ad10)
Location: fs/namespace.c:560
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff8139ad10-ffffffff8139ad8f: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e1a0)
Location: fs/namespace.c:603
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff8141e1a0-ffffffff8141e228: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aabb0)
Location: fs/namespace.c:718
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff814aabb0-ffffffff814aac6a: free_vfsmnt (STB_LOCAL)
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
In fs/namespace.c (ffffffff814e0757)
Location: fs/namespace.c:611
Inline: True
Inline callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
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
In fs/namespace.c (ffffffff81514017)
Location: fs/namespace.c:618
Inline: True
Inline callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
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
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b3fc0)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffff8000103b3fc0-ffff8000103b4004: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592ea4)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
c0592ea4-c0592ee4: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004afe40)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
c0000000004afe40-c0000000004afea4: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002777f2)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffe0002777f2-ffffffe000277838: free_vfsmnt (STB_LOCAL)
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
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9ef0)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812f9ef0-ffffffff812f9f27: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812eab10)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812eab10-ffffffff812eab47: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7ce0)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff812f7ce0-ffffffff812f7d17: free_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_vfsmnt(struct mount *mnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81309120)
Location: fs/namespace.c:549
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:delayed_free_vfsmnt
```
**Symbols:**

```
ffffffff81309120-ffffffff81309157: free_vfsmnt (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
