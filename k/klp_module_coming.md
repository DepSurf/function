# Function: <code>klp_module_coming</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f0140)
Location: kernel/livepatch/core.c:940
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810f0140-ffffffff810f031e: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f72b0)
Location: kernel/livepatch/core.c:947
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810f72b0-ffffffff810f7476: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f8410)
Location: kernel/livepatch/core.c:833
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810f8410-ffffffff810f85dd: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811026b0)
Location: kernel/livepatch/core.c:888
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811026b0-ffffffff811028db: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:948
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8110ade4-ffffffff8110af0d: klp_module_coming.cold.23 (STB_LOCAL)
ffffffff8110aa90-ffffffff8110ab8a: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:948
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811165d4-ffffffff811166fd: klp_module_coming.cold.23 (STB_LOCAL)
ffffffff81116280-ffffffff8111637a: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811206e8-ffffffff8112083e: klp_module_coming.cold (STB_LOCAL)
ffffffff81120300-ffffffff811203d8: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8112cdfd-ffffffff8112cf4d: klp_module_coming.cold (STB_LOCAL)
ffffffff8112ca20-ffffffff8112cb0e: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1168
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113b4ae-ffffffff8113b5fd: klp_module_coming.cold (STB_LOCAL)
ffffffff8113b070-ffffffff8113b17a: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1168
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81be31bd-ffffffff81be330c: klp_module_coming.cold (STB_LOCAL)
ffffffff81135b60-ffffffff81135c6a: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1167
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81bd508d-ffffffff81bd51dc: klp_module_coming.cold (STB_LOCAL)
ffffffff811369a0-ffffffff81136aa3: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1167
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81cafc9b-ffffffff81cafdea: klp_module_coming.cold (STB_LOCAL)
ffffffff811595e0-ffffffff811596e3: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1164
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81e6091b-ffffffff81e60a5b: klp_module_coming.cold (STB_LOCAL)
ffffffff81182b90-ffffffff81182c91: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1189
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8205a57e-ffffffff8205a593: klp_module_coming.cold (STB_LOCAL)
ffffffff811bda40-ffffffff811bdcc5: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1217
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff820d8dac-ffffffff820d8dc1: klp_module_coming.cold (STB_LOCAL)
ffffffff811d0420-ffffffff811d06a5: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1217
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff821b44e5-ffffffff821b44fa: klp_module_coming.cold (STB_LOCAL)
ffffffff811e5070-ffffffff811e52f5: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/livepatch.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: include/linux/livepatch.h:222
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f1210)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c0000000001f1210-c0000000001f16b4: klp_module_coming (STB_GLOBAL)
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
Location: include/linux/livepatch.h:222
Inline: True
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
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811253dd-ffffffff8112552d: klp_module_coming.cold (STB_LOCAL)
ffffffff81125000-ffffffff811250ee: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81117e3d-ffffffff81117f8d: klp_module_coming.cold (STB_LOCAL)
ffffffff81117a60-ffffffff81117b4e: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811232cd-ffffffff8112341d: klp_module_coming.cold (STB_LOCAL)
ffffffff81122ef0-ffffffff81122fde: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int klp_module_coming(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1109
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8112f8dd-ffffffff8112fa2d: klp_module_coming.cold (STB_LOCAL)
ffffffff8112f500-ffffffff8112f5ee: klp_module_coming (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
