# Function: <code>pcpu_freelist_destroy</code>

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
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81187ec0)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff81187ec0-ffffffff81187ed3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81195e80)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff81195e80-ffffffff81195e93: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8119d3f0)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff8119d3f0-ffffffff8119d403: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811acfa0)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811acfa0-ffffffff811acfb3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811c4520)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811c4520-ffffffff811c4533: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d60c0)
Location: kernel/bpf/percpu_freelist.c:26
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811d60c0-ffffffff811d60d3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eaab0)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811eaab0-ffffffff811eaac3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f7210)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811f7210-ffffffff811f7223: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121af00)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff8121af00-ffffffff8121af13: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121de50)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff8121de50-ffffffff8121de63: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812217b0)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff812217b0-ffffffff812217c3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812591e0)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff812591e0-ffffffff812591f3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a2120)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff812a2120-ffffffff812a2139: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812ffc20)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff812ffc20-ffffffff812ffc39: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132e780)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff8132e780-ffffffff8132e799: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81352ca0)
Location: kernel/bpf/percpu_freelist.c:25
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff81352ca0-ffffffff81352cb9: pcpu_freelist_destroy (STB_GLOBAL)
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
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027bdd8)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffff80001027bdd8-ffff80001027be04: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04adbfc)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
c04adbfc-c04adc1c: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c000000000325550)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
c000000000325550-c000000000325588: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b3870)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffe0001b3870-ffffffe0001b389a: pcpu_freelist_destroy (STB_GLOBAL)
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
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ef830)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811ef830-ffffffff811ef843: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e25c0)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811e25c0-ffffffff811e25d3: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed600)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811ed600-ffffffff811ed613: pcpu_freelist_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcpu_freelist_destroy(struct pcpu_freelist *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbad0)
Location: kernel/bpf/percpu_freelist.c:23
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:prealloc_destroy
  - kernel/bpf/stackmap.c:stack_map_free
```
**Symbols:**

```
ffffffff811fbad0-ffffffff811fbae3: pcpu_freelist_destroy (STB_GLOBAL)
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
