# Function: <code>pcpu_freelist_push</code>

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
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81187ee0)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81187ee0-ffffffff81187f23: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81195ea0)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff81195ea0-ffffffff81195ee3: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8119d410)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8119d410-ffffffff8119d453: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811acfc0)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811acfc0-ffffffff811ad003: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811c4540)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811c4540-ffffffff811c4583: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d6130)
Location: kernel/bpf/percpu_freelist.c:48
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811d6130-ffffffff811d615d: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eab20)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811eab20-ffffffff811eab4d: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f7280)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811f7280-ffffffff811f72ad: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121af70)
Location: kernel/bpf/percpu_freelist.c:51
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff8121af70-ffffffff8121afd2: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121df90)
Location: kernel/bpf/percpu_freelist.c:91
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff8121df90-ffffffff8121dfc0: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81221900)
Location: kernel/bpf/percpu_freelist.c:91
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81221900-ffffffff81221938: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81259350)
Location: kernel/bpf/percpu_freelist.c:91
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81259350-ffffffff81259388: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a22b0)
Location: kernel/bpf/percpu_freelist.c:91
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff812a22b0-ffffffff812a22e9: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812ffe60)
Location: kernel/bpf/percpu_freelist.c:89
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff812ffe60-ffffffff812ffeaf: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132e9c0)
Location: kernel/bpf/percpu_freelist.c:89
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff8132e9c0-ffffffff8132ea0f: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81352ee0)
Location: kernel/bpf/percpu_freelist.c:89
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:__bpf_get_stackid
  - kernel/bpf/stackmap.c:__bpf_get_stackid
```
**Symbols:**

```
ffffffff81352ee0-ffffffff81352f2f: pcpu_freelist_push (STB_GLOBAL)
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
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027bea8)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffff80001027bea8-ffff80001027bf04: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04adc70)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c04adc70-c04adcd0: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c000000000325680)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
c000000000325680-c000000000325750: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3928)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffe0001b3928-ffffffe0001b3968: pcpu_freelist_push (STB_GLOBAL)
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
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ef8a0)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811ef8a0-ffffffff811ef8cd: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e2630)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811e2630-ffffffff811e2647: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed670)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811ed670-ffffffff811ed69d: pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbb40)
Location: kernel/bpf/percpu_freelist.c:45
Inline: False
Direct callers:
  - kernel/bpf/stackmap.c:stack_map_delete_elem
  - kernel/bpf/stackmap.c:bpf_stackmap_copy
  - kernel/bpf/stackmap.c:bpf_get_stackid
  - kernel/bpf/stackmap.c:bpf_get_stackid
```
**Symbols:**

```
ffffffff811fbb40-ffffffff811fbb6d: pcpu_freelist_push (STB_GLOBAL)
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
