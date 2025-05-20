# Function: <code>module_enable_ro</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void module_enable_ro(const struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811073d0)
Location: kernel/module.c:1902
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811073d0-ffffffff8110743a: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110e880)
Location: kernel/module.c:1918
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocations
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8110e880-ffffffff8110e90c: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811188e1)
Location: kernel/module.c:1913
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811158a0-ffffffff8111592c: module_enable_ro.part.59 (STB_LOCAL)
ffffffff81116200-ffffffff8111621e: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81119e22)
Location: kernel/module.c:1940
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81116880-ffffffff8111690c: module_enable_ro.part.55 (STB_LOCAL)
ffffffff811176c0-ffffffff811176df: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811253d6)
Location: kernel/module.c:1948
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81121e80-ffffffff81121f0c: module_enable_ro.part.56 (STB_LOCAL)
ffffffff81122ca0-ffffffff81122cbf: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811337a0)
Location: kernel/module.c:1947
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8112f970-ffffffff8112fa03: module_enable_ro.part.61 (STB_LOCAL)
ffffffff81130d40-ffffffff81130d5e: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113f11c)
Location: kernel/module.c:1948
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8113b0a0-ffffffff8113b133: module_enable_ro.part.63 (STB_LOCAL)
ffffffff8113c5f0-ffffffff8113c60e: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114a528)
Location: kernel/module.c:1956
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81146650-ffffffff81146715: module_enable_ro.part.0 (STB_LOCAL)
ffffffff81147cc0-ffffffff81147cde: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8115618c)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81152230-ffffffff811522f5: module_enable_ro.part.0 (STB_LOCAL)
ffffffff81153b00-ffffffff81153b1e: module_enable_ro (STB_GLOBAL)
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
In kernel/module.c (ffffffff81163576)
Location: kernel/module.c:2038
Inline: True
Inline callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81162b30-ffffffff81162be7: module_enable_ro.part.0 (STB_LOCAL)
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
In kernel/module.c (ffffffff8115ee76)
Location: kernel/module.c:2097
Inline: True
Inline callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8115ed70-ffffffff8115ee27: module_enable_ro.part.0 (STB_LOCAL)
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
In kernel/module.c (ffffffff8115fbab)
Location: kernel/module.c:2007
Inline: True
Inline callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8115f9e0-ffffffff8115fa97: module_enable_ro.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811873c7)
Location: kernel/module.c:2009
Inline: True
Direct callers:
  - kernel/module.c:complete_formation
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81187390-ffffffff8118749c: module_enable_ro (STB_LOCAL)
ffffffff81cb27aa-ffffffff81cb27bf: module_enable_ro.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/strict_rwx.c (0)
Location: kernel/module/strict_rwx.c:92
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff81e61b50-ffffffff81e61b65: module_enable_ro.cold (STB_LOCAL)
ffffffff81190610-ffffffff81190726: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/strict_rwx.c (0)
Location: kernel/module/strict_rwx.c:92
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff8205abd9-ffffffff8205abee: module_enable_ro.cold (STB_LOCAL)
ffffffff811cdb00-ffffffff811cdc16: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/strict_rwx.c (0)
Location: kernel/module/strict_rwx.c:35
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff820d947b-ffffffff820d9490: module_enable_ro.cold (STB_LOCAL)
ffffffff811e1390-ffffffff811e14cd: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/strict_rwx.c (0)
Location: kernel/module/strict_rwx.c:35
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff821b4cfc-ffffffff821b4d11: module_enable_ro.cold (STB_LOCAL)
ffffffff811f70c0-ffffffff811f71fd: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffff8000101c54c0)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - arch/arm64/kernel/ftrace.c:ftrace_make_call
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffff8000101c0ef8-ffff8000101c0fbc: module_enable_ro.part.0 (STB_LOCAL)
ffff8000101c2e78-ffff8000101c2eb8: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (c040c640)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
c04085b4-c0408664: module_enable_ro.part.0 (STB_LOCAL)
c040a0a8-c040a0d8: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: include/linux/module.h:856
Inline: True
```
```
In kernel/module.c (0)
Location: include/linux/module.h:856
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/module.h:856
Inline: True
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
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114e7ac)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8114a850-ffffffff8114a915: module_enable_ro.part.0 (STB_LOCAL)
ffffffff8114c120-ffffffff8114c13e: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81141a5c)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8113db00-ffffffff8113dbc5: module_enable_ro.part.0 (STB_LOCAL)
ffffffff8113f3d0-ffffffff8113f3ee: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114c65c)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81148700-ffffffff811487c5: module_enable_ro.part.0 (STB_LOCAL)
ffffffff81149fd0-ffffffff81149fee: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void module_enable_ro(const struct module *mod, bool after_init);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81159342)
Location: kernel/module.c:2013
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81155370-ffffffff81155435: module_enable_ro.part.0 (STB_LOCAL)
ffffffff81156cb0-ffffffff81156cce: module_enable_ro (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool after_init</code>
</li>
</ul>
</details>
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
