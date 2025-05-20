# Function: <code>klp_find_object_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e89a0)
Location: kernel/livepatch/core.c:171
Inline: False
```
**Symbols:**

```
ffffffff810e89a0-ffffffff810e8ab0: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810eeef0)
Location: kernel/livepatch/core.c:173
Inline: False
```
**Symbols:**

```
ffffffff810eeef0-ffffffff810ef007: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6060)
Location: kernel/livepatch/core.c:173
Inline: False
```
**Symbols:**

```
ffffffff810f6060-ffffffff810f6177: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f76d0)
Location: kernel/livepatch/core.c:142
Inline: False
```
**Symbols:**

```
ffffffff810f76d0-ffffffff810f77ed: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811017c0)
Location: kernel/livepatch/core.c:137
Inline: False
```
**Symbols:**

```
ffffffff811017c0-ffffffff811018dd: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:137
Inline: False
```
**Symbols:**

```
ffffffff81109c10-ffffffff81109cef: klp_find_object_symbol (STB_LOCAL)
ffffffff8110abd7-ffffffff8110ac29: klp_find_object_symbol.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:137
Inline: False
```
**Symbols:**

```
ffffffff811153e0-ffffffff811154bf: klp_find_object_symbol (STB_LOCAL)
ffffffff811163c7-ffffffff81116419: klp_find_object_symbol.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff8111f3c0-ffffffff8111f496: klp_find_object_symbol (STB_LOCAL)
ffffffff81120451-ffffffff811204aa: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff8112bb10-ffffffff8112bbe6: klp_find_object_symbol (STB_LOCAL)
ffffffff8112cb5a-ffffffff8112cbb3: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:155
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff81139c50-ffffffff81139d26: klp_find_object_symbol (STB_LOCAL)
ffffffff8113b1ef-ffffffff8113b248: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:155
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff81134740-ffffffff81134816: klp_find_object_symbol (STB_LOCAL)
ffffffff81be2efe-ffffffff81be2f57: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:156
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff81135630-ffffffff811356fd: klp_find_object_symbol (STB_LOCAL)
ffffffff81bd4da8-ffffffff81bd4dfd: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:156
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff81158110-ffffffff811581dd: klp_find_object_symbol (STB_LOCAL)
ffffffff81caf795-ffffffff81caf7ea: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:156
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff81181580-ffffffff81181656: klp_find_object_symbol (STB_LOCAL)
ffffffff81e60440-ffffffff81e60494: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811bbe70)
Location: kernel/livepatch/core.c:163
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff811bbe70-ffffffff811bbf9d: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811ce810)
Location: kernel/livepatch/core.c:156
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff811ce810-ffffffff811ce935: klp_find_object_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e33f0)
Location: kernel/livepatch/core.c:156
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/livepatch/core.c:klp_resolve_symbols
```
**Symbols:**

```
ffffffff811e33f0-ffffffff811e3515: klp_find_object_symbol (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001eeff0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
c0000000001eeff0-c0000000001ef1b0: klp_find_object_symbol (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff811240f0-ffffffff811241c6: klp_find_object_symbol (STB_LOCAL)
ffffffff8112513a-ffffffff81125193: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff81116b50-ffffffff81116c26: klp_find_object_symbol (STB_LOCAL)
ffffffff81117b9a-ffffffff81117bf3: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff81121fe0-ffffffff811220b6: klp_find_object_symbol (STB_LOCAL)
ffffffff8112302a-ffffffff81123083: klp_find_object_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int klp_find_object_symbol(const char *objname, const char *name, long unsigned int sympos, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:154
Inline: False
```
**Symbols:**

```
ffffffff8112e5f0-ffffffff8112e6c6: klp_find_object_symbol (STB_LOCAL)
ffffffff8112f63a-ffffffff8112f693: klp_find_object_symbol.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
