# Function: <code>vmalloc_exec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cf630)
Location: mm/vmalloc.c:1843
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff811cf630-ffffffff811cf682: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ec7b0)
Location: mm/vmalloc.c:1864
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff811ec7b0-ffffffff811ec802: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fda50)
Location: mm/vmalloc.c:1877
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff811fda50-ffffffff811fdaa2: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812086b0)
Location: mm/vmalloc.c:1947
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff812086b0-ffffffff812086ec: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812217c0)
Location: mm/vmalloc.c:1939
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff812217c0-ffffffff81221804: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81243680)
Location: mm/vmalloc.c:1926
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff81243680-ffffffff812436cb: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81257d80)
Location: mm/vmalloc.c:1928
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff81257d80-ffffffff81257dcb: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a980)
Location: mm/vmalloc.c:2681
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff8126a980-ffffffff8126a9ce: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279890)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff81279890-ffffffff812798de: vmalloc_exec (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff8000103107c8)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:alloc_insn_page
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffff8000103107c8-ffff8000103108c4: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c8a8)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
c052c8a8-c052c918: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e17a0)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
c0000000003e17a0-c0000000003e1808: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000218864)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffe000218864-ffffffe0002188b2: vmalloc_exec (STB_GLOBAL)
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
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81271ee0)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff81271ee0-ffffffff81271f2e: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263e50)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff81263e50-ffffffff81263e9e: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126fc80)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff8126fc80-ffffffff8126fcce: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *vmalloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f670)
Location: mm/vmalloc.c:2689
Inline: False
Direct callers:
  - kernel/module.c:module_alloc
```
**Symbols:**

```
ffffffff8127f670-ffffffff8127f6be: vmalloc_exec (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
