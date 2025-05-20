# Function: <code>klp_module_going</code>

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
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f0320)
Location: kernel/livepatch/core.c:1006
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff810f0320-ffffffff810f0468: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7480)
Location: kernel/livepatch/core.c:1013
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff810f7480-ffffffff810f75c8: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f85e0)
Location: kernel/livepatch/core.c:903
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff810f85e0-ffffffff810f8729: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811028e0)
Location: kernel/livepatch/core.c:970
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811028e0-ffffffff81102928: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8110ab90)
Location: kernel/livepatch/core.c:1030
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8110ab90-ffffffff8110abd7: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116380)
Location: kernel/livepatch/core.c:1030
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81116380-ffffffff811163c7: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:1184
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8112083e-ffffffff81120851: klp_module_going.cold (STB_LOCAL)
ffffffff811203e0-ffffffff8112042b: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112cb10)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8112cb10-ffffffff8112cb5a: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113b180)
Location: kernel/livepatch/core.c:1249
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff8113b180-ffffffff8113b1cc: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135c70)
Location: kernel/livepatch/core.c:1249
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81135c70-ffffffff81135cbc: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81136ab0)
Location: kernel/livepatch/core.c:1248
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81136ab0-ffffffff81136afc: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811596f0)
Location: kernel/livepatch/core.c:1248
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811596f0-ffffffff8115973c: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81182ca0)
Location: kernel/livepatch/core.c:1245
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff81182ca0-ffffffff81182cfd: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811bdce0)
Location: kernel/livepatch/core.c:1270
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811bdce0-ffffffff811bdd3d: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811d06c0)
Location: kernel/livepatch/core.c:1298
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811d06c0-ffffffff811d071d: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e5310)
Location: kernel/livepatch/core.c:1298
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811e5310-ffffffff811e536d: klp_module_going (STB_GLOBAL)
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
Location: include/linux/livepatch.h:223
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
Location: include/linux/livepatch.h:223
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f16c0)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
c0000000001f16c0-c0000000001f1754: klp_module_going (STB_GLOBAL)
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
Location: include/linux/livepatch.h:223
Inline: True
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
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811250f0)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff811250f0-ffffffff8112513a: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81117b50)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81117b50-ffffffff81117b9a: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81122fe0)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81122fe0-ffffffff8112302a: klp_module_going (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_module_going(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112f5f0)
Location: kernel/livepatch/core.c:1185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8112f5f0-ffffffff8112f63a: klp_module_going (STB_GLOBAL)
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
