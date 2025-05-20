# Function: <code>pcpu_freelist_pop</code>

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
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81188040)
Location: kernel/bpf/percpu_freelist.c:77
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81188040-ffffffff811880e7: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81196000)
Location: kernel/bpf/percpu_freelist.c:77
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81196000-ffffffff811960a9: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8119d590)
Location: kernel/bpf/percpu_freelist.c:77
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8119d590-ffffffff8119d638: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ad130)
Location: kernel/bpf/percpu_freelist.c:77
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811ad130-ffffffff811ad1f3: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811c46b0)
Location: kernel/bpf/percpu_freelist.c:77
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811c46b0-ffffffff811c4773: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d6330)
Location: kernel/bpf/percpu_freelist.c:112
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811d6330-ffffffff811d6363: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eacf0)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811eacf0-ffffffff811ead23: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f7450)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811f7450-ffffffff811f7483: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121b120)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8121b120-ffffffff8121b156: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121e090)
Location: kernel/bpf/percpu_freelist.c:200
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff8121e090-ffffffff8121e0de: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81221b60)
Location: kernel/bpf/percpu_freelist.c:200
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81221b60-ffffffff81221ba1: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81259640)
Location: kernel/bpf/percpu_freelist.c:200
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81259640-ffffffff81259681: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a25d0)
Location: kernel/bpf/percpu_freelist.c:200
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff812a25d0-ffffffff812a260d: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81300050)
Location: kernel/bpf/percpu_freelist.c:191
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81300050-ffffffff813000b2: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132ebb0)
Location: kernel/bpf/percpu_freelist.c:191
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff8132ebb0-ffffffff8132ec12: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff813530d0)
Location: kernel/bpf/percpu_freelist.c:191
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff813530d0-ffffffff81353132: pcpu_freelist_pop (STB_GLOBAL)
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
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027c208)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffff80001027c208-ffff80001027c254: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04adee0)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c04adee0-c04adf08: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c000000000325ab0)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c000000000325ab0-c000000000325b10: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3bc4)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffe0001b3bc4-ffffffe0001b3bfe: pcpu_freelist_pop (STB_GLOBAL)
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
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811efa70)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811efa70-ffffffff811efaa3: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e27e0)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811e27e0-ffffffff811e27f7: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed840)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811ed840-ffffffff811ed873: pcpu_freelist_pop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pcpu_freelist_node *pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbd10)
Location: kernel/bpf/percpu_freelist.c:109
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811fbd10-ffffffff811fbd43: pcpu_freelist_pop (STB_GLOBAL)
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
