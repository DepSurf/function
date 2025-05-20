# Function: <code>lock_rdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8168ff10)
Location: drivers/md/md.c:2159
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff8168ff10-ffffffff8168ffa1: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f0bc0)
Location: drivers/md/md.c:2158
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff816f0bc0-ffffffff816f0c51: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81722450)
Location: drivers/md/md.c:2194
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81722450-ffffffff817224e1: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81739b90)
Location: drivers/md/md.c:2229
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81739b90-ffffffff81739c21: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817ac3e0)
Location: drivers/md/md.c:2276
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff817ac3e0-ffffffff817ac471: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817f2790)
Location: drivers/md/md.c:2291
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff817f2790-ffffffff817f2821: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8181e690)
Location: drivers/md/md.c:2282
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff8181e690-ffffffff8181e721: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81860b60)
Location: drivers/md/md.c:2345
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81860b60-ffffffff81860bf1: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81892790)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81892790-ffffffff81892821: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81965943)
Location: drivers/md/md.c:2525
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81960a30-ffffffff81960a7b: lock_rdev (STB_LOCAL)
ffffffff8196fe82-ffffffff8196fea4: lock_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8196c3a3)
Location: drivers/md/md.c:2546
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81967330-ffffffff8196737b: lock_rdev (STB_LOCAL)
ffffffff81c25fd0-ffffffff81c25ff2: lock_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff8194ed93)
Location: drivers/md/md.c:2510
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff8194b3d0-ffffffff8194b41b: lock_rdev (STB_LOCAL)
ffffffff81c18155-ffffffff81c18177: lock_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff819f4233)
Location: drivers/md/md.c:2520
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff819f0570-ffffffff819f05bb: lock_rdev (STB_LOCAL)
ffffffff81d27551-ffffffff81d27573: lock_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81b5db01)
Location: drivers/md/md.c:2512
Inline: True
Inline callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81b588d0-ffffffff81b58925: lock_rdev (STB_LOCAL)
ffffffff81ef341a-ffffffff81ef343c: lock_rdev.cold (STB_LOCAL)
```
</details>
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
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae3f30)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffff800010ae3f30-ffff800010ae3fe0: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc686c)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
c0bc686c-c0bc691c: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bcdd90)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
c000000000bcdd90-c000000000bcde98: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006db018)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffe0006db018-ffffffe0006db09e: lock_rdev (STB_LOCAL)
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
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81838610)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81838610-ffffffff818386a1: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817ffc80)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff817ffc80-ffffffff817ffd11: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81887c40)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff81887c40-ffffffff81887cd1: lock_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int lock_rdev(struct md_rdev *rdev, dev_t dev, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a3f70)
Location: drivers/md/md.c:2399
Inline: False
Direct callers:
  - drivers/md/md.c:md_import_device
```
**Symbols:**

```
ffffffff818a3f70-ffffffff818a4001: lock_rdev (STB_LOCAL)
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
