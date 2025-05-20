# Function: <code>bpf_get_kallsym</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f3d0)
Location: kernel/bpf/core.c:462
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8118f3d0-ffffffff8118f47a: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d840)
Location: kernel/bpf/core.c:471
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8119d840-ffffffff8119d8ea: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1fe0)
Location: kernel/bpf/core.c:550
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811b1fe0-ffffffff811b208d: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0890)
Location: kernel/bpf/core.c:673
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811c0890-ffffffff811c0931: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d13d0)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811d13d0-ffffffff811d147b: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd950)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811dd950-ffffffff811dd9fb: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa380)
Location: kernel/bpf/core.c:738
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811fa380-ffffffff811fa422: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f93e0)
Location: kernel/bpf/core.c:734
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811f93e0-ffffffff811f9487: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa270)
Location: kernel/bpf/core.c:740
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811fa270-ffffffff811fa317: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b940)
Location: kernel/bpf/core.c:741
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8122b940-ffffffff8122b9e7: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d420)
Location: kernel/bpf/core.c:744
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8126d420-ffffffff8126d4eb: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c25d0)
Location: kernel/bpf/core.c:752
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff812c25d0-ffffffff812c269b: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9490)
Location: kernel/bpf/core.c:753
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff812e9490-ffffffff812e955b: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307880)
Location: kernel/bpf/core.c:796
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81307880-ffffffff8130794b: bpf_get_kallsym (STB_GLOBAL)
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e660)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffff80001025e660-ffff80001025e744: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491d64)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c0491d64-c0491e1c: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303460)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c000000000303460-c00000000030358c: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c9f8)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffe00019c9f8-ffffffe00019cabc: bpf_get_kallsym (STB_GLOBAL)
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
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5f70)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811d5f70-ffffffff811d601b: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8d30)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811c8d30-ffffffff811c8ddb: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3d40)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811d3d40-ffffffff811d3deb: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2050)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811e2050-ffffffff811e2110: bpf_get_kallsym (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
