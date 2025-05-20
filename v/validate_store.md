# Function: <code>validate_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811eceb0)
Location: mm/slub.c:4925
Inline: False
```
**Symbols:**

```
ffffffff811eceb0-ffffffff811ed0c3: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120c610)
Location: mm/slub.c:5150
Inline: False
```
**Symbols:**

```
ffffffff8120c610-ffffffff8120c81c: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121e670)
Location: mm/slub.c:5119
Inline: False
```
**Symbols:**

```
ffffffff8121e670-ffffffff8121e87c: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122a200)
Location: mm/slub.c:5181
Inline: False
```
**Symbols:**

```
ffffffff8122a200-ffffffff8122a41a: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812453b0)
Location: mm/slub.c:5197
Inline: False
```
**Symbols:**

```
ffffffff812453b0-ffffffff812455ca: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5201
Inline: False
```
**Symbols:**

```
ffffffff812694c0-ffffffff8126969a: validate_store (STB_LOCAL)
ffffffff8126b1e2-ffffffff8126b216: validate_store.cold.98 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5250
Inline: False
```
**Symbols:**

```
ffffffff8127c5a0-ffffffff8127c772: validate_store (STB_LOCAL)
ffffffff8127f918-ffffffff8127f94c: validate_store.cold.98 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5241
Inline: False
```
**Symbols:**

```
ffffffff81298160-ffffffff8129834e: validate_store (STB_LOCAL)
ffffffff8129b82a-ffffffff8129b85f: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffff812a7fc0-ffffffff812a81ae: validate_store (STB_LOCAL)
ffffffff812ab6b6-ffffffff812ab6eb: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812dd4d0)
Location: mm/slub.c:5329
Inline: False
```
**Symbols:**

```
ffffffff812dd4d0-ffffffff812dd559: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e62c0)
Location: mm/slub.c:5269
Inline: False
```
**Symbols:**

```
ffffffff812e62c0-ffffffff812e6349: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5334
Inline: False
```
**Symbols:**

```
ffffffff812ed980-ffffffff812edade: validate_store (STB_LOCAL)
ffffffff81bdb869-ffffffff81bdb89f: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81335e80)
Location: mm/slub.c:5572
Inline: False
```
**Symbols:**

```
ffffffff81335e80-ffffffff81335eb4: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a76a0)
Location: mm/slub.c:5623
Inline: False
```
**Symbols:**

```
ffffffff813a76a0-ffffffff813a76ec: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8142b500)
Location: mm/slub.c:5753
Inline: False
```
**Symbols:**

```
ffffffff8142b500-ffffffff8142b576: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81460a70)
Location: mm/slub.c:5767
Inline: False
```
**Symbols:**

```
ffffffff81460a70-ffffffff81460ae6: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458a30)
Location: mm/slub.c:6378
Inline: False
```
**Symbols:**

```
ffffffff81458a30-ffffffff81458aa6: validate_store (STB_LOCAL)
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
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349600)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffff800010349600-ffff800010349860: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d7b0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
c054d7b0-c054d940: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
ssize_t validate_store(struct kobject *kobj, struct kobj_attribute *attr, const char *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/powernv/opal-flash.c (c0000000000ca550)
Location: arch/powerpc/platforms/powernv/opal-flash.c:190
Inline: False
```
```
In mm/slub.c (c0000000004282c0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
c0000000000ca550-c0000000000ca6c8: validate_store (STB_LOCAL)
c0000000004282c0-c000000000428630: validate_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023b31c)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffe00023b31c-ffffffe00023b496: validate_store (STB_LOCAL)
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
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffff812a05a0-ffffffff812a078e: validate_store (STB_LOCAL)
ffffffff812a3c96-ffffffff812a3ccb: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffff812920b0-ffffffff8129229e: validate_store (STB_LOCAL)
ffffffff81295766-ffffffff8129579b: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffff8129e3b0-ffffffff8129e59e: validate_store (STB_LOCAL)
ffffffff812a1aa6-ffffffff812a1adb: validate_store.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t validate_store(struct kmem_cache *s, const char *buf, size_t length);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:5268
Inline: False
```
**Symbols:**

```
ffffffff812ae460-ffffffff812ae60d: validate_store (STB_LOCAL)
ffffffff812b1c56-ffffffff812b1c8b: validate_store.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kobject *kobj</code>
</li>
<li>
<b>Param added. </b>
<code>struct kobj_attribute *attr</code>
</li>
<li>
<b>Param added. </b>
<code>size_t count</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kmem_cache *s</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t length</code>
</li>
<li>
<b>Param reordered. </b>
<code>s, buf, length</code> ➡️ <code>kobj, attr, buf, count</code>
</li>
</ul>
</details>
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
