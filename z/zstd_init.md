# Function: <code>zstd_init</code>

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
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81375c60)
Location: fs/squashfs/zstd_wrapper.c:38
Inline: False
```
**Symbols:**

```
ffffffff81375c60-ffffffff81375ce7: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:38
Inline: False
```
**Symbols:**

```
ffffffff813a4660-ffffffff813a46d2: zstd_init (STB_LOCAL)
ffffffff813a46e5-ffffffff813a4705: zstd_init.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:38
Inline: False
```
**Symbols:**

```
ffffffff813bd460-ffffffff813bd4d2: zstd_init (STB_LOCAL)
ffffffff813bd4e5-ffffffff813bd505: zstd_init.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff813e7d20-ffffffff813e7d93: zstd_init (STB_LOCAL)
ffffffff813e7da6-ffffffff813e7dc6: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff81401da0-ffffffff81401e13: zstd_init (STB_LOCAL)
ffffffff81401e26-ffffffff81401e46: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff8144f990-ffffffff8144fa03: zstd_init (STB_LOCAL)
ffffffff8144fa40-ffffffff8144fa60: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff8146bef0-ffffffff8146bf63: zstd_init (STB_LOCAL)
ffffffff81bed6e6-ffffffff81bed706: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff81471580-ffffffff814715ef: zstd_init (STB_LOCAL)
ffffffff81bdf7e9-ffffffff81bdf809: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff814c8010-ffffffff814c807f: zstd_init (STB_LOCAL)
ffffffff81ccf39a-ffffffff81ccf3ba: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff815534d0-ffffffff81553548: zstd_init (STB_LOCAL)
ffffffff81e8241b-ffffffff81e8243b: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff815f4c40)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff815f4c40-ffffffff815f4ccd: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff8162ccc0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff8162ccc0-ffffffff8162cd4d: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81666180)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff81666180-ffffffff8166623d: zstd_init (STB_LOCAL)
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
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffff8000104dfde8)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffff8000104dfde8-ffff8000104dfe70: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c06a1994)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
c06a1994-c06a1a18: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c00000000061c7a0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
c00000000061c7a0-c00000000061c860: zstd_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffe0003543a6)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffe0003543a6-ffffffe00035442a: zstd_init (STB_LOCAL)
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
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff813fa380-ffffffff813fa3f3: zstd_init (STB_LOCAL)
ffffffff813fa406-ffffffff813fa426: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff813eae00-ffffffff813eae73: zstd_init (STB_LOCAL)
ffffffff813eae86-ffffffff813eaea6: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff813f7700-ffffffff813f7773: zstd_init (STB_LOCAL)
ffffffff813f7786-ffffffff813f77a6: zstd_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *zstd_init(struct squashfs_sb_info *msblk, void *buff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: fs/squashfs/zstd_wrapper.c:29
Inline: False
```
**Symbols:**

```
ffffffff8140d390-ffffffff8140d403: zstd_init (STB_LOCAL)
ffffffff8140d416-ffffffff8140d436: zstd_init.cold (STB_LOCAL)
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
