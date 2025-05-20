# Function: <code>bpf_map_precharge_memlock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180d60)
Location: kernel/bpf/syscall.c:51
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81180d60-ffffffff81180db4: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cde0)
Location: kernel/bpf/syscall.c:79
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8118cde0-ffffffff8118ce34: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191d50)
Location: kernel/bpf/syscall.c:90
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81191d50-ffffffff81191da9: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f430)
Location: kernel/bpf/syscall.c:137
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8119f430-ffffffff8119f489: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b4e90)
Location: kernel/bpf/syscall.c:171
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811b4e90-ffffffff811b4ee9: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_map_precharge_memlock(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3210)
Location: kernel/bpf/syscall.c:171
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811c3210-ffffffff811c326f: bpf_map_precharge_memlock (STB_GLOBAL)
```
</details>
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
</ul>
