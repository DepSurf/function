# Function: <code>ftrace_free_mem</code>

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
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81167810)
Location: kernel/trace/ftrace.c:6091
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81167810-ffffffff81167b46: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81176510)
Location: kernel/trace/ftrace.c:6077
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81176510-ffffffff81176831: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184150)
Location: kernel/trace/ftrace.c:6037
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81184150-ffffffff8118448b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190ef0)
Location: kernel/trace/ftrace.c:6085
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81190ef0-ffffffff8119122b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119cef0)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff8119cef0-ffffffff8119d24b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6611
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff811b497f-ffffffff811b499f: ftrace_free_mem.cold (STB_LOCAL)
ffffffff811b2f00-ffffffff811b31a9: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6764
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81be544d-ffffffff81be546d: ftrace_free_mem.cold (STB_LOCAL)
ffffffff811b0a60-ffffffff811b0d19: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6769
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81bd7251-ffffffff81bd7269: ftrace_free_mem.cold (STB_LOCAL)
ffffffff811b1410-ffffffff811b1763: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6770
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81cb47a2-ffffffff81cb47f4: ftrace_free_mem.cold (STB_LOCAL)
ffffffff811db2a0-ffffffff811db606: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7204
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81e65792-ffffffff81e657e4: ftrace_free_mem.cold (STB_LOCAL)
ffffffff81211300-ffffffff81211677: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7320
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff8205cf4c-ffffffff8205cf86: ftrace_free_mem.cold (STB_LOCAL)
ffffffff8125a870-ffffffff8125abf4: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7135
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff820db8e0-ffffffff820db91a: ftrace_free_mem.cold (STB_LOCAL)
ffffffff81271d10-ffffffff81272094: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7137
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff821b7640-ffffffff821b767a: ftrace_free_mem.cold (STB_LOCAL)
ffffffff8128c1a0-ffffffff8128c584: ftrace_free_mem (STB_GLOBAL)
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
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010215d98)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffff800010215d98-ffff800010216100: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454b08)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
c0454b08-c0454eac: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297950)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
c000000000297950-c000000000297e30: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001759c2)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffe0001759c2-ffffffe000175d2c: ftrace_free_mem (STB_GLOBAL)
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
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81195510)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81195510-ffffffff8119586b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188620)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff81188620-ffffffff8118897b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811932e0)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff811932e0-ffffffff8119363b: ftrace_free_mem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ftrace_free_mem(struct module *mod, void *start_ptr, void *end_ptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a0eb0)
Location: kernel/trace/ftrace.c:6118
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/trace/ftrace.c:ftrace_free_init_mem
```
**Symbols:**

```
ffffffff811a0eb0-ffffffff811a120b: ftrace_free_mem (STB_GLOBAL)
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
