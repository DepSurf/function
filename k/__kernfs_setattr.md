# Function: <code>__kernfs_setattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81288c70)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
**Symbols:**

```
ffffffff81288c70-ffffffff81288d24: __kernfs_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812b6160)
Location: fs/kernfs/inode.c:69
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
**Symbols:**

```
ffffffff812b6160-ffffffff812b6214: __kernfs_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812cb9f0)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
**Symbols:**

```
ffffffff812cb9f0-ffffffff812cbaa4: __kernfs_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812d8e40)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
**Symbols:**

```
ffffffff812d8e40-ffffffff812d8ef8: __kernfs_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff812fd6a0)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
```
**Symbols:**

```
ffffffff812fd6a0-ffffffff812fd758: __kernfs_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8132b550)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8132b550-ffffffff8132b5fe: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813428b0)
Location: fs/kernfs/inode.c:66
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff813428b0-ffffffff8134295e: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136aa00)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8136aa00-ffffffff8136aaa2: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81382bc0)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81382bc0-ffffffff81382c62: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813cd650)
Location: fs/kernfs/inode.c:74
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff813cd650-ffffffff813cd6ef: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813df280)
Location: fs/kernfs/inode.c:74
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff813df280-ffffffff813df31f: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff813e5e40)
Location: fs/kernfs/inode.c:74
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff813e5e40-ffffffff813e5edf: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81437a40)
Location: fs/kernfs/inode.c:68
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81437a40-ffffffff81437adf: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff814b2770)
Location: fs/kernfs/inode.c:68
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff814b2770-ffffffff814b281a: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81549320)
Location: fs/kernfs/inode.c:68
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81549320-ffffffff815493ca: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81580f00)
Location: fs/kernfs/inode.c:68
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81580f00-ffffffff81580faa: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff815b99b0)
Location: fs/kernfs/inode.c:68
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff815b99b0-ffffffff815b9a5a: __kernfs_setattr (STB_GLOBAL)
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
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffff8000104510a0)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffff8000104510a0-ffff800010451138: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c0614088)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
c0614088-c0614128: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (c000000000569630)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
c000000000569630-c000000000569718: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffe0002e3f72)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffe0002e3f72-ffffffe0002e4010: __kernfs_setattr (STB_GLOBAL)
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
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8137b1a0)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8137b1a0-ffffffff8137b242: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8136bc70)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8136bc70-ffffffff8136bd12: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff81378c70)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff81378c70-ffffffff81378d12: __kernfs_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __kernfs_setattr(struct kernfs_node *kn, const struct iattr *iattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/inode.c (ffffffff8138c720)
Location: fs/kernfs/inode.c:72
Inline: False
Direct callers:
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/kernfs/inode.c:kernfs_setattr
  - fs/kernfs/dir.c:__kernfs_new_node
```
**Symbols:**

```
ffffffff8138c720-ffffffff8138c7c2: __kernfs_setattr (STB_GLOBAL)
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
