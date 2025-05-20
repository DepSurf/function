# Function: <code>vm_insert_pages</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812930e0)
Location: mm/memory.c:1589
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff812930e0-ffffffff81293158: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129d9b0)
Location: mm/memory.c:1763
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff8129d9b0-ffffffff8129da28: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a2f80)
Location: mm/memory.c:1781
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff812a2f80-ffffffff812a2ff8: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6650)
Location: mm/memory.c:1876
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff812e6650-ffffffff812e671b: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81345b90)
Location: mm/memory.c:1969
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff81345b90-ffffffff81345c78: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813bdf30)
Location: mm/memory.c:1940
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff813bdf30-ffffffff813be018: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f2880)
Location: mm/memory.c:1960
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff813f2880-ffffffff813f2cb0: vm_insert_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vm_insert_pages(struct vm_area_struct *vma, long unsigned int addr, struct page **pages, long unsigned int *num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141d5c0)
Location: mm/memory.c:1996
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
  - net/ipv4/tcp.c:tcp_zerocopy_vm_insert_batch
```
**Symbols:**

```
ffffffff8141d5c0-ffffffff8141d99c: vm_insert_pages (STB_GLOBAL)
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
