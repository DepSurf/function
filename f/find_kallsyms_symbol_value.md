# Function: <code>find_kallsyms_symbol_value</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81139930)
Location: kernel/module.c:4127
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81139930-ffffffff811399a0: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81144ae0)
Location: kernel/module.c:4155
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81144ae0-ffffffff81144b50: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811505c0)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811505c0-ffffffff81150630: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81162300)
Location: kernel/module.c:4229
Inline: True
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81162300-ffffffff81162369: find_kallsyms_symbol_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8115e360)
Location: kernel/module.c:4460
Inline: True
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff8115e360-ffffffff8115e3c9: find_kallsyms_symbol_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8115f380)
Location: kernel/module.c:4364
Inline: True
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff8115f380-ffffffff8115f3e9: find_kallsyms_symbol_value.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811837d0)
Location: kernel/module.c:4385
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811837d0-ffffffff81183840: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff81191bd0)
Location: kernel/module/kallsyms.c:445
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81191bd0-ffffffff81191c5a: find_kallsyms_symbol_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811cf2a0)
Location: kernel/module/kallsyms.c:445
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
  - kernel/module/kallsyms.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811cf2a0-ffffffff811cf32a: find_kallsyms_symbol_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811e3510)
Location: kernel/module/kallsyms.c:466
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff811e3510-ffffffff811e3547: find_kallsyms_symbol_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811f9270)
Location: kernel/module/kallsyms.c:466
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check_attach_target
```
**Symbols:**

```
ffffffff811f9270-ffffffff811f92a7: find_kallsyms_symbol_value (STB_GLOBAL)
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
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bf370)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffff8000101bf370-ffff8000101bf408: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0406bb8)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
c0406bb8-c0406c38: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002249f0)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
c0000000002249f0-c000000000224c50: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001419b6)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffe0001419b6-ffffffe000141a3e: find_kallsyms_symbol_value (STB_LOCAL)
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
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148be0)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81148be0-ffffffff81148c50: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113be90)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff8113be90-ffffffff8113bf00: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81146a90)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff81146a90-ffffffff81146b00: find_kallsyms_symbol_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int find_kallsyms_symbol_value(struct module *mod, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811536a0)
Location: kernel/module.c:4222
Inline: False
Direct callers:
  - kernel/module.c:module_kallsyms_lookup_name
  - kernel/module.c:module_kallsyms_lookup_name
```
**Symbols:**

```
ffffffff811536a0-ffffffff81153710: find_kallsyms_symbol_value (STB_LOCAL)
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
