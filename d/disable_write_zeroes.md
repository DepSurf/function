# Function: <code>disable_write_zeroes</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174da53)
Location: drivers/md/dm.c:826
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8174ed50-ffffffff8174ed7a: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bfb3f)
Location: drivers/md/dm.c:835
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff817c0fa0-ffffffff817c0fc7: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81807bc5)
Location: drivers/md/dm.c:919
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818096a0-ffffffff818096ca: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81833a95)
Location: drivers/md/dm.c:974
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818357b0-ffffffff818357da: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81878718)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818787d0-ffffffff818787fa: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa558)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818aa610-ffffffff818aa63a: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979f93)
Location: drivers/md/dm.c:978
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197a910-ffffffff8197a938: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197eda5)
Location: drivers/md/dm.c:974
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197f150-ffffffff8197f178: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81962c03)
Location: drivers/md/dm.c:977
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff81963270-ffffffff81963298: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0a5e6)
Location: drivers/md/dm.c:866
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81a0b360-ffffffff81a0b388: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b72ffe)
Location: drivers/md/dm.c:1003
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81b73760-ffffffff81b73790: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0efa0)
Location: drivers/md/dm.c:1081
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d10350-ffffffff81d10380: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d781ad)
Location: drivers/md/dm.c:1097
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d797c0-ffffffff81d797e4: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2f3e6)
Location: drivers/md/dm.c:1083
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81e30960-ffffffff81e30984: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b004d0)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffff800010b00560-ffff800010b00598: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdff44)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c0bdffdc-c0be0010: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef940)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c000000000befa00-c000000000befa28: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f09ea)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffe0006f0a6a-ffffffe0006f0aa0: disable_write_zeroes (STB_GLOBAL)
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
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818503d8)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81850490-ffffffff818504ba: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818179e8)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81817aa0-ffffffff81817aca: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189fa08)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8189fac0-ffffffff8189faea: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void disable_write_zeroes(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bbc68)
Location: drivers/md/dm.c:965
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818bbd20-ffffffff818bbd4a: disable_write_zeroes (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
