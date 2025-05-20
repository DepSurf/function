# Function: <code>__writeback_inodes_sb_nr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81239bc0)
Location: fs/fs-writeback.c:2204
Inline: False
Direct callers:
  - fs/fs-writeback.c:writeback_inodes_sb
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
```
**Symbols:**

```
ffffffff81239bc0-ffffffff81239c92: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81261b80)
Location: fs/fs-writeback.c:2283
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff81261b80-ffffffff81261c54: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81275080)
Location: fs/fs-writeback.c:2281
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff81275080-ffffffff81275154: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812825e0)
Location: fs/fs-writeback.c:2290
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb_nr
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812825e0-ffffffff812826a2: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a5160)
Location: fs/fs-writeback.c:2323
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812a5160-ffffffff812a5222: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812cc020)
Location: fs/fs-writeback.c:2321
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812cc020-ffffffff812cc0e2: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e0f60)
Location: fs/fs-writeback.c:2347
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812e0f60-ffffffff812e1022: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs-writeback.c (0)
Location: fs/fs-writeback.c:2362
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812ff660-ffffffff812ff72a: __writeback_inodes_sb_nr (STB_LOCAL)
ffffffff81302405-ffffffff81302425: __writeback_inodes_sb_nr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81314570)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff81314570-ffffffff81314638: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134e090)
Location: fs/fs-writeback.c:2459
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8134e090-ffffffff8134e14e: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135af40)
Location: fs/fs-writeback.c:2452
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8135af40-ffffffff8135affe: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81361b40)
Location: fs/fs-writeback.c:2453
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff81361b40-ffffffff81361bfe: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b01a0)
Location: fs/fs-writeback.c:2593
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff813b01a0-ffffffff813b025e: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81434db0)
Location: fs/fs-writeback.c:2588
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff81434db0-ffffffff81434e7c: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c2dc0)
Location: fs/fs-writeback.c:2620
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff814c2dc0-ffffffff814c2e8c: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f81a0)
Location: fs/fs-writeback.c:2631
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff814f81a0-ffffffff814f826c: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152c920)
Location: fs/fs-writeback.c:2653
Inline: True
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8152c920-ffffffff8152c9ec: __writeback_inodes_sb_nr (STB_LOCAL)
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
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103ca3b0)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffff8000103ca3b0-ffff8000103ca490: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a69f0)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
c05a69f0-c05a6ae0: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cbcf0)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
c0000000004cbcf0-c0000000004cbde0: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe00028861a)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffe00028861a-ffffffe0002886be: __writeback_inodes_sb_nr (STB_LOCAL)
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
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130cb50)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8130cb50-ffffffff8130cc18: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fd770)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff812fd770-ffffffff812fd838: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130a940)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8130a940-ffffffff8130aa08: __writeback_inodes_sb_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __writeback_inodes_sb_nr(struct super_block *sb, long unsigned int nr, enum wb_reason reason, bool skip_if_busy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131c070)
Location: fs/fs-writeback.c:2450
Inline: False
Direct callers:
  - fs/fs-writeback.c:try_to_writeback_inodes_sb
  - fs/fs-writeback.c:writeback_inodes_sb
```
**Symbols:**

```
ffffffff8131c070-ffffffff8131c138: __writeback_inodes_sb_nr (STB_LOCAL)
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
