# Function: <code>find_acceptable_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8130c7e0)
Location: fs/exportfs/expfs.c:41
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8130c7e0-ffffffff8130c8bb: find_acceptable_alias.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81340fc8)
Location: fs/exportfs/expfs.c:41
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81340ab0-ffffffff81340b87: find_acceptable_alias.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81356830)
Location: fs/exportfs/expfs.c:41
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81356830-ffffffff81356924: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8136b7d0)
Location: fs/exportfs/expfs.c:42
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8136b7d0-ffffffff8136b8c6: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8139052d)
Location: fs/exportfs/expfs.c:42
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81390360-ffffffff8139043b: find_acceptable_alias.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813bf5d0)
Location: fs/exportfs/expfs.c:42
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff813bf120-ffffffff813bf1fb: find_acceptable_alias.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff813d8760)
Location: fs/exportfs/expfs.c:42
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff813d8760-ffffffff813d8858: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81403120)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81403120-ffffffff81403221: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8141d030)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8141d030-ffffffff8141d131: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8146c074)
Location: fs/exportfs/expfs.c:43
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff8146bbc0-ffffffff8146bca0: find_acceptable_alias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814867c3)
Location: fs/exportfs/expfs.c:43
Inline: True
Inline callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff81486310-ffffffff814863f0: find_acceptable_alias.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8148bef0)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff8148bef0-ffffffff8148bff1: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff814e3700)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff814e3700-ffffffff814e3801: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81571910)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff81571910-ffffffff81571a12: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81616c40)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff81616c40-ffffffff81616d42: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff8164ed20)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff8164ed20-ffffffff8164ee4a: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81688260)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
  - fs/exportfs/expfs.c:exportfs_decode_fh_raw
```
**Symbols:**

```
ffffffff81688260-ffffffff8168838a: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffff8000104fec90)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffff8000104fec90-ffff8000104fee70: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c06bbcf8)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
c06bbcf8-c06bbe10: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (c0000000006425b0)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
c0000000006425b0-c000000000642860: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffe00036cafe)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffe00036cafe-ffffffe00036cc56: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81415610)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81415610-ffffffff81415711: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81406090)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81406090-ffffffff81406191: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81412990)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81412990-ffffffff81412a91: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *find_acceptable_alias(struct dentry *result, int (*acceptable)(void *, struct dentry *), void *context);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exportfs/expfs.c (ffffffff81428600)
Location: fs/exportfs/expfs.c:43
Inline: True
Direct callers:
  - fs/exportfs/expfs.c:exportfs_decode_fh
  - fs/exportfs/expfs.c:exportfs_decode_fh
```
**Symbols:**

```
ffffffff81428600-ffffffff81428719: find_acceptable_alias (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
