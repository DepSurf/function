# Function: <code>pcpu_freelist_populate</code>

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
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81187f30)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81187f30-ffffffff81188038: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81195ef0)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81195ef0-ffffffff81195ffb: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8119d460)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8119d460-ffffffff8119d584: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ad010)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811ad010-ffffffff811ad128: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811c4590)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811c4590-ffffffff811c46a8: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d6160)
Location: kernel/bpf/percpu_freelist.c:58
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811d6160-ffffffff811d6278: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eab50)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811eab50-ffffffff811eac45: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f72b0)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811f72b0-ffffffff811f73a5: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121afe0)
Location: kernel/bpf/percpu_freelist.c:61
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8121afe0-ffffffff8121b07e: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121dfc0)
Location: kernel/bpf/percpu_freelist.c:101
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8121dfc0-ffffffff8121e05e: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81221940)
Location: kernel/bpf/percpu_freelist.c:101
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81221940-ffffffff812219de: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81259390)
Location: kernel/bpf/percpu_freelist.c:101
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81259390-ffffffff81259480: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a22f0)
Location: kernel/bpf/percpu_freelist.c:101
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff812a22f0-ffffffff812a23ee: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812ffec0)
Location: kernel/bpf/percpu_freelist.c:99
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff812ffec0-ffffffff812fffe5: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132ea20)
Location: kernel/bpf/percpu_freelist.c:99
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff8132ea20-ffffffff8132eb45: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81352f40)
Location: kernel/bpf/percpu_freelist.c:99
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_init
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff81352f40-ffffffff81353065: pcpu_freelist_populate (STB_GLOBAL)
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
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027bf08)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffff80001027bf08-ffff80001027c0c4: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04adcd0)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
c04adcd0-c04ade00: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c000000000325750)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
c000000000325750-c000000000325944: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3968)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffe0001b3968-ffffffe0001b3aac: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ef8d0)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811ef8d0-ffffffff811ef9c5: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e2650)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811e2650-ffffffff811e2731: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed6a0)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811ed6a0-ffffffff811ed795: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_freelist_populate(struct pcpu_freelist *s, void *buf, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbb70)
Location: kernel/bpf/percpu_freelist.c:55
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
```
**Symbols:**

```
ffffffff811fbb70-ffffffff811fbc63: pcpu_freelist_populate (STB_GLOBAL)
```
</details>
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
