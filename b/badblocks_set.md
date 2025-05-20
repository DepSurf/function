# Function: <code>badblocks_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81412850)
Location: block/badblocks.c:151
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81412850-ffffffff81412ccd: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8142dcb0)
Location: block/badblocks.c:171
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff8142dcb0-ffffffff8142e191: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8143aff0)
Location: block/badblocks.c:171
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff8143aff0-ffffffff8143b4a1: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81467010)
Location: block/badblocks.c:171
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81467010-ffffffff814674bf: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8149ae90)
Location: block/badblocks.c:171
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff8149ae90-ffffffff8149b322: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814b51a0)
Location: block/badblocks.c:171
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814b51a0-ffffffff814b5632: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e3710)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814e3710-ffffffff814e3b75: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814fcad0)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814fcad0-ffffffff814fcf35: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8155c240)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff8155c240-ffffffff8155c6a8: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81578390)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81578390-ffffffff815787f9: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81580110)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81580110-ffffffff81580544: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81cd8a14-ffffffff81cd8a84: badblocks_set.cold (STB_LOCAL)
ffffffff815e5410-ffffffff815e586c: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:162
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff81e8c47b-ffffffff81e8c4ed: badblocks_set.cold (STB_LOCAL)
ffffffff816944d0-ffffffff81694938: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:162
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff820769d9-ffffffff82076a41: badblocks_set.cold (STB_LOCAL)
ffffffff81753650-ffffffff81753abf: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:162
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff820f6832-ffffffff820f688a: badblocks_set.cold (STB_LOCAL)
ffffffff8178f810-ffffffff8178fc6a: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff817d3ac2)
Location: block/badblocks.c:1429
Inline: True
Inline callers:
  - block/badblocks.c:badblocks_store
Direct callers:
  - drivers/nvdimm/badrange.c:set_badblock
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff817d39f0-ffffffff817d3a0c: badblocks_set (STB_GLOBAL)
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
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffff8000105fe748)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffff8000105fe748-ffff8000105febc0: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c07a94dc)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
c07a94dc-c07a9b84: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c000000000798250)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
c000000000798250-c00000000079884c: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffe000439d76)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffe000439d76-ffffffe00043a16a: badblocks_set (STB_GLOBAL)
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
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f50b0)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814f50b0-ffffffff814f5515: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e55c0)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814e55c0-ffffffff814e5a25: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f1140)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff814f1140-ffffffff814f15a5: badblocks_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int badblocks_set(struct badblocks *bb, sector_t s, int sectors, int acknowledged);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8150a1a0)
Location: block/badblocks.c:163
Inline: False
Direct callers:
  - block/badblocks.c:badblocks_store
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:super_1_load
```
**Symbols:**

```
ffffffff8150a1a0-ffffffff8150a605: badblocks_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
