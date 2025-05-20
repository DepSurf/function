# Function: <code>dput_to_list</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff812e9e5b-ffffffff812e9e6e: dput_to_list.cold (STB_LOCAL)
ffffffff812e8810-ffffffff812e8956: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fa3a0)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff812fa3a0-ffffffff812fa4fa: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333440)
Location: fs/dcache.c:897
Inline: False
```
**Symbols:**

```
ffffffff81333440-ffffffff8133359e: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133eda0)
Location: fs/dcache.c:904
Inline: False
```
**Symbols:**

```
ffffffff8133eda0-ffffffff8133ef08: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81345180)
Location: fs/dcache.c:907
Inline: False
```
**Symbols:**

```
ffffffff81345180-ffffffff813452e8: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392d10)
Location: fs/dcache.c:907
Inline: False
```
**Symbols:**

```
ffffffff81392d10-ffffffff81392e78: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414410)
Location: fs/dcache.c:932
Inline: False
```
**Symbols:**

```
ffffffff81414410-ffffffff81414573: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f8c0)
Location: fs/dcache.c:932
Inline: False
```
**Symbols:**

```
ffffffff8149f8c0-ffffffff8149fa23: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4be0)
Location: fs/dcache.c:932
Inline: False
```
**Symbols:**

```
ffffffff814d4be0-ffffffff814d4d43: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506f20)
Location: fs/dcache.c:869
Inline: False
```
**Symbols:**

```
ffffffff81506f20-ffffffff8150703a: dput_to_list (STB_GLOBAL)
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
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a9348)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffff8000103a9348-ffff8000103a9550: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058a658)
Location: fs/dcache.c:878
Inline: False
```
**Symbols:**

```
c058a658-c058a7f0: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a3d40)
Location: fs/dcache.c:878
Inline: False
```
**Symbols:**

```
c0000000004a3d40-c0000000004a3fe0: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026f376)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffe00026f376-ffffffe00026f50e: dput_to_list (STB_GLOBAL)
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
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f2980)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff812f2980-ffffffff812f2ada: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e35b0)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff812e35b0-ffffffff812e370a: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0790)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff812f0790-ffffffff812f08ea: dput_to_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dput_to_list(struct dentry *dentry, struct list_head *list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81301950)
Location: fs/dcache.c:878
Inline: False
Direct callers:
  - fs/namespace.c:__put_mountpoint
```
**Symbols:**

```
ffffffff81301950-ffffffff81301a9f: dput_to_list (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
