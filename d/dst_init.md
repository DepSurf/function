# Function: <code>dst_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817237a0)
Location: net/core/dst.c:163
Inline: False
Direct callers:
  - net/core/dst.c:dst_alloc
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff817237a0-ffffffff8172389d: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8178d200)
Location: net/core/dst.c:163
Inline: False
Direct callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff8178d200-ffffffff8178d300: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817baad0)
Location: net/core/dst.c:163
Inline: False
Direct callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff817baad0-ffffffff817babd0: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff817d9815)
Location: net/core/dst.c:61
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
Direct callers:
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff817d9b30-ffffffff817d9c05: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81853f35)
Location: net/core/dst.c:61
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
Direct callers:
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff81854160-ffffffff81854235: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189f685)
Location: net/core/dst.c:63
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
Direct callers:
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff8189f890-ffffffff8189f93a: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818c2045)
Location: net/core/dst.c:63
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
Direct callers:
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff818c23d0-ffffffff818c247a: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8190e7a5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff8190eb40-ffffffff8190ebe9: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81940e05)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff819411b0-ffffffff81941259: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a10c95)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
```
**Symbols:**

```
ffffffff81a10740-ffffffff81a107e8: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81a11045)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81a10b90-ffffffff81a10c38: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819f7eb5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff819f7a00-ffffffff819f7aab: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81aa9af5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81aa95f0-ffffffff81aa969b: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81c21f75)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81c219b0-ffffffff81c21a83: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81dd40d5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81dd3c00-ffffffff81dd3cd3: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81e44e55)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81e449c0-ffffffff81e44aa5: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81f03ad5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
  - net/core/dst.c:dst_alloc
Direct callers:
  - net/sched/sch_frag.c:sch_fragment
  - net/sched/sch_frag.c:sch_fragment
```
**Symbols:**

```
ffffffff81f03620-ffffffff81f036ff: dst_init (STB_GLOBAL)
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
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffff800010be09c0)
Location: net/core/dst.c:47
Inline: True
Direct callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffff800010be09c0-ffff800010be0ab4: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c0cfab54)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
c0cfaf88-c0cfb074: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (c000000000cc1ad0)
Location: net/core/dst.c:47
Inline: True
Direct callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
c000000000cc1ad0-c000000000cc1c28: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffe000766ba4)
Location: net/core/dst.c:47
Inline: False
Direct callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffe000766ba4-ffffffe000766c8e: dst_init (STB_GLOBAL)
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
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff818e0dd5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff818e1180-ffffffff818e1229: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff8189ac15)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff8189afc0-ffffffff8189b069: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff81931e05)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff819321b0-ffffffff81932259: dst_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dst_init(struct dst_entry *dst, struct dst_ops *ops, struct net_device *dev, int initial_ref, int initial_obsolete, short unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dst.c (ffffffff819534d5)
Location: net/core/dst.c:47
Inline: True
Inline callers:
  - net/core/dst.c:__metadata_dst_init
```
**Symbols:**

```
ffffffff81953880-ffffffff81953929: dst_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int initial_ref</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst, ops, dev, initial_ref, initial_obsolete, flags</code> ➡️ <code>dst, ops, dev, initial_obsolete, flags</code>
</li>
</ul>
</details>
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
