# Function: <code>__pcpu_freelist_push</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81187fef)
Location: kernel/bpf/percpu_freelist.c:31
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81195fb2)
Location: kernel/bpf/percpu_freelist.c:31
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8119d52d)
Location: kernel/bpf/percpu_freelist.c:31
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ad0d1)
Location: kernel/bpf/percpu_freelist.c:31
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811c4651)
Location: kernel/bpf/percpu_freelist.c:31
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_populate
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811d60e0)
Location: kernel/bpf/percpu_freelist.c:40
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811d60e0-ffffffff811d6123: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811eaad0)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811eaad0-ffffffff811eab13: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811f7230)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811f7230-ffffffff811f7273: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121af94)
Location: kernel/bpf/percpu_freelist.c:43
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff8121af20-ffffffff8121af63: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121de70)
Location: kernel/bpf/percpu_freelist.c:82
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff8121de70-ffffffff8121df90: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812217d0)
Location: kernel/bpf/percpu_freelist.c:82
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff812217d0-ffffffff812218f1: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81259200)
Location: kernel/bpf/percpu_freelist.c:82
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff81259200-ffffffff81259342: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812a2140)
Location: kernel/bpf/percpu_freelist.c:82
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff812a2140-ffffffff812a22a3: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812ffc50)
Location: kernel/bpf/percpu_freelist.c:80
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff812ffc50-ffffffff812ffe49: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132e7b0)
Location: kernel/bpf/percpu_freelist.c:80
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff8132e7b0-ffffffff8132e9a9: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff81352cd0)
Location: kernel/bpf/percpu_freelist.c:80
Inline: True
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff81352cd0-ffffffff81352ec9: __pcpu_freelist_push (STB_GLOBAL)
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
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffff80001027be08)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffff80001027be08-ffff80001027bea8: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c04adc90)
Location: kernel/bpf/percpu_freelist.c:37
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
c04adc1c-c04adc70: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (c0000000003256c0)
Location: kernel/bpf/percpu_freelist.c:37
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
c000000000325590-c000000000325674: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffe0001b389a)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffe0001b389a-ffffffe0001b3928: __pcpu_freelist_push (STB_GLOBAL)
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
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ef850)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811ef850-ffffffff811ef893: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811e25e0)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811e25e0-ffffffff811e2623: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811ed620)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811ed620-ffffffff811ed663: __pcpu_freelist_push (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __pcpu_freelist_push(struct pcpu_freelist *s, struct pcpu_freelist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff811fbaf0)
Location: kernel/bpf/percpu_freelist.c:37
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_push
```
**Symbols:**

```
ffffffff811fbaf0-ffffffff811fbb31: __pcpu_freelist_push (STB_GLOBAL)
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
