# Function: <code>dax_copy_to_iter</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816e1c10)
Location: drivers/dax/super.c:298
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff816e1c10-ffffffff816e1c3b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81705030)
Location: drivers/dax/super.c:297
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81705030-ffffffff81705058: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173ee40)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff8173ee40-ffffffff8173ee6b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763020)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81763020-ffffffff8176304b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81822de0)
Location: drivers/dax/super.c:341
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81822de0-ffffffff81822e10: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831af0)
Location: drivers/dax/super.c:349
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81831af0-ffffffff81831b20: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814d20)
Location: drivers/dax/super.c:349
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81814d20-ffffffff81814d50: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f4b0)
Location: drivers/dax/super.c:341
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff8189f4b0-ffffffff8189f4e0: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e9520)
Location: drivers/dax/super.c:165
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff819e9520-ffffffff819e9593: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65df0)
Location: drivers/dax/super.c:187
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81b65df0-ffffffff81b65e63: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb9400)
Location: drivers/dax/super.c:187
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81bb9400-ffffffff81bb9473: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0da60)
Location: drivers/dax/super.c:187
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
```
**Symbols:**

```
ffffffff81c0da60-ffffffff81c0dad3: dax_copy_to_iter (STB_GLOBAL)
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
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010962e18)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffff800010962e18-ffff800010962e9c: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39e6c)
Location: drivers/dax/super.c:337
Inline: True
```
**Symbols:**

```
c0a39e6c-c0a39eb4: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19240)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
c000000000a19240-c000000000a19298: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d039e)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffe0005d039e-ffffffe0005d03f2: dax_copy_to_iter (STB_GLOBAL)
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
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717710)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81717710-ffffffff8171773b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efc40)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff816efc40-ffffffff816efc6b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817564e0)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff817564e0-ffffffff8175650b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t dax_copy_to_iter(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771b60)
Location: drivers/dax/super.c:337
Inline: True
Direct callers:
  - fs/dax.c:dax_iomap_actor
  - drivers/md/dm-linear.c:linear_dax_copy_to_iter
  - drivers/md/dm-stripe.c:stripe_dax_copy_to_iter
```
**Symbols:**

```
ffffffff81771b60-ffffffff81771b8b: dax_copy_to_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
