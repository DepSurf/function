# Function: <code>squashfs_readpage_block</code>

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
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff81324cb0)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81324cb0-ffffffff8132534a: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8133ab10)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8133ab10-ffffffff8133b198: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8134f780)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8134f780-ffffffff8134fcd6: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff81373e30)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81373e30-ffffffff81374453: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813a2e3f-ffffffff813a2e6a: squashfs_readpage_block.cold.6 (STB_LOCAL)
ffffffff813a28e0-ffffffff813a2e3f: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:27
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813bbc3e-ffffffff813bbc6d: squashfs_readpage_block.cold.6 (STB_LOCAL)
ffffffff813bb6c0-ffffffff813bbc3e: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e64d4-ffffffff813e650b: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff813e5f60-ffffffff813e64d4: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8140054a-ffffffff81400581: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff813fffc0-ffffffff8140054a: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8144dae0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8144dae0-ffffffff8144df6d: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffff8146a0a0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8146a0a0-ffffffff8146a524: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81bdf6d7-ffffffff81bdf70b: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff8146f670-ffffffff8146fbe5: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff81ccf1e7-ffffffff81ccf23a: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff814c60d0-ffffffff814c6652: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff81e82290-ffffffff81e822dd: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff81551090-ffffffff81551791: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:22
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff82071725-ffffffff82071744: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff815f2230-ffffffff815f276e: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:22
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff820f13be-ffffffff820f13dd: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff8162a320-ffffffff8162a85e: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:22
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_read_folio
```
**Symbols:**

```
ffffffff821ce660-ffffffff821ce67f: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff81663640-ffffffff81663b79: squashfs_readpage_block (STB_GLOBAL)
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
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffff8000104de008)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffff8000104de008-ffff8000104de514: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (c069fbe0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c069fbe0-c06a012c: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (c000000000619c80)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
c000000000619c80-c00000000061a448: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/file_direct.c (ffffffe000352a0e)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffe000352a0e-ffffffe000352e70: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f8b2a-ffffffff813f8b61: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff813f85a0-ffffffff813f8b2a: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813e95aa-ffffffff813e95e1: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff813e9020-ffffffff813e95aa: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff813f5eaa-ffffffff813f5ee1: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff813f5920-ffffffff813f5eaa: squashfs_readpage_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int squashfs_readpage_block(struct page *target_page, u64 block, int bsize, int expected);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/file_direct.c (0)
Location: fs/squashfs/file_direct.c:25
Inline: False
Direct callers:
  - fs/squashfs/file.c:squashfs_readpage
```
**Symbols:**

```
ffffffff8140bb0d-ffffffff8140bb44: squashfs_readpage_block.cold (STB_LOCAL)
ffffffff8140b570-ffffffff8140bb0d: squashfs_readpage_block (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int expected</code>
</li>
</ul>
</details>
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
