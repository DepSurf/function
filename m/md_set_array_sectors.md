# Function: <code>md_set_array_sectors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168f400)
Location: drivers/md/md.c:6416
Inline: False
```
**Symbols:**

```
ffffffff8168f400-ffffffff8168f454: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f0210)
Location: drivers/md/md.c:6439
Inline: False
```
**Symbols:**

```
ffffffff816f0210-ffffffff816f0264: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81721ab0)
Location: drivers/md/md.c:6495
Inline: False
```
**Symbols:**

```
ffffffff81721ab0-ffffffff81721b08: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81737fc0)
Location: drivers/md/md.c:6708
Inline: False
```
**Symbols:**

```
ffffffff81737fc0-ffffffff8173800e: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817a85e0)
Location: drivers/md/md.c:6763
Inline: False
```
**Symbols:**

```
ffffffff817a85e0-ffffffff817a85fc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f8d1e)
Location: drivers/md/md.c:6832
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff817f00c0-ffffffff817f00dc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81824d68)
Location: drivers/md/md.c:6819
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8181bfb0-ffffffff8181bfcc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818671de)
Location: drivers/md/md.c:6881
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8185e1f0-ffffffff8185e20c: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81898f6e)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8188fd20-ffffffff8188fd3c: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819682a2)
Location: drivers/md/md.c:7183
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8195eba0-ffffffff8195ebbc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196ee5b)
Location: drivers/md/md.c:7216
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff819653d0-ffffffff819653ec: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819536b1)
Location: drivers/md/md.c:7171
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81949680-ffffffff8194969c: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819f8c81)
Location: drivers/md/md.c:7184
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff819ee780-ffffffff819ee79c: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b5fef9)
Location: drivers/md/md.c:7181
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81b551d0-ffffffff81b551f6: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cfa384)
Location: drivers/md/md.c:7167
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81cee020-ffffffff81cee046: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d69b16)
Location: drivers/md/md.c:7170
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81d56d50-ffffffff81d56d76: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e1fd8f)
Location: drivers/md/md.c:7285
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81e0dcc0-ffffffff81e0dce6: md_set_array_sectors (STB_GLOBAL)
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
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aece78)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffff800010ae1f00-ffff800010ae1f34: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bca454)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
c0bc3140-c0bc3164: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd2c84)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
c000000000bc98b0-c000000000bc98cc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e1088)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffe0006d89e4-ffffffe0006d8a14: md_set_array_sectors (STB_GLOBAL)
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
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8183edee)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff81835ba0-ffffffff81835bbc: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8180644e)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff817fd210-ffffffff817fd22c: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8188e41e)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff818851d0-ffffffff818851ec: md_set_array_sectors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void md_set_array_sectors(struct mddev *mddev, sector_t array_sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a7633)
Location: drivers/md/md.c:6985
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff818a0be0-ffffffff818a0bfc: md_set_array_sectors (STB_GLOBAL)
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
