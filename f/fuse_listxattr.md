# Function: <code>fuse_listxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81314290)
Location: fs/fuse/dir.c:1800
Inline: False
```
**Symbols:**

```
ffffffff81314290-ffffffff813143e0: fuse_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff813488f0)
Location: fs/fuse/dir.c:1828
Inline: False
```
**Symbols:**

```
ffffffff813488f0-ffffffff81348a40: fuse_listxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81367960)
Location: fs/fuse/xattr.c:132
Inline: False
```
**Symbols:**

```
ffffffff81367960-ffffffff81367b14: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8137bf20)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff8137bf20-ffffffff8137c0f0: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813a0dc0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff813a0dc0-ffffffff813a0f90: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813d01a0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff813d01a0-ffffffff813d0367: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff813e9710)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff813e9710-ffffffff813e98d7: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff81415b5c-ffffffff81415b68: fuse_listxattr.cold (STB_LOCAL)
ffffffff81415880-ffffffff81415a39: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff8142f9ac-ffffffff8142f9b8: fuse_listxattr.cold (STB_LOCAL)
ffffffff8142f6c0-ffffffff8142f872: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff8147f80c-ffffffff8147f818: fuse_listxattr.cold (STB_LOCAL)
ffffffff8147f530-ffffffff8147f6e2: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff81bef794-ffffffff81bef7a0: fuse_listxattr.cold (STB_LOCAL)
ffffffff8149abb0-ffffffff8149ad78: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:110
Inline: False
```
**Symbols:**

```
ffffffff81be183c-ffffffff81be1848: fuse_listxattr.cold (STB_LOCAL)
ffffffff8149fe00-ffffffff8149ffc2: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:110
Inline: False
```
**Symbols:**

```
ffffffff81cd233c-ffffffff81cd2348: fuse_listxattr.cold (STB_LOCAL)
ffffffff814f7e10-ffffffff814f7fd2: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:109
Inline: False
```
**Symbols:**

```
ffffffff81e85472-ffffffff81e8547e: fuse_listxattr.cold (STB_LOCAL)
ffffffff81587e60-ffffffff8158803f: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff8162e1c0)
Location: fs/fuse/xattr.c:109
Inline: False
```
**Symbols:**

```
ffffffff8162e1c0-ffffffff8162e3a7: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff81666400)
Location: fs/fuse/xattr.c:109
Inline: False
```
**Symbols:**

```
ffffffff81666400-ffffffff816665ec: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffff816a06e0)
Location: fs/fuse/xattr.c:109
Inline: False
```
**Symbols:**

```
ffffffff816a06e0-ffffffff816a08cc: fuse_listxattr (STB_GLOBAL)
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
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffff800010514070)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffff800010514070-ffff80001051421c: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c06ceed8)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
c06ceed8-c06cf088: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (c00000000065c270)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
c00000000065c270-c00000000065c4c0: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/xattr.c (ffffffe00037dce0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffe00037dce0-ffffffe00037de46: fuse_listxattr (STB_GLOBAL)
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
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff81427f8c-ffffffff81427f98: fuse_listxattr.cold (STB_LOCAL)
ffffffff81427ca0-ffffffff81427e52: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff81418a0c-ffffffff81418a18: fuse_listxattr.cold (STB_LOCAL)
ffffffff81418720-ffffffff814188d2: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff8142412c-ffffffff81424138: fuse_listxattr.cold (STB_LOCAL)
ffffffff81423e40-ffffffff81423ff2: fuse_listxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_listxattr(struct dentry *entry, char *list, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/xattr.c (0)
Location: fs/fuse/xattr.c:107
Inline: False
```
**Symbols:**

```
ffffffff8143af6c-ffffffff8143af78: fuse_listxattr.cold (STB_LOCAL)
ffffffff8143ac80-ffffffff8143ae32: fuse_listxattr (STB_GLOBAL)
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
