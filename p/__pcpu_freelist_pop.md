# Function: <code>__pcpu_freelist_pop</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d6280)
Location: kernel/bpf/percpu_freelist.c:87
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811d6280-ffffffff811d6322: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eac50)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811eac50-ffffffff811eacef: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f73b0)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811f73b0-ffffffff811f744f: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121b080)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff8121b080-ffffffff8121b11f: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121e0ab)
Location: kernel/bpf/percpu_freelist.c:193
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8121e060-ffffffff8121e085: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812219e0)
Location: kernel/bpf/percpu_freelist.c:193
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff812219e0-ffffffff81221b56: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81259480)
Location: kernel/bpf/percpu_freelist.c:193
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff81259480-ffffffff81259632: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a23f0)
Location: kernel/bpf/percpu_freelist.c:193
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff812a23f0-ffffffff812a25ce: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8130006c)
Location: kernel/bpf/percpu_freelist.c:184
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81300000-ffffffff81300031: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132ebcc)
Location: kernel/bpf/percpu_freelist.c:184
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8132eb60-ffffffff8132eb91: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff813530ec)
Location: kernel/bpf/percpu_freelist.c:184
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81353080-ffffffff813530b1: __pcpu_freelist_pop (STB_GLOBAL)
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
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027c0c8)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffff80001027c0c8-ffff80001027c204: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04ade00)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
c04ade00-c04adee0: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c000000000325950)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
c000000000325950-c000000000325aac: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3aac)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffe0001b3aac-ffffffe0001b3bc4: __pcpu_freelist_pop (STB_GLOBAL)
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
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ef9d0)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811ef9d0-ffffffff811efa6f: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e2740)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811e2740-ffffffff811e27df: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed7a0)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811ed7a0-ffffffff811ed83f: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pcpu_freelist_node *__pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbc70)
Location: kernel/bpf/percpu_freelist.c:84
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff811fbc70-ffffffff811fbd0b: __pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
