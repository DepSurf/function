# Function: <code>wait_sb_inodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81239e23)
Location: fs/fs-writeback.c:2144
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81261de9)
Location: fs/fs-writeback.c:2198
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812752e9)
Location: fs/fs-writeback.c:2196
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81282843)
Location: fs/fs-writeback.c:2205
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a5383)
Location: fs/fs-writeback.c:2238
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cc257)
Location: fs/fs-writeback.c:2236
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e11ae)
Location: fs/fs-writeback.c:2262
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ff90f)
Location: fs/fs-writeback.c:2277
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131482e)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_sb_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134b960)
Location: fs/fs-writeback.c:2374
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
**Symbols:**

```
ffffffff8134b960-ffffffff8134bb2c: wait_sb_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_sb_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81358880)
Location: fs/fs-writeback.c:2367
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
**Symbols:**

```
ffffffff81358880-ffffffff81358a5a: wait_sb_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_sb_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135f280)
Location: fs/fs-writeback.c:2368
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
**Symbols:**

```
ffffffff8135f280-ffffffff8135f45a: wait_sb_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_sb_inodes(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813ade90)
Location: fs/fs-writeback.c:2508
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
**Symbols:**

```
ffffffff813ade90-ffffffff813ae06a: wait_sb_inodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8143502e)
Location: fs/fs-writeback.c:2503
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c306e)
Location: fs/fs-writeback.c:2535
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f844e)
Location: fs/fs-writeback.c:2546
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152cbce)
Location: fs/fs-writeback.c:2568
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103ca694)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a6c90)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cc064)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe000288898)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130ce0e)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fda2e)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130abfe)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131c327)
Location: fs/fs-writeback.c:2365
Inline: True
Inline callers:
  - fs/fs-writeback.c:sync_inodes_sb
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
