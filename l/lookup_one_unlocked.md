# Function: <code>lookup_one_unlocked</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lookup_one_unlocked(struct user_namespace *mnt_userns, const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401de5)
Location: fs/namei.c:2779
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff81401c40-ffffffff81401cf3: lookup_one_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lookup_one_unlocked(struct user_namespace *mnt_userns, const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148bf65)
Location: fs/namei.c:2758
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff8148bd90-ffffffff8148be43: lookup_one_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lookup_one_unlocked(struct mnt_idmap *idmap, const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c1805)
Location: fs/namei.c:2789
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff814c0890-ffffffff814c0943: lookup_one_unlocked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *lookup_one_unlocked(struct mnt_idmap *idmap, const char *name, struct dentry *base, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3cc5)
Location: fs/namei.c:2806
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
Direct callers:
  - fs/namei.c:lookup_positive_unlocked
  - fs/exportfs/expfs.c:reconnect_one
```
**Symbols:**

```
ffffffff814f2d70-ffffffff814f2e23: lookup_one_unlocked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
