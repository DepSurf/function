# Function: <code>shutdown_memcg_caches</code>

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
In mm/slab_common.c (ffffffff811b31bf)
Location: mm/slab_common.c:630
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811ccc28)
Location: mm/slab_common.c:635
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811dcd18)
Location: mm/slab_common.c:664
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811e5f7a)
Location: mm/slab_common.c:742
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff811fc1ba)
Location: mm/slab_common.c:751
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff8121dbab)
Location: mm/slab_common.c:780
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff81230b8b)
Location: mm/slab_common.c:807
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff81240fc4)
Location: mm/slab_common.c:833
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff8124f465)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shutdown_memcg_caches(struct kmem_cache *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8127d580)
Location: mm/slab_common.c:834
Inline: False
Direct callers:
  - mm/slab_common.c:kmem_cache_destroy
```
**Symbols:**

```
ffffffff8127d580-ffffffff8127d732: shutdown_memcg_caches (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffff8000102e58bc)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (c0509b54)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (c0000000003a7980)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffe0001fc2d6)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff81247ab5)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff8123aa5f)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
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
In mm/slab_common.c (ffffffff81245855)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slab_common.c (ffffffff8125475c)
Location: mm/slab_common.c:834
Inline: True
Inline callers:
  - mm/slab_common.c:kmem_cache_destroy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
