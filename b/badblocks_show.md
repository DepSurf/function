# Function: <code>badblocks_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168fd20)
Location: drivers/md/md.c:8913
Inline: False
Direct callers:
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8168fd20-ffffffff8168fe1c: badblocks_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81412f80)
Location: block/badblocks.c:450
Inline: False
Direct callers:
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff81412f80-ffffffff8141307d: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8142e4b0)
Location: block/badblocks.c:475
Inline: False
Direct callers:
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8142e4b0-ffffffff8142e5ad: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8143b7b0)
Location: block/badblocks.c:475
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8143b7b0-ffffffff8143b8b6: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814677c0)
Location: block/badblocks.c:475
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814677c0-ffffffff814678c6: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8149b630)
Location: block/badblocks.c:475
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8149b630-ffffffff8149b73e: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814b5940)
Location: block/badblocks.c:475
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814b5940-ffffffff814b5a4e: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e3e80)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814e3e80-ffffffff814e3f94: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814fd240)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814fd240-ffffffff814fd354: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8155c6b0)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8155c6b0-ffffffff8155c7b9: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81578800)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff81578800-ffffffff81578904: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81580550)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff81580550-ffffffff81580654: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff81cd8a84-ffffffff81cd8afa: badblocks_show.cold (STB_LOCAL)
ffffffff815e5870-ffffffff815e5973: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:465
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff81e8c4ed-ffffffff81e8c567: badblocks_show.cold (STB_LOCAL)
ffffffff81694940-ffffffff81694a66: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:465
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8207695f-ffffffff820769d9: badblocks_show.cold (STB_LOCAL)
ffffffff817534a0-ffffffff817535c6: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:465
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff820f67df-ffffffff820f6832: badblocks_show.cold (STB_LOCAL)
ffffffff8178f660-ffffffff8178f787: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/badblocks.c (0)
Location: block/badblocks.c:1497
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff821d3cb6-ffffffff821d3d09: badblocks_show.cold (STB_LOCAL)
ffffffff817d1dc0-ffffffff817d1ee7: badblocks_show (STB_GLOBAL)
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
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffff8000105fe550)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffff8000105fe550-ffff8000105fe66c: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c07a9ff8)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
c07a9ff8-c07aa164: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c000000000798c40)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
c000000000798c40-c000000000798dbc: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffe00043a408)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffe00043a408-ffffffe00043a4ee: badblocks_show (STB_GLOBAL)
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
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f5820)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814f5820-ffffffff814f5934: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e5d30)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814e5d30-ffffffff814e5e44: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f18b0)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff814f18b0-ffffffff814f19c4: badblocks_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t badblocks_show(struct badblocks *bb, char *page, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8150a910)
Location: block/badblocks.c:467
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:region_badblocks_show
  - drivers/md/md.c:ubb_show
  - drivers/md/md.c:bb_show
```
**Symbols:**

```
ffffffff8150a910-ffffffff8150aa24: badblocks_show (STB_GLOBAL)
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
