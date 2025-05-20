# Function: <code>vmalloc_huge</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *vmalloc_huge(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81367060)
Location: mm/vmalloc.c:3281
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
**Symbols:**

```
ffffffff81367060-ffffffff813670d5: vmalloc_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *vmalloc_huge(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e2f10)
Location: mm/vmalloc.c:3343
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_large_system_hash
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/udp.c:udp_pernet_init
```
**Symbols:**

```
ffffffff813e2f10-ffffffff813e2f85: vmalloc_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *vmalloc_huge(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81417b70)
Location: mm/vmalloc.c:3436
Inline: False
Direct callers:
  - mm/mm_init.c:alloc_large_system_hash
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/udp.c:udp_pernet_init
```
**Symbols:**

```
ffffffff81417b70-ffffffff81417be5: vmalloc_huge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *vmalloc_huge(long unsigned int size, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814446c0)
Location: mm/vmalloc.c:3436
Inline: False
Direct callers:
  - mm/mm_init.c:alloc_large_system_hash
  - net/ipv4/inet_hashtables.c:inet_pernet_hashinfo_alloc
  - net/ipv4/udp.c:udp_pernet_init
```
**Symbols:**

```
ffffffff814446c0-ffffffff81444735: vmalloc_huge (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
