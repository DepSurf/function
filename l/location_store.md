# Function: <code>location_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169f950)
Location: drivers/md/bitmap.c:2121
Inline: False
```
**Symbols:**

```
ffffffff8169f950-ffffffff8169fbd4: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81700d40)
Location: drivers/md/bitmap.c:2184
Inline: True
```
**Symbols:**

```
ffffffff81700d40-ffffffff81700fec: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81732aa0)
Location: drivers/md/bitmap.c:2212
Inline: True
```
**Symbols:**

```
ffffffff81732aa0-ffffffff81732d4c: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8174b870)
Location: drivers/md/bitmap.c:2255
Inline: True
```
**Symbols:**

```
ffffffff8174b870-ffffffff8174bb27: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bdbc0)
Location: drivers/md/md-bitmap.c:2274
Inline: True
```
**Symbols:**

```
ffffffff817bdbc0-ffffffff817bdea3: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81805ba0)
Location: drivers/md/md-bitmap.c:2274
Inline: True
```
**Symbols:**

```
ffffffff81805ba0-ffffffff81805e9b: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81831da0)
Location: drivers/md/md-bitmap.c:2265
Inline: True
```
**Symbols:**

```
ffffffff81831da0-ffffffff8183202b: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81874550)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff81874550-ffffffff818747fe: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a6360)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff818a6360-ffffffff818a660e: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81975ee0)
Location: drivers/md/md-bitmap.c:2267
Inline: True
```
**Symbols:**

```
ffffffff81975ee0-ffffffff81976171: location_store.part.0 (STB_LOCAL)
ffffffff81976180-ffffffff819761c8: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8197aed0)
Location: drivers/md/md-bitmap.c:2270
Inline: True
```
**Symbols:**

```
ffffffff8197aed0-ffffffff8197b161: location_store.part.0 (STB_LOCAL)
ffffffff8197b170-ffffffff8197b1b8: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195f100)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff8195f100-ffffffff8195f386: location_store.part.0 (STB_LOCAL)
ffffffff8195f390-ffffffff8195f3d8: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a04a40)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff81a04a40-ffffffff81a04cc6: location_store.part.0 (STB_LOCAL)
ffffffff81a04cd0-ffffffff81a04d18: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b6c720)
Location: drivers/md/md-bitmap.c:2273
Inline: True
```
**Symbols:**

```
ffffffff81b6c720-ffffffff81b6c9af: location_store.part.0 (STB_LOCAL)
ffffffff81b6c9b0-ffffffff81b6ca09: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d08810)
Location: drivers/md/md-bitmap.c:2277
Inline: True
```
**Symbols:**

```
ffffffff81d08810-ffffffff81d08a9f: location_store.part.0 (STB_LOCAL)
ffffffff81d08ab0-ffffffff81d08b09: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d71990)
Location: drivers/md/md-bitmap.c:2343
Inline: True
```
**Symbols:**

```
ffffffff81d71990-ffffffff81d71c09: location_store.part.0 (STB_LOCAL)
ffffffff81d71c20-ffffffff81d71c79: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e28a70)
Location: drivers/md/md-bitmap.c:2347
Inline: True
```
**Symbols:**

```
ffffffff81e28a70-ffffffff81e28caf: location_store.part.0 (STB_LOCAL)
ffffffff81e28cc0-ffffffff81e28d47: location_store (STB_LOCAL)
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
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010afb2d0)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffff800010afb2d0-ffff800010afb530: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bdbd34)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
c0bdbd34-c0bdbfb8: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be94b0)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
c000000000be94b0-c000000000be9898: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ecaaa)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffe0006ecaaa-ffffffe0006ecc96: location_store (STB_LOCAL)
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
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8184c1e0)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff8184c1e0-ffffffff8184c48e: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81813800)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff81813800-ffffffff81813aae: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8189b810)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff8189b810-ffffffff8189babe: location_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t location_store(struct mddev *mddev, const char *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b79c0)
Location: drivers/md/md-bitmap.c:2272
Inline: True
```
**Symbols:**

```
ffffffff818b79c0-ffffffff818b7c6e: location_store (STB_LOCAL)
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
