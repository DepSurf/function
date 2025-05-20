# Function: <code>proc_lookupfd_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81281410)
Location: fs/proc/fd.c:209
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfd
  - fs/proc/fd.c:proc_lookupfdinfo
```
**Symbols:**

```
ffffffff81281410-ffffffff812814e9: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812ae4c0)
Location: fs/proc/fd.c:209
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff812ae4c0-ffffffff812ae5a4: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812c3ea0)
Location: fs/proc/fd.c:208
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff812c3ea0-ffffffff812c3f84: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812d1200)
Location: fs/proc/fd.c:198
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff812d1200-ffffffff812d1303: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff812f5990)
Location: fs/proc/fd.c:199
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff812f5990-ffffffff812f5a10: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81322fa0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff81322fa0-ffffffff8132305a: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8133a0f0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff8133a0f0-ffffffff8133a1aa: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81362290)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff81362290-ffffffff81362353: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff8137a4f0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff8137a4f0-ffffffff8137a5b3: proc_lookupfd_common (STB_LOCAL)
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
In fs/proc/fd.c (ffffffff813c37f9)
Location: fs/proc/fd.c:206
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813d57d0)
Location: fs/proc/fd.c:195
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff813d57d0-ffffffff813d58c3: proc_lookupfd_common (STB_LOCAL)
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
In fs/proc/fd.c (ffffffff813dc74a)
Location: fs/proc/fd.c:195
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
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
In fs/proc/fd.c (ffffffff8142dd3a)
Location: fs/proc/fd.c:209
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
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
In fs/proc/fd.c (ffffffff814a779a)
Location: fs/proc/fd.c:219
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
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
In fs/proc/fd.c (ffffffff8153cfba)
Location: fs/proc/fd.c:220
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
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
In fs/proc/fd.c (ffffffff8157528a)
Location: fs/proc/fd.c:221
Inline: True
Inline callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff815adb20)
Location: fs/proc/fd.c:223
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff815adb20-ffffffff815adc29: proc_lookupfd_common (STB_LOCAL)
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
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffff800010446818)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffff800010446818-ffff800010446908: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c060b918)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
c060b918-c060b9fc: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (c00000000055c6a0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
c00000000055c6a0-c00000000055c800: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffe0002dc7a2)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffe0002dc7a2-ffffffe0002dc86e: proc_lookupfd_common (STB_LOCAL)
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
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81372ad0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff81372ad0-ffffffff81372b93: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813635a0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff813635a0-ffffffff81363663: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff813705a0)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff813705a0-ffffffff81370663: proc_lookupfd_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *proc_lookupfd_common(struct inode *dir, struct dentry *dentry, instantiate_t *instantiate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/fd.c (ffffffff81383f70)
Location: fs/proc/fd.c:206
Inline: False
Direct callers:
  - fs/proc/fd.c:proc_lookupfdinfo
  - fs/proc/fd.c:proc_lookupfd
```
**Symbols:**

```
ffffffff81383f70-ffffffff81384033: proc_lookupfd_common (STB_LOCAL)
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
