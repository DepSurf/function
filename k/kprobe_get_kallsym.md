# Function: <code>kprobe_get_kallsym</code>

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
In <code>5.0</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811952e0)
Location: kernel/kprobes.c:2287
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811952e0-ffffffff81195364: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811962f0)
Location: kernel/kprobes.c:2292
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811962f0-ffffffff81196374: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bf280)
Location: kernel/kprobes.c:2286
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811bf280-ffffffff811bf304: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f2690)
Location: kernel/kprobes.c:2504
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811f2690-ffffffff811f2721: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812393e0)
Location: kernel/kprobes.c:2511
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff812393e0-ffffffff81239471: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812503f0)
Location: kernel/kprobes.c:2524
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff812503f0-ffffffff81250481: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kprobe_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8126a240)
Location: kernel/kprobes.c:2509
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8126a240-ffffffff8126a2d1: kprobe_get_kallsym (STB_GLOBAL)
```
</details>
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
