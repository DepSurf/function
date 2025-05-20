# Function: <code>flush_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812480a0)
Location: fs/block_dev.c:1042
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:check_disk_change
```
**Symbols:**

```
ffffffff812480a0-ffffffff8124815d: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270890)
Location: fs/block_dev.c:1120
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff81270890-ffffffff81270903: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81284210)
Location: fs/block_dev.c:1372
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff81284210-ffffffff81284280: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812918c0)
Location: fs/block_dev.c:1297
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff812918c0-ffffffff8129192b: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4620)
Location: fs/block_dev.c:1287
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff812b4620-ffffffff812b468b: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1308
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff812dbc40-ffffffff812dbc8a: flush_disk (STB_LOCAL)
ffffffff812ddf23-ffffffff812ddf4b: flush_disk.cold.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1347
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff812f1330-ffffffff812f137a: flush_disk (STB_LOCAL)
ffffffff812f3513-ffffffff812f353b: flush_disk.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff813131e0-ffffffff8131322a: flush_disk (STB_LOCAL)
ffffffff81314f9c-ffffffff81314fc6: flush_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff81326120-ffffffff81326148: flush_disk (STB_LOCAL)
ffffffff81327e26-ffffffff81327e50: flush_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135ff5e)
Location: fs/block_dev.c:1380
Inline: True
Inline callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
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
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e0380)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffff8000103e0380-ffff8000103e03e8: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b91e8)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
c05b91e8-c05b923c: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e60a0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
c0000000004e60a0-c0000000004e611c: flush_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002970fa)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffe0002970fa-ffffffe000297154: flush_disk (STB_LOCAL)
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
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff8131e700-ffffffff8131e728: flush_disk (STB_LOCAL)
ffffffff81320406-ffffffff81320430: flush_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff8130f2a0-ffffffff8130f2c8: flush_disk (STB_LOCAL)
ffffffff81310fa6-ffffffff81310fd0: flush_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff8131c1d0-ffffffff8131c1f8: flush_disk (STB_LOCAL)
ffffffff8131ded6-ffffffff8131df00: flush_disk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void flush_disk(struct block_device *bdev, bool kill_dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1399
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
```
**Symbols:**

```
ffffffff8132e2e0-ffffffff8132e308: flush_disk (STB_LOCAL)
ffffffff8132fbcd-ffffffff8132fbf7: flush_disk.cold (STB_LOCAL)
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
