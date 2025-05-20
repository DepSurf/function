# Function: <code>dquot_add_space</code>

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
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812e3d20)
Location: fs/quota/dquot.c:1303
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff812e3d20-ffffffff812e3f22: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813108e0)
Location: fs/quota/dquot.c:1300
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813108e0-ffffffff81310af0: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81327b00)
Location: fs/quota/dquot.c:1300
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81327b00-ffffffff81327d10: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8134f650)
Location: fs/quota/dquot.c:1310
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8134f650-ffffffff8134f867: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81367960)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81367960-ffffffff81367b77: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813b1c80)
Location: fs/quota/dquot.c:1310
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813b1c80-ffffffff813b1f07: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c3280)
Location: fs/quota/dquot.c:1311
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813c3280-ffffffff813c34e9: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813c9860)
Location: fs/quota/dquot.c:1309
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813c9860-ffffffff813c9acf: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1314
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8141a0e0-ffffffff8141a3f1: dquot_add_space (STB_LOCAL)
ffffffff81cc7e23-ffffffff81cc7e4a: dquot_add_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1324
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff814930f0-ffffffff81493417: dquot_add_space (STB_LOCAL)
ffffffff81e7aa77-ffffffff81e7aa9e: dquot_add_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1324
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81526db0-ffffffff815270d7: dquot_add_space (STB_LOCAL)
ffffffff8206b98b-ffffffff8206b9b2: dquot_add_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1382
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8155f270-ffffffff8155f5a6: dquot_add_space (STB_LOCAL)
ffffffff820eb839-ffffffff820eb852: dquot_add_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/quota/dquot.c (0)
Location: fs/quota/dquot.c:1336
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81595960-ffffffff81595c96: dquot_add_space (STB_LOCAL)
ffffffff821c8a63-ffffffff821c8a7c: dquot_add_space.cold (STB_LOCAL)
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
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffff800010432758)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffff800010432758-ffff8000104329ec: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c05f7f88)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
c05f7f88-c05f821c: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (c000000000540310)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
c000000000540310-c00000000054060c: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffe0002cba66)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffe0002cba66-ffffffe0002cbc10: dquot_add_space (STB_LOCAL)
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
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135ff40)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8135ff40-ffffffff81360157: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81350be0)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff81350be0-ffffffff81350df7: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8135da10)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff8135da10-ffffffff8135dc27: dquot_add_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dquot_add_space(struct dquot *dquot, qsize_t space, qsize_t rsv_space, unsigned int flags, struct dquot_warn *warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff813712a0)
Location: fs/quota/dquot.c:1312
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_transfer
  - fs/quota/dquot.c:__dquot_alloc_space
  - fs/quota/dquot.c:__dquot_alloc_space
```
**Symbols:**

```
ffffffff813712a0-ffffffff813714b5: dquot_add_space (STB_LOCAL)
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
