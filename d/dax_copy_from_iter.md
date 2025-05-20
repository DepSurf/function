# Function: <code>dax_copy_from_iter</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8163c9d0)
Location: drivers/dax/super.c:248
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff8163c9d0-ffffffff8163c9f3: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816a5660)
Location: drivers/dax/super.c:272
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff816a5660-ffffffff816a5689: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1be0)
Location: drivers/dax/super.c:288
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff816e1be0-ffffffff816e1c0b: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705000)
Location: drivers/dax/super.c:287
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81705000-ffffffff81705028: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ee10)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff8173ee10-ffffffff8173ee3b: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81762ff0)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81762ff0-ffffffff8176301b: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822db0)
Location: drivers/dax/super.c:331
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81822db0-ffffffff81822de0: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831ac0)
Location: drivers/dax/super.c:339
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81831ac0-ffffffff81831af0: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814cf0)
Location: drivers/dax/super.c:339
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81814cf0-ffffffff81814d20: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f480)
Location: drivers/dax/super.c:331
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff8189f480-ffffffff8189f4b0: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e94a0)
Location: drivers/dax/super.c:149
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff819e94a0-ffffffff819e9513: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65d60)
Location: drivers/dax/super.c:171
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81b65d60-ffffffff81b65dd3: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9370)
Location: drivers/dax/super.c:171
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81bb9370-ffffffff81bb93e3: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0d9d0)
Location: drivers/dax/super.c:171
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81c0d9d0-ffffffff81c0da43: dax_copy_from_iter (STB_GLOBAL)
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
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962d90)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffff800010962d90-ffff800010962e14: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39e24)
Location: drivers/dax/super.c:327
Inline: True
```
**Symbols:**

```
c0a39e24-c0a39e6c: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a191e0)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
c000000000a191e0-c000000000a19238: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d034a)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffe0005d034a-ffffffe0005d039e: dax_copy_from_iter (STB_GLOBAL)
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
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817176e0)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff817176e0-ffffffff8171770b: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efc10)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff816efc10-ffffffff816efc3b: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817564b0)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff817564b0-ffffffff817564db: dax_copy_from_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_from_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771b30)
Location: drivers/dax/super.c:327
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_from_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_from_iter
```
**Symbols:**

```
ffffffff81771b30-ffffffff81771b5b: dax_copy_from_iter (STB_GLOBAL)
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
