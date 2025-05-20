# Function: <code>badblocks_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168fbc0)
Location: drivers/md/md.c:8954
Inline: False
Direct callers:
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8168fbc0-ffffffff8168fca0: badblocks_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81413080)
Location: block/badblocks.c:500
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff81413080-ffffffff8141312e: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8142e5b0)
Location: block/badblocks.c:525
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8142e5b0-ffffffff8142e65e: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8143b8c0)
Location: block/badblocks.c:525
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8143b8c0-ffffffff8143b965: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814678d0)
Location: block/badblocks.c:525
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814678d0-ffffffff81467975: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8149b740)
Location: block/badblocks.c:525
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8149b740-ffffffff8149b7ef: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814b5a50)
Location: block/badblocks.c:525
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814b5a50-ffffffff814b5aff: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e3fa0)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814e3fa0-ffffffff814e404f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814fd360)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814fd360-ffffffff814fd40f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8155c7c0)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8155c7c0-ffffffff8155c86f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81578910)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff81578910-ffffffff815789bf: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81580660)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff81580660-ffffffff8158070f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff815e5980)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff815e5980-ffffffff815e5a2f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81694a70)
Location: block/badblocks.c:515
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff81694a70-ffffffff81694b41: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff81753ad0)
Location: block/badblocks.c:515
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff81753ad0-ffffffff81753ba1: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8178fc80)
Location: block/badblocks.c:515
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8178fc80-ffffffff8178fd53: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff817d3a20)
Location: block/badblocks.c:1547
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff817d3a20-ffffffff817d3af3: badblocks_store (STB_GLOBAL)
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
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffff8000105febc0)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffff8000105febc0-ffff8000105fec98: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c07aa164)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
```
**Symbols:**

```
c07aa164-c07aa238: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (c000000000798dc0)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
c000000000798dc0-c000000000798eb8: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffe00043a4ee)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffe00043a4ee-ffffffe00043a57e: badblocks_store (STB_GLOBAL)
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
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f5940)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814f5940-ffffffff814f59ef: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814e5e50)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814e5e50-ffffffff814e5eff: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff814f19d0)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff814f19d0-ffffffff814f1a7f: badblocks_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t badblocks_store(struct badblocks *bb, const char *page, size_t len, int unack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/badblocks.c (ffffffff8150aa30)
Location: block/badblocks.c:517
Inline: False
Direct callers:
  - block/genhd.c:disk_badblocks_store
  - drivers/md/md.c:ubb_store
  - drivers/md/md.c:bb_store
```
**Symbols:**

```
ffffffff8150aa30-ffffffff8150aadf: badblocks_store (STB_GLOBAL)
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
