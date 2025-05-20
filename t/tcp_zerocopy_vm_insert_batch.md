# Function: <code>tcp_zerocopy_vm_insert_batch</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa9d9e)
Location: net/ipv4/tcp.c:1745
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2250)
Location: net/ipv4/tcp.c:1975
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81ab2250-ffffffff81ab2364: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9d560)
Location: net/ipv4/tcp.c:1997
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81a9d560-ffffffff81a9d67f: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b593d0)
Location: net/ipv4/tcp.c:1999
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81b593d0-ffffffff81b594ef: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce7b00)
Location: net/ipv4/tcp.c:2026
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81ce7b00-ffffffff81ce7c2b: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eab3d0)
Location: net/ipv4/tcp.c:2126
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81eab3d0-ffffffff81eab4fb: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f09ae0)
Location: net/ipv4/tcp.c:1982
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81f09ae0-ffffffff81f09c15: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_zerocopy_vm_insert_batch(struct vm_area_struct *vma, struct page **pages, unsigned int pages_to_map, long unsigned int *address, u32 *length, u32 *seq, struct tcp_zerocopy_receive *zc, u32 total_bytes_to_map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fcde10)
Location: net/ipv4/tcp.c:1992
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_zerocopy_receive
  - net/ipv4/tcp.c:tcp_zerocopy_receive
```
**Symbols:**

```
ffffffff81fcde10-ffffffff81fcdf45: tcp_zerocopy_vm_insert_batch (STB_LOCAL)
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
