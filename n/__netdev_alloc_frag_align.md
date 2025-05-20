# Function: <code>__netdev_alloc_frag_align</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d1ee0)
Location: net/core/skbuff.c:152
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff819d1ee0-ffffffff819d1f69: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a81b60)
Location: net/core/skbuff.c:154
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81a81b60-ffffffff81a81be9: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf3a40)
Location: net/core/skbuff.c:149
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81bf3a40-ffffffff81bf3ae0: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1a50)
Location: net/core/skbuff.c:232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81da1a50-ffffffff81da1b0b: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e101f0)
Location: net/core/skbuff.c:303
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81e101f0-ffffffff81e102ab: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__netdev_alloc_frag_align(unsigned int fragsz, unsigned int align_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81eccca0)
Location: net/core/skbuff.c:304
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_alloc_frags
```
**Symbols:**

```
ffffffff81eccca0-ffffffff81eccd5c: __netdev_alloc_frag_align (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
