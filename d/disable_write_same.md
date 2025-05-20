# Function: <code>disable_write_same</code>

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
In drivers/md/dm.c (ffffffff816a1793)
Location: drivers/md/dm.c:983
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_softirq_done
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817027e8)
Location: drivers/md/dm.c:817
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff81703a50-ffffffff81703a7a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817346a3)
Location: drivers/md/dm.c:817
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_softirq_done
```
**Symbols:**

```
ffffffff81735910-ffffffff8173593a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174da93)
Location: drivers/md/dm.c:818
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8174ed20-ffffffff8174ed4a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bfb75)
Location: drivers/md/dm.c:827
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff817c0f70-ffffffff817c0f97: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807bfe)
Location: drivers/md/dm.c:911
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81809670-ffffffff8180969a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833ace)
Location: drivers/md/dm.c:966
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81835780-ffffffff818357aa: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81878776)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818787a0-ffffffff818787ca: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa5b6)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818aa5e0-ffffffff818aa60a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197a01a)
Location: drivers/md/dm.c:970
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197a8e0-ffffffff8197a908: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197ee03)
Location: drivers/md/dm.c:966
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197f120-ffffffff8197f148: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81962c59)
Location: drivers/md/dm.c:969
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff81963240-ffffffff81963268: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0a63e)
Location: drivers/md/dm.c:858
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81a0b330-ffffffff81a0b358: disable_write_same (STB_GLOBAL)
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
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b0050c)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffff800010b00528-ffff800010b00560: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdff8c)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c0bdffa8-c0bdffdc: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef9a4)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c000000000bef9d0-c000000000bef9f8: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0a1c)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffe0006f0a34-ffffffe0006f0a6a: disable_write_same (STB_GLOBAL)
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
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81850436)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81850460-ffffffff8185048a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81817a46)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81817a70-ffffffff81817a9a: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189fa66)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8189fa90-ffffffff8189faba: disable_write_same (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disable_write_same(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bbcc6)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818bbcf0-ffffffff818bbd1a: disable_write_same (STB_GLOBAL)
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
