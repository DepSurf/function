# Function: <code>dquot_add_inodes</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e3f30)
Location: fs/quota/dquot.c:1258
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff812e3f30-ffffffff812e40a3: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81310770)
Location: fs/quota/dquot.c:1255
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff81310770-ffffffff813108e0: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81327990)
Location: fs/quota/dquot.c:1255
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff81327990-ffffffff81327b00: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134f4d0)
Location: fs/quota/dquot.c:1265
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff8134f4d0-ffffffff8134f650: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813677e0)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff813677e0-ffffffff81367960: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b0060)
Location: fs/quota/dquot.c:1265
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813b0060-ffffffff813b0249: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c1660)
Location: fs/quota/dquot.c:1266
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813c1660-ffffffff813c1849: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c7df0)
Location: fs/quota/dquot.c:1264
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff813c7df0-ffffffff813c7fd9: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1269
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
```
**Symbols:**

```
ffffffff81418430-ffffffff8141868b: dquot_add_inodes (STB_LOCAL)
ffffffff81cc7cf9-ffffffff81cc7d18: dquot_add_inodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1279
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff81492c80-ffffffff81492ec6: dquot_add_inodes (STB_LOCAL)
ffffffff81e7aa58-ffffffff81e7aa77: dquot_add_inodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1279
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff81526920-ffffffff81526b66: dquot_add_inodes (STB_LOCAL)
ffffffff8206b96c-ffffffff8206b98b: dquot_add_inodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1337
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff8155edf0-ffffffff8155f02e: dquot_add_inodes (STB_LOCAL)
ffffffff820eb820-ffffffff820eb839: dquot_add_inodes.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1291
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff815954e0-ffffffff8159571e: dquot_add_inodes (STB_LOCAL)
ffffffff821c8a4a-ffffffff821c8a63: dquot_add_inodes.cold (STB_LOCAL)
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
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff80001042f810)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffff80001042f810-ffff80001042f9cc: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f821c)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
c05f821c-c05f8408: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000540610)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
c000000000540610-c000000000540878: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cb90e)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffe0002cb90e-ffffffe0002cba66: dquot_add_inodes (STB_LOCAL)
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
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135fdc0)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff8135fdc0-ffffffff8135ff40: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81350a60)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff81350a60-ffffffff81350be0: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135d890)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff8135d890-ffffffff8135da10: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dquot_add_inodes(struct dquot *dquot, qsize_t inodes, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813714c0)
Location: fs/quota/dquot.c:1267
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:dquot_alloc_inode
```
**Symbols:**

```
ffffffff813714c0-ffffffff8137163e: dquot_add_inodes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
