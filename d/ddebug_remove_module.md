# Function: <code>ddebug_remove_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81413cc0)
Location: lib/dynamic_debug.c:918
Inline: False
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81413cc0-ffffffff81413d8e: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8145bd50)
Location: lib/dynamic_debug.c:920
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8145bd50-ffffffff8145be20: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8147a830)
Location: lib/dynamic_debug.c:920
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8147a830-ffffffff8147a900: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81483b40)
Location: lib/dynamic_debug.c:920
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81483b40-ffffffff81483c0b: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814bfb80)
Location: lib/dynamic_debug.c:924
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff814bfb80-ffffffff814bfc4b: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:924
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff814f1b93-ffffffff814f1bae: ddebug_remove_module.cold.18 (STB_LOCAL)
ffffffff814f0af0-ffffffff814f0ba0: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:924
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81505ad4-ffffffff81505aef: ddebug_remove_module.cold.18 (STB_LOCAL)
ffffffff81504ad0-ffffffff81504b80: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff815340c5-ffffffff815340e0: ddebug_remove_module.cold (STB_LOCAL)
ffffffff81533a80-ffffffff81533b10: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81554f05-ffffffff81554f20: ddebug_remove_module.cold (STB_LOCAL)
ffffffff815548c0-ffffffff81554950: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:968
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff815de3ed-ffffffff815de408: ddebug_remove_module.cold (STB_LOCAL)
ffffffff815ddd10-ffffffff815ddda0: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:1022
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81bf45e2-ffffffff81bf45f6: ddebug_remove_module.cold (STB_LOCAL)
ffffffff815fba00-ffffffff815fba8f: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:1026
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81be64d6-ffffffff81be64ea: ddebug_remove_module.cold (STB_LOCAL)
ffffffff815de650-ffffffff815de6df: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:1038
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81cddd4b-ffffffff81cddd5f: ddebug_remove_module.cold (STB_LOCAL)
ffffffff8164a100-ffffffff8164a18f: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:1028
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff81ea40ba-ffffffff81ea40ce: ddebug_remove_module.cold (STB_LOCAL)
ffffffff81760800-ffffffff817608b1: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188f300)
Location: lib/dynamic_debug.c:1321
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff8188f300-ffffffff8188f3c0: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818cf264)
Location: lib/dynamic_debug.c:1317
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_module_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff819210c4)
Location: lib/dynamic_debug.c:1321
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_module_notify
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
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffff800010661198)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffff800010661198-ffff800010661278: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c080a1e4)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c080a1e4-c080a2a8: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c000000000814e80)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c000000000814e80-c000000000814fc0: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffe00048dcf2)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffe00048dcf2-ffffffe00048dd96: ddebug_remove_module (STB_GLOBAL)
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
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8154d4e5-ffffffff8154d500: ddebug_remove_module.cold (STB_LOCAL)
ffffffff8154cea0-ffffffff8154cf30: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8153d7c5-ffffffff8153d7e0: ddebug_remove_module.cold (STB_LOCAL)
ffffffff8153d180-ffffffff8153d210: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81549225-ffffffff81549240: ddebug_remove_module.cold (STB_LOCAL)
ffffffff81548be0-ffffffff81548c70: ddebug_remove_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ddebug_remove_module(const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:961
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81563075-ffffffff81563090: ddebug_remove_module.cold (STB_LOCAL)
ffffffff81562a30-ffffffff81562ac0: ddebug_remove_module (STB_GLOBAL)
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
