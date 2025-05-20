# Function: <code>resolve_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81106530)
Location: kernel/module.c:1364
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81106530-ffffffff81106636: resolve_symbol.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8110de40)
Location: kernel/module.c:1369
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8110de40-ffffffff8110df45: resolve_symbol.isra.57 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81115750)
Location: kernel/module.c:1362
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81115750-ffffffff81115817: resolve_symbol.isra.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81116440)
Location: kernel/module.c:1379
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81116440-ffffffff81116507: resolve_symbol.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811219d0)
Location: kernel/module.c:1387
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811219d0-ffffffff81121a97: resolve_symbol.isra.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8112f4d0)
Location: kernel/module.c:1386
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8112f4d0-ffffffff8112f597: resolve_symbol.isra.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113ae60)
Location: kernel/module.c:1387
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113ae60-ffffffff8113af27: resolve_symbol.isra.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81146480)
Location: kernel/module.c:1383
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81146480-ffffffff81146549: resolve_symbol.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81151f80-ffffffff81152097: resolve_symbol (STB_LOCAL)
ffffffff81156dce-ffffffff81156df7: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1435
Inline: False
Direct callers:
  - kernel/module.c:resolve_symbol_wait
  - kernel/module.c:resolve_symbol_wait
```
**Symbols:**

```
ffffffff81163890-ffffffff811639ae: resolve_symbol (STB_LOCAL)
ffffffff81167ad4-ffffffff81167afd: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1485
Inline: False
Direct callers:
  - kernel/module.c:resolve_symbol_wait
  - kernel/module.c:resolve_symbol_wait
```
**Symbols:**

```
ffffffff8115f9b0-ffffffff8115fc35: resolve_symbol (STB_LOCAL)
ffffffff81be400a-ffffffff81be4076: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1396
Inline: False
Direct callers:
  - kernel/module.c:simplify_symbols
  - kernel/module.c:simplify_symbols
```
**Symbols:**

```
ffffffff811603f0-ffffffff811605b7: resolve_symbol (STB_LOCAL)
ffffffff81bd5e4f-ffffffff81bd5ecf: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1396
Inline: False
Direct callers:
  - kernel/module.c:simplify_symbols
  - kernel/module.c:simplify_symbols
```
**Symbols:**

```
ffffffff81185590-ffffffff8118577d: resolve_symbol (STB_LOCAL)
ffffffff81cb253f-ffffffff81cb25e5: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1051
Inline: False
Direct callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
```
**Symbols:**

```
ffffffff8118d1f0-ffffffff8118d3d0: resolve_symbol (STB_LOCAL)
ffffffff81e616eb-ffffffff81e61775: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1054
Inline: False
Direct callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
```
**Symbols:**

```
ffffffff811c9c10-ffffffff811c9e4f: resolve_symbol (STB_LOCAL)
ffffffff8205ab29-ffffffff8205ab3e: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1109
Inline: False
Direct callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
```
**Symbols:**

```
ffffffff811dcc40-ffffffff811dcffe: resolve_symbol (STB_LOCAL)
ffffffff820d93da-ffffffff820d93ef: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1109
Inline: False
Direct callers:
  - kernel/module/main.c:simplify_symbols
  - kernel/module/main.c:simplify_symbols
```
**Symbols:**

```
ffffffff811f2ab0-ffffffff811f2cf5: resolve_symbol (STB_LOCAL)
ffffffff821b4c5b-ffffffff821b4c70: resolve_symbol.cold (STB_LOCAL)
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
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c2a38)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000101c2a38-ffff8000101c2bc0: resolve_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0408d34)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
c0408d34-c0408e8c: resolve_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000227180)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
c000000000227180-c000000000227530: resolve_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001430f2)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffe0001430f2-ffffffe000143212: resolve_symbol (STB_LOCAL)
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
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114a5a0-ffffffff8114a6b7: resolve_symbol (STB_LOCAL)
ffffffff8114f3ee-ffffffff8114f417: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113d850-ffffffff8113d967: resolve_symbol (STB_LOCAL)
ffffffff8114269e-ffffffff811426c7: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81148450-ffffffff81148567: resolve_symbol (STB_LOCAL)
ffffffff8114d29e-ffffffff8114d2c7: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
const struct kernel_symbol *resolve_symbol(struct module *mod, const struct load_info *info, const char *name, char *ownername);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1432
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811550a0-ffffffff811551b7: resolve_symbol (STB_LOCAL)
ffffffff8115a065-ffffffff8115a08e: resolve_symbol.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
