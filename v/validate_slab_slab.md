# Function: <code>validate_slab_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff811ecf77)
Location: mm/slub.c:4115
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8120c6dc)
Location: mm/slub.c:4342
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8121e73c)
Location: mm/slub.c:4311
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8122a2ca)
Location: mm/slub.c:4353
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8124547a)
Location: mm/slub.c:4369
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812695ad)
Location: mm/slub.c:4371
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8127c685)
Location: mm/slub.c:4423
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81298258)
Location: mm/slub.c:4414
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a80b8)
Location: mm/slub.c:4432
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
void validate_slab_slab(struct kmem_cache *s, struct page *page, long unsigned int *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349368)
Location: mm/slub.c:4432
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffff800010349368-ffff800010349600: validate_slab_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void validate_slab_slab(struct kmem_cache *s, struct page *page, long unsigned int *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d514)
Location: mm/slub.c:4432
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
**Symbols:**

```
c054d514-c054d7b0: validate_slab_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c000000000428584)
Location: mm/slub.c:4432
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void validate_slab_slab(struct kmem_cache *s, struct page *page, long unsigned int *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023b104)
Location: mm/slub.c:4432
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffe00023b104-ffffffe00023b31c: validate_slab_slab (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812a0698)
Location: mm/slub.c:4432
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812921a8)
Location: mm/slub.c:4432
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff8129e4a8)
Location: mm/slub.c:4432
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void validate_slab_slab(struct kmem_cache *s, struct page *page, long unsigned int *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff812ae200)
Location: mm/slub.c:4432
Inline: False
Direct callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff812ae200-ffffffff812ae460: validate_slab_slab (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
