# Function: <code>timestamp_truncate</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc660)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff812fc660-ffffffff812fc6ff: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8133578d)
Location: fs/inode.c:2250
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81335070-ffffffff8133510f: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8134110d)
Location: fs/inode.c:2251
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff813409e0-ffffffff81340a7f: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81347508)
Location: fs/inode.c:2277
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81346eb0-ffffffff81346f4f: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81394f68)
Location: fs/inode.c:2282
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81394910-ffffffff813949af: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417349)
Location: fs/inode.c:2363
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81416ad0-ffffffff81416b81: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a28e9)
Location: fs/inode.c:2412
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff814a1f60-ffffffff814a2010: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d7a29)
Location: fs/inode.c:2457
Inline: True
Inline callers:
  - fs/inode.c:current_time
Direct callers:
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff814d70f0-ffffffff814d71a0: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509470)
Location: fs/inode.c:2460
Inline: True
Direct callers:
  - fs/inode.c:inode_needs_update_time
  - fs/inode.c:inode_update_timestamps
  - fs/inode.c:inode_update_timestamps
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81509470-ffffffff81509520: timestamp_truncate (STB_GLOBAL)
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac0a0)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffff8000103ac0a0-ffff8000103ac188: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c780)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
c058c780-c058c898: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a75b0)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
c0000000004a75b0-c0000000004a76c8: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027164a)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffe00027164a-ffffffe000271708: timestamp_truncate (STB_GLOBAL)
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
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4c40)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff812f4c40-ffffffff812f4cdf: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5860)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff812e5860-ffffffff812e58ff: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2a50)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff812f2a50-ffffffff812f2aef: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct timespec64 timestamp_truncate(struct timespec64 t, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304160)
Location: fs/inode.c:2190
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:notify_change
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81304160-ffffffff813041ff: timestamp_truncate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
