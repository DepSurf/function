# Function: <code>loop_backing_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8156da20)
Location: drivers/block/loop.c:737
Inline: False
```
**Symbols:**

```
ffffffff8156da20-ffffffff8156da54: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815c3310)
Location: drivers/block/loop.c:732
Inline: False
```
**Symbols:**

```
ffffffff815c3310-ffffffff815c3344: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff815f1a30)
Location: drivers/block/loop.c:708
Inline: False
```
**Symbols:**

```
ffffffff815f1a30-ffffffff815f1a64: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81605b70)
Location: drivers/block/loop.c:731
Inline: False
```
**Symbols:**

```
ffffffff81605b70-ffffffff81605ba6: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8166df70)
Location: drivers/block/loop.c:720
Inline: False
```
**Symbols:**

```
ffffffff8166df70-ffffffff8166dfa6: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ab7b0)
Location: drivers/block/loop.c:770
Inline: True
```
**Symbols:**

```
ffffffff816ab7b0-ffffffff816ab7e4: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cbf20)
Location: drivers/block/loop.c:767
Inline: True
```
**Symbols:**

```
ffffffff816cbf20-ffffffff816cbf54: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81707520)
Location: drivers/block/loop.c:767
Inline: True
```
**Symbols:**

```
ffffffff81707520-ffffffff81707558: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8172b770)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffff8172b770-ffffffff8172b7a8: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e7c70)
Location: drivers/block/loop.c:792
Inline: True
```
**Symbols:**

```
ffffffff817e7c70-ffffffff817e7ca8: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fcb60)
Location: drivers/block/loop.c:790
Inline: True
```
**Symbols:**

```
ffffffff817fcb60-ffffffff817fcb95: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186ce30)
Location: drivers/block/loop.c:829
Inline: True
```
**Symbols:**

```
ffffffff8186ce30-ffffffff8186ce65: loop_backing_file (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010921b80)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffff800010921b80-ffff800010921bd4: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a073c8)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
c0a073c8-c0a07400: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c6980)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
c0000000009c6980-c0000000009c69b8: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe0005a06bc)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffe0005a06bc-ffffffe0005a06f4: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816f1550)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffff816f1550-ffffffff816f1588: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816cb650)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffff816cb650-ffffffff816cb688: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171ec30)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffff8171ec30-ffffffff8171ec68: loop_backing_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct file *loop_backing_file(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8173a060)
Location: drivers/block/loop.c:777
Inline: True
```
**Symbols:**

```
ffffffff8173a060-ffffffff8173a098: loop_backing_file (STB_GLOBAL)
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
