# Function: <code>ftrace_mod_get_kallsym</code>

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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81167750)
Location: kernel/trace/ftrace.c:5987
Inline: False
Direct callers:
  - kernel/kallsyms.c:get_ksymbol_ftrace_mod
```
**Symbols:**

```
ffffffff81167750-ffffffff8116780b: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81176450)
Location: kernel/trace/ftrace.c:5973
Inline: False
Direct callers:
  - kernel/kallsyms.c:get_ksymbol_ftrace_mod
```
**Symbols:**

```
ffffffff81176450-ffffffff8117650b: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184090)
Location: kernel/trace/ftrace.c:5933
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81184090-ffffffff8118414b: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5981
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811923a0-ffffffff811923b3: ftrace_mod_get_kallsym.cold (STB_LOCAL)
ffffffff81190e30-ffffffff81190eee: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119ce30)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8119ce30-ffffffff8119ceed: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2e40)
Location: kernel/trace/ftrace.c:6511
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811b2e40-ffffffff811b2efd: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6649
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81be5435-ffffffff81be544d: ftrace_mod_get_kallsym.cold (STB_LOCAL)
ffffffff811b08c0-ffffffff811b0a5f: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6654
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81bd7239-ffffffff81bd7251: ftrace_mod_get_kallsym.cold (STB_LOCAL)
ffffffff811b1260-ffffffff811b1404: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6655
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81cb478a-ffffffff81cb47a2: ftrace_mod_get_kallsym.cold (STB_LOCAL)
ffffffff811db0f0-ffffffff811db294: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7089
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81e6577a-ffffffff81e65792: ftrace_mod_get_kallsym.cold (STB_LOCAL)
ffffffff81211100-ffffffff812112f1: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125a650)
Location: kernel/trace/ftrace.c:7205
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8125a650-ffffffff8125a859: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81271b30)
Location: kernel/trace/ftrace.c:7020
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81271b30-ffffffff81271cf5: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128bfc0)
Location: kernel/trace/ftrace.c:7022
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8128bfc0-ffffffff8128c185: ftrace_mod_get_kallsym (STB_GLOBAL)
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010215c98)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffff800010215c98-ffff800010215d98: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454a1c)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c0454a1c-c0454b08: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297800)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c000000000297800-c000000000297948: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001758fc)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffe0001758fc-ffffffe0001759c2: ftrace_mod_get_kallsym (STB_GLOBAL)
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
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81195450)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81195450-ffffffff8119550d: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188560)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81188560-ffffffff8118861d: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81193220)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81193220-ffffffff811932dd: ftrace_mod_get_kallsym (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ftrace_mod_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name, char *module_name, int *exported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a0dd0)
Location: kernel/trace/ftrace.c:6018
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811a0dd0-ffffffff811a0eb0: ftrace_mod_get_kallsym (STB_GLOBAL)
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
