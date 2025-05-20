# Function: <code>__flush_cpu_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ea3f0)
Location: mm/slub.c:2146
Inline: True
Inline callers:
  - mm/slub.c:flush_cpu_slab
  - mm/slub.c:slab_cpuup_callback
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff811ea3f0-ffffffff811ea440: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120a5bc)
Location: mm/slub.c:2275
Inline: True
Inline callers:
  - mm/slub.c:slab_cpuup_callback
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81209a30-ffffffff81209a80: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121c5ac)
Location: mm/slub.c:2278
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8121baa0-ffffffff8121baf0: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81227dec)
Location: mm/slub.c:2282
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812274e0-ffffffff81227528: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81245a8c)
Location: mm/slub.c:2295
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812439a0-ffffffff812439e8: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81265eec)
Location: mm/slub.c:2276
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81265ac0-ffffffff81265b08: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127abcc)
Location: mm/slub.c:2328
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8127a800-ffffffff8127a846: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81296523)
Location: mm/slub.c:2335
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81296150-ffffffff81296196: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a62f3)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812a5f30-ffffffff812a5f76: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812db143)
Location: mm/slub.c:2372
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812dff49-ffffffff812dff8e: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812e9ac3)
Location: mm/slub.c:2437
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81be996b-ffffffff81be99b0: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812f1455)
Location: mm/slub.c:2454
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81bdb9d5-ffffffff81bdba1a: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81339fe0)
Location: mm/slub.c:2618
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81cc1a0f-ffffffff81cc1a88: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813abd20)
Location: mm/slub.c:2660
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81e73ecf-ffffffff81e73f52: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff83ec5f25)
Location: mm/slub.c:2749
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:slub_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff836eb007)
Location: mm/slub.c:2759
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:slub_cpu_dead
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8391a287)
Location: mm/slub.c:3033
Inline: True
Inline callers:
  - mm/slub.c:bootstrap
  - mm/slub.c:slub_cpu_dead
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
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010347494)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffff800010346fc0-ffff800010347020: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054bccc)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
c054bafc-c054bb54: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000425638)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
c000000000425030-c0000000004250b0: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe000239d24)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffe000239b6a-ffffffe000239bc0: __flush_cpu_slab (STB_LOCAL)
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
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129e8d3)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8129e510-ffffffff8129e556: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81290416)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff81290090-ffffffff812900d6: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129c6e3)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff8129c320-ffffffff8129c366: __flush_cpu_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __flush_cpu_slab(struct kmem_cache *s, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ac713)
Location: mm/slub.c:2314
Inline: True
Inline callers:
  - mm/slub.c:slub_cpu_dead
  - mm/slub.c:flush_cpu_slab
Direct callers:
  - mm/slub.c:bootstrap
```
**Symbols:**

```
ffffffff812ac300-ffffffff812ac349: __flush_cpu_slab (STB_LOCAL)
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
