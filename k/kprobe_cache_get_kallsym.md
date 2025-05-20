# Function: <code>kprobe_cache_get_kallsym</code>

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
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194040)
Location: kernel/kprobes.c:302
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff81194040-ffffffff811940b0: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195030)
Location: kernel/kprobes.c:303
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff81195030-ffffffff811950a3: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bdef0)
Location: kernel/kprobes.c:303
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811bdef0-ffffffff811bdf63: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f1270)
Location: kernel/kprobes.c:314
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff811f1270-ffffffff811f130f: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81237d60)
Location: kernel/kprobes.c:314
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff81237d60-ffffffff81237dff: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124ee40)
Location: kernel/kprobes.c:314
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff8124ee40-ffffffff8124eedf: kprobe_cache_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kprobe_cache_get_kallsym(struct kprobe_insn_cache *c, unsigned int *symnum, long unsigned int *value, char *type, char *sym);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81268d70)
Location: kernel/kprobes.c:314
Inline: False
Direct callers:
  - kernel/kprobes.c:kprobe_get_kallsym
  - kernel/kprobes.c:kprobe_get_kallsym
```
**Symbols:**

```
ffffffff81268d70-ffffffff81268e0f: kprobe_cache_get_kallsym (STB_GLOBAL)
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
