# Function: <code>disable_discard</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818785f0)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818785f0-ffffffff8187862c: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa430)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818aa430-ffffffff818aa46c: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979fd0)
Location: drivers/md/dm.c:961
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197a8a0-ffffffff8197a8d9: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197ee39)
Location: drivers/md/dm.c:957
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff8197f0e0-ffffffff8197f119: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81962c87)
Location: drivers/md/dm.c:960
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
Direct callers:
  - drivers/md/dm-rq.c:dm_done
```
**Symbols:**

```
ffffffff81963200-ffffffff81963239: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0a66e)
Location: drivers/md/dm.c:849
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81a0b2f0-ffffffff81a0b329: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b73065)
Location: drivers/md/dm.c:995
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81b73730-ffffffff81b73760: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0efe9)
Location: drivers/md/dm.c:1073
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d10310-ffffffff81d10340: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d781f7)
Location: drivers/md/dm.c:1089
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d79780-ffffffff81d797a4: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2f430)
Location: drivers/md/dm.c:1075
Inline: True
Inline callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81e30920-ffffffff81e30944: disable_discard (STB_GLOBAL)
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
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00380)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffff800010b00380-ffff800010b003c4: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdfde0)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c0bdfde0-c0bdfe24: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef790)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
c000000000bef790-c000000000bef7ec: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f08dc)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffe0006f08dc-ffffffe0006f091e: disable_discard (STB_GLOBAL)
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
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818502b0)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818502b0-ffffffff818502ec: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818178c0)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818178c0-ffffffff818178fc: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189f8e0)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8189f8e0-ffffffff8189f91c: disable_discard (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void disable_discard(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bbb40)
Location: drivers/md/dm.c:948
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff818bbb40-ffffffff818bbb7c: disable_discard (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
