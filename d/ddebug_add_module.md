# Function: <code>ddebug_add_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81414140)
Location: lib/dynamic_debug.c:840
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81414140-ffffffff8141420b: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8145bfe0)
Location: lib/dynamic_debug.c:842
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8145bfe0-ffffffff8145c0ab: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8147aad0)
Location: lib/dynamic_debug.c:842
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8147aad0-ffffffff8147ab9b: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81483dd0)
Location: lib/dynamic_debug.c:842
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81483dd0-ffffffff81483e9b: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814bfe10)
Location: lib/dynamic_debug.c:846
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff814bfe10-ffffffff814bfedb: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:846
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff814f1be4-ffffffff814f1c05: ddebug_add_module.cold.21 (STB_LOCAL)
ffffffff814f0d10-ffffffff814f0dc1: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:846
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81505ab3-ffffffff81505ad4: ddebug_add_module.cold.17 (STB_LOCAL)
ffffffff81504a10-ffffffff81504ac1: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8153405e)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8153405e-ffffffff8153409f: ddebug_add_module.cold (STB_LOCAL)
ffffffff815339b0-ffffffff81533a3d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81554e9e)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81554e9e-ffffffff81554edf: ddebug_add_module.cold (STB_LOCAL)
ffffffff815547f0-ffffffff8155487d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:890
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff815de38e-ffffffff815de3cf: ddebug_add_module.cold (STB_LOCAL)
ffffffff815ddbe0-ffffffff815ddc6d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:944
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81bf4595-ffffffff81bf45c8: ddebug_add_module.cold (STB_LOCAL)
ffffffff815fb8d0-ffffffff815fb95f: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:948
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81be6489-ffffffff81be64bc: ddebug_add_module.cold (STB_LOCAL)
ffffffff815de530-ffffffff815de5bf: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:960
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81cddcfe-ffffffff81cddd31: ddebug_add_module.cold (STB_LOCAL)
ffffffff81649fe0-ffffffff8164a06f: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:950
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff81ea406f-ffffffff81ea40a0: ddebug_add_module.cold (STB_LOCAL)
ffffffff817606c0-ffffffff8176075a: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug_info *di, const char *modname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188f210)
Location: lib/dynamic_debug.c:1266
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8188f210-ffffffff8188f223: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug_info *di, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818cefc0)
Location: lib/dynamic_debug.c:1226
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_module_notify
```
**Symbols:**

```
ffffffff818cefc0-ffffffff818cf227: ddebug_add_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ddebug_add_module(struct _ddebug_info *di, const char *modname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81920df0)
Location: lib/dynamic_debug.c:1230
Inline: False
Direct callers:
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:ddebug_module_notify
```
**Symbols:**

```
ffffffff81920df0-ffffffff81921086: ddebug_add_module (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffff800010661040)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffff800010661040-ffff800010661124: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c080a0b4)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
c080a0b4-c080a178: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c000000000814cd0)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
c000000000814cd0-c000000000814dec: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffe00048dbc4)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffe00048dbc4-ffffffe00048dc98: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8154d47e)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8154d47e-ffffffff8154d4bf: ddebug_add_module.cold (STB_LOCAL)
ffffffff8154cdd0-ffffffff8154ce5d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8153d75e)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8153d75e-ffffffff8153d79f: ddebug_add_module.cold (STB_LOCAL)
ffffffff8153d0b0-ffffffff8153d13d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815491be)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff815491be-ffffffff815491ff: ddebug_add_module.cold (STB_LOCAL)
ffffffff81548b10-ffffffff81548b9d: ddebug_add_module (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ddebug_add_module(struct _ddebug *tab, unsigned int n, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8156300e)
Location: lib/dynamic_debug.c:883
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - lib/dynamic_debug.c:dynamic_debug_init
  - lib/dynamic_debug.c:dynamic_debug_init
```
**Symbols:**

```
ffffffff8156300e-ffffffff8156304f: ddebug_add_module.cold (STB_LOCAL)
ffffffff81562960-ffffffff815629ed: ddebug_add_module (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct _ddebug_info *di</code>
</li>
<li>
<b>Param added. </b>
<code>const char *modname</code>
</li>
<li>
<b>Param removed. </b>
<code>struct _ddebug *tab</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int n</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
</ul>
</details>
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
