# Function: <code>walk_mem_res</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81092af0)
Location: kernel/resource.c:476
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81092af0-ffffffff81092b49: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096510)
Location: kernel/resource.c:444
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81096510-ffffffff81096569: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e850)
Location: kernel/resource.c:442
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8109e850-ffffffff8109e871: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2ea0)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810a2ea0-ffffffff810a2ec1: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a94e0)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810a94e0-ffffffff810a9501: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b1050)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810b1050-ffffffff810b10f2: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac7b0)
Location: kernel/resource.c:465
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810ac7b0-ffffffff810ac852: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad9b0)
Location: kernel/resource.c:451
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810ad9b0-ffffffff810ada4c: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bf530)
Location: kernel/resource.c:451
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810bf530-ffffffff810bf5cc: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d6910)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810d6910-ffffffff810d69d4: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6320)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810f6320-ffffffff810f63e4: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81102770)
Location: kernel/resource.c:438
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81102770-ffffffff81102834: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110c0a0)
Location: kernel/resource.c:493
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8110c0a0-ffffffff8110c164: walk_mem_res (STB_GLOBAL)
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
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010101290)
Location: kernel/resource.c:458
Inline: False
```
**Symbols:**

```
ffff800010101290-ffff8000101012ec: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035d8d8)
Location: kernel/resource.c:458
Inline: False
```
**Symbols:**

```
c035d8d8-c035d924: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001489c0)
Location: kernel/resource.c:458
Inline: False
```
**Symbols:**

```
c0000000001489c0-c0000000001489f0: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8638)
Location: kernel/resource.c:458
Inline: False
```
**Symbols:**

```
ffffffe0000c8638-ffffffe0000c8686: walk_mem_res (STB_GLOBAL)
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
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2e00)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810a2e00-ffffffff810a2e21: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810917e0)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810917e0-ffffffff81091801: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2db0)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810a2db0-ffffffff810a2dd1: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int walk_mem_res(u64 start, u64 end, void *arg, int (*func)(struct resource *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aae50)
Location: kernel/resource.c:458
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff810aae50-ffffffff810aae71: walk_mem_res (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
