# Function: <code>atime_needs_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81229060)
Location: fs/inode.c:1606
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81229060-ffffffff81229117: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81251760)
Location: fs/inode.c:1616
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/namei.c:link_path_walk
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81251760-ffffffff8125182f: atime_needs_update (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cfdf0)
Location: fs/inode.c:1680
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812cfdf0-ffffffff812cfec4: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ecd40)
Location: fs/inode.c:1693
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812ecd40-ffffffff812ece10: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fe8d0)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812fe8d0-ffffffff812fe9a0: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81337970)
Location: fs/inode.c:1788
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81337970-ffffffff81337a40: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813432b0)
Location: fs/inode.c:1789
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff813432b0-ffffffff81343380: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81349570)
Location: fs/inode.c:1797
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81349570-ffffffff81349666: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813972c0)
Location: fs/inode.c:1802
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff813972c0-ffffffff813973b6: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814193e0)
Location: fs/inode.c:1883
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814193e0-ffffffff8141955b: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a4e10)
Location: fs/inode.c:1885
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814a4e10-ffffffff814a4f8f: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814da0f0)
Location: fs/inode.c:1929
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff814da0f0-ffffffff814da20c: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150c720)
Location: fs/inode.c:1932
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff8150c720-ffffffff8150c83f: atime_needs_update (STB_GLOBAL)
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
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103af790)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffff8000103af790-ffff8000103af8b0: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058f500)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c058f500-c058f694: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004ab2f0)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
c0000000004ab2f0-c0000000004ab480: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027421a)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffe00027421a-ffffffe000274302: atime_needs_update (STB_GLOBAL)
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
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f6eb0)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f6eb0-ffffffff812f6f80: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e7ad0)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812e7ad0-ffffffff812e7ba0: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4cc0)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff812f4cc0-ffffffff812f4d90: atime_needs_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool atime_needs_update(const struct path *path, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81305e50)
Location: fs/inode.c:1704
Inline: False
Direct callers:
  - fs/namei.c:trailing_symlink
  - fs/inode.c:touch_atime
```
**Symbols:**

```
ffffffff81305e50-ffffffff81305f20: atime_needs_update (STB_GLOBAL)
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
