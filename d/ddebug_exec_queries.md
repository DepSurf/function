# Function: <code>ddebug_exec_queries</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81414f10)
Location: lib/dynamic_debug.c:466
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81414f10-ffffffff8141504c: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8145cc40)
Location: lib/dynamic_debug.c:473
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff8145cc40-ffffffff8145cd80: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8147b740)
Location: lib/dynamic_debug.c:473
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff8147b740-ffffffff8147b880: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81484a90)
Location: lib/dynamic_debug.c:473
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff81484a90-ffffffff81484bdc: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814c0ad0)
Location: lib/dynamic_debug.c:477
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff814c0ad0-ffffffff814c0c1c: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:477
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff814f1830-ffffffff814f192b: ddebug_exec_queries (STB_LOCAL)
ffffffff814f1f1d-ffffffff814f1f7f: ddebug_exec_queries.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:477
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff81505550-ffffffff8150564b: ddebug_exec_queries (STB_LOCAL)
ffffffff81505de5-ffffffff81505e47: ddebug_exec_queries.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff81533570-ffffffff81533671: ddebug_exec_queries (STB_LOCAL)
ffffffff81533f30-ffffffff81533f92: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff815543b0-ffffffff815544b1: ddebug_exec_queries (STB_LOCAL)
ffffffff81554d70-ffffffff81554dd2: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:478
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
```
**Symbols:**

```
ffffffff815dd6d0-ffffffff815dd7d1: ddebug_exec_queries (STB_LOCAL)
ffffffff815de242-ffffffff815de2a4: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:518
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
```
**Symbols:**

```
ffffffff815fb370-ffffffff815fb472: ddebug_exec_queries (STB_LOCAL)
ffffffff81bf447c-ffffffff81bf44c7: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:518
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
```
**Symbols:**

```
ffffffff815ddfb0-ffffffff815de0b2: ddebug_exec_queries (STB_LOCAL)
ffffffff81be6344-ffffffff81be638f: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:518
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
```
**Symbols:**

```
ffffffff81649560-ffffffff81649662: ddebug_exec_queries (STB_LOCAL)
ffffffff81cddacf-ffffffff81cddb1a: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:522
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:dynamic_debug_exec_queries
```
**Symbols:**

```
ffffffff817602a0-ffffffff8176039d: ddebug_exec_queries (STB_LOCAL)
ffffffff81ea3fcf-ffffffff81ea4010: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188e840)
Location: lib/dynamic_debug.c:565
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:ddebug_apply_class_bitmap
```
**Symbols:**

```
ffffffff8188e840-ffffffff8188e97a: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818d0db0)
Location: lib/dynamic_debug.c:565
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:ddebug_apply_class_bitmap
```
**Symbols:**

```
ffffffff818d0db0-ffffffff818d0ee6: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81922da0)
Location: lib/dynamic_debug.c:566
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_dyndbg_module_param_cb
  - lib/dynamic_debug.c:ddebug_dyndbg_boot_param_cb
  - lib/dynamic_debug.c:ddebug_apply_class_bitmap
```
**Symbols:**

```
ffffffff81922da0-ffffffff81922ed6: ddebug_exec_queries (STB_LOCAL)
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
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffff800010660a30)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffff800010660a30-ffff800010660be0: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c08090d8)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
c08090d8-c0809cb0: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c0000000008146a0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
c0000000008146a0-c000000000814910: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffe00048d700)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffe00048d700-ffffffe00048d85e: ddebug_exec_queries (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff8154c990-ffffffff8154ca91: ddebug_exec_queries (STB_LOCAL)
ffffffff8154d350-ffffffff8154d3b2: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff8153cc70-ffffffff8153cd71: ddebug_exec_queries (STB_LOCAL)
ffffffff8153d630-ffffffff8153d692: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff815486d0-ffffffff815487d1: ddebug_exec_queries (STB_LOCAL)
ffffffff81549090-ffffffff815490f2: ddebug_exec_queries.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ddebug_exec_queries(char *query, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:479
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_dyndbg_param_cb
```
**Symbols:**

```
ffffffff81562520-ffffffff81562621: ddebug_exec_queries (STB_LOCAL)
ffffffff81562ee0-ffffffff81562f42: ddebug_exec_queries.cold (STB_LOCAL)
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
