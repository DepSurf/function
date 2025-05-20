# Function: <code>alloc_vfsmnt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122c420)
Location: fs/namespace.c:201
Inline: False
Direct callers:
  - fs/namespace.c:vfs_kern_mount
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff8122c420-ffffffff8122c637: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81254bb0)
Location: fs/namespace.c:201
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
```
**Symbols:**

```
ffffffff81254bb0-ffffffff81254dca: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268110)
Location: fs/namespace.c:200
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_kern_mount
```
**Symbols:**

```
ffffffff81268110-ffffffff8126832a: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812755c0)
Location: fs/namespace.c:203
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff812755c0-ffffffff812757e2: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81297e80)
Location: fs/namespace.c:203
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff81297e80-ffffffff812980a2: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bde10)
Location: fs/namespace.c:203
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff812bde10-ffffffff812be03e: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d29e0)
Location: fs/namespace.c:178
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
```
**Symbols:**

```
ffffffff812d29e0-ffffffff812d2bbe: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efbb0)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff812efbb0-ffffffff812efd70: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301680)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff81301680-ffffffff81301840: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a740)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff8133a740-ffffffff8133a900: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346350)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff81346350-ffffffff81346510: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134c760)
Location: fs/namespace.c:195
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff8134c760-ffffffff8134c929: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139a5e0)
Location: fs/namespace.c:195
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff8139a5e0-ffffffff8139a7a9: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141d300)
Location: fs/namespace.c:196
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff8141d300-ffffffff8141d4a6: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814a9650)
Location: fs/namespace.c:311
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff814a9650-ffffffff814a97f6: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814de5a0)
Location: fs/namespace.c:197
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff814de5a0-ffffffff814de746: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81511030)
Location: fs/namespace.c:202
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff81511030-ffffffff815111ef: alloc_vfsmnt (STB_LOCAL)
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
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b3d70)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffff8000103b3d70-ffff8000103b3ed0: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592c7c)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
c0592c7c-c0592dd8: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004afad0)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
c0000000004afad0-c0000000004afca4: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe0002775f4)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffe0002775f4-ffffffe00027773e: alloc_vfsmnt (STB_LOCAL)
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
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9c60)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff812f9c60-ffffffff812f9e20: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea880)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff812ea880-ffffffff812eaa40: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7a50)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff812f7a50-ffffffff812f7c10: alloc_vfsmnt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mount *alloc_vfsmnt(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308d90)
Location: fs/namespace.c:175
Inline: False
Direct callers:
  - fs/namespace.c:clone_mnt
  - fs/namespace.c:vfs_create_mount
```
**Symbols:**

```
ffffffff81308d90-ffffffff81308f50: alloc_vfsmnt (STB_LOCAL)
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
