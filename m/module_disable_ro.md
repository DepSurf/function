# Function: <code>module_disable_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81107360)
Location: kernel/module.c:1894
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81107360-ffffffff811073ca: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e800)
Location: kernel/module.c:1909
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocations
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8110e800-ffffffff8110e880: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811182d9)
Location: kernel/module.c:1901
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81115820-ffffffff811158a0: module_disable_ro.part.58 (STB_LOCAL)
ffffffff811161e0-ffffffff811161fa: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8111a113)
Location: kernel/module.c:1928
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81116800-ffffffff81116880: module_disable_ro.part.54 (STB_LOCAL)
ffffffff811176a0-ffffffff811176bb: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811256ca)
Location: kernel/module.c:1936
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81121e00-ffffffff81121e80: module_disable_ro.part.55 (STB_LOCAL)
ffffffff81122c80-ffffffff81122c9b: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81133b55)
Location: kernel/module.c:1935
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8112f8f0-ffffffff8112f970: module_disable_ro.part.60 (STB_LOCAL)
ffffffff81130d20-ffffffff81130d3a: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113ec5b)
Location: kernel/module.c:1936
Inline: True
Inline callers:
  - kernel/module.c:load_module
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113b020-ffffffff8113b0a0: module_disable_ro.part.62 (STB_LOCAL)
ffffffff8113c5d0-ffffffff8113c5ea: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147c30)
Location: kernel/module.c:1944
Inline: False
```
**Symbols:**

```
ffffffff81147c30-ffffffff81147cba: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153a70)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
ffffffff81153a70-ffffffff81153afa: module_disable_ro (STB_GLOBAL)
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
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c2df0)
Location: kernel/module.c:2001
Inline: False
Direct callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
```
**Symbols:**

```
ffff8000101c2df0-ffff8000101c2e78: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040a024)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
c040a024-c040a0a8: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:857
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114c090)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
ffffffff8114c090-ffffffff8114c11a: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113f340)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
ffffffff8113f340-ffffffff8113f3ca: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149f40)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
ffffffff81149f40-ffffffff81149fca: module_disable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void module_disable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156c20)
Location: kernel/module.c:2001
Inline: False
```
**Symbols:**

```
ffffffff81156c20-ffffffff81156caa: module_disable_ro (STB_GLOBAL)
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
