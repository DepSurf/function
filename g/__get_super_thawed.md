# Function: <code>__get_super_thawed</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248a80)
Location: fs/super.c:693
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff81248a80-ffffffff81248b88: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254390)
Location: fs/super.c:696
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff81254390-ffffffff81254498: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812764a0)
Location: fs/super.c:696
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812764a0-ffffffff812765a8: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129cd50)
Location: fs/super.c:728
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff8129cd50-ffffffff8129ce59: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1f10)
Location: fs/super.c:732
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812b1f10-ffffffff812b2019: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cecc0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812cecc0-ffffffff812cedbd: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e06f0)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812e06f0-ffffffff812e07ed: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317500)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff81317500-ffffffff81317626: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103879c8)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffff8000103879c8-ffff800010387b4c: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056fb84)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
c056fb84-c056fc9c: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047d870)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
c00000000047d870-c00000000047da1c: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259eea)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffe000259eea-ffffffe000259fce: __get_super_thawed (STB_LOCAL)
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
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8cd0)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812d8cd0-ffffffff812d8dcd: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9950)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812c9950-ffffffff812c9a4d: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6ae0)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812d6ae0-ffffffff812d6bdd: __get_super_thawed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *__get_super_thawed(struct block_device *bdev, bool excl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e74b0)
Location: fs/super.c:792
Inline: False
Direct callers:
  - fs/super.c:get_super_exclusive_thawed
  - fs/super.c:get_super_thawed
```
**Symbols:**

```
ffffffff812e74b0-ffffffff812e75b6: __get_super_thawed (STB_LOCAL)
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
