# Function: <code>module_kallsyms_on_each_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110aa10)
Location: kernel/module.c:3841
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8110aa10-ffffffff8110aaa5: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811120c0)
Location: kernel/module.c:4012
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff811120c0-ffffffff81112162: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81119840)
Location: kernel/module.c:4029
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81119840-ffffffff811198e2: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111b1a0)
Location: kernel/module.c:4074
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8111b1a0-ffffffff8111b242: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81126710)
Location: kernel/module.c:4096
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81126710-ffffffff811267b4: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811344b0)
Location: kernel/module.c:4129
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff811344b0-ffffffff8113454f: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113fc90)
Location: kernel/module.c:4166
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8113fc90-ffffffff8113fd2f: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114afe0)
Location: kernel/module.c:4194
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8114afe0-ffffffff8114b07c: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156c60)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81156c60-ffffffff81156cfc: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81167810)
Location: kernel/module.c:4268
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81167810-ffffffff811678ac: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164010)
Location: kernel/module.c:4499
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81164010-ffffffff811640ac: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164dc0)
Location: kernel/module.c:4404
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
```
**Symbols:**

```
ffffffff81164dc0-ffffffff81164e7b: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a5d0)
Location: kernel/module.c:4425
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
```
**Symbols:**

```
ffffffff8118a5d0-ffffffff8118a68b: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff81191d20)
Location: kernel/module/kallsyms.c:485
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
```
**Symbols:**

```
ffffffff81191d20-ffffffff81191e09: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811cf410)
Location: kernel/module/kallsyms.c:497
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/trace/ftrace.c:ftrace_lookup_symbols
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
```
**Symbols:**

```
ffffffff811cf410-ffffffff811cf4f9: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(const char *modname, int (*fn)(void *, const char *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811e3560)
Location: kernel/module/kallsyms.c:476
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/trace/ftrace.c:ftrace_lookup_symbols
```
**Symbols:**

```
ffffffff811e3560-ffffffff811e3668: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(const char *modname, int (*fn)(void *, const char *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811f92c0)
Location: kernel/module/kallsyms.c:476
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/trace/ftrace.c:ftrace_lookup_symbols
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff811f92c0-ffffffff811f93c8: module_kallsyms_on_each_symbol (STB_GLOBAL)
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
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c60f8)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffff8000101c60f8-ffff8000101c61e0: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040d248)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
c040d248-c040d2fc: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022ddd0)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
c00000000022ddd0-c00000000022df18: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000146810)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffe000146810-ffffffe0001468c6: module_kallsyms_on_each_symbol (STB_GLOBAL)
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
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114f280)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8114f280-ffffffff8114f31c: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81142530)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81142530-ffffffff811425cc: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114d130)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff8114d130-ffffffff8114d1cc: module_kallsyms_on_each_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int module_kallsyms_on_each_symbol(int (*fn)(void *, const char *, struct module *, long unsigned int), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81159eb0)
Location: kernel/module.c:4261
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_find_object_symbol
  - kernel/kallsyms.c:kallsyms_on_each_symbol
```
**Symbols:**

```
ffffffff81159eb0-ffffffff81159f4c: module_kallsyms_on_each_symbol (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *modname</code>
</li>
<li>
<b>Param reordered. </b>
<code>fn, data</code> ➡️ <code>modname, fn, data</code>
</li>
<li>
<b>Param type changed. </b>
<code>int (*fn)(void *, const char *, struct module *, long unsigned int)</code> ➡️ <code>int (*fn)(void *, const char *, long unsigned int)</code>
</li>
</ul>
</details>
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
