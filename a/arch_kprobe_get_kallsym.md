# Function: <code>arch_kprobe_get_kallsym</code>

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
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811952d0)
Location: kernel/kprobes.c:2281
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811952d0-ffffffff811952e0: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811962e0)
Location: kernel/kprobes.c:2286
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811962e0-ffffffff811962f0: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bf270)
Location: kernel/kprobes.c:2280
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811bf270-ffffffff811bf280: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f2670)
Location: kernel/kprobes.c:2498
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811f2670-ffffffff811f2684: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812393b0)
Location: kernel/kprobes.c:2505
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff812393b0-ffffffff812393c4: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812503c0)
Location: kernel/kprobes.c:2518
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff812503c0-ffffffff812503d4: arch_kprobe_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_kprobe_get_kallsym(unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8126a210)
Location: kernel/kprobes.c:2503
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff8126a210-ffffffff8126a224: arch_kprobe_get_kallsym (STB_WEAK)
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
