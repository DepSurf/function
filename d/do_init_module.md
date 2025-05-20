# Function: <code>do_init_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118c104)
Location: kernel/module.c:3222
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8118c104-ffffffff8118c2d3: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8119ee4e)
Location: kernel/module.c:3360
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8119ee4e-ffffffff8119f045: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811ae8b6)
Location: kernel/module.c:3375
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811ae8b6-ffffffff811aeab6: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111b397)
Location: kernel/module.c:3418
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8111b397-ffffffff8111b585: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81126907)
Location: kernel/module.c:3438
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81126907-ffffffff81126b0d: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3465
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81131580-ffffffff81131797: do_init_module (STB_LOCAL)
ffffffff8113466b-ffffffff81134691: do_init_module.cold.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3465
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113ce30-ffffffff8113d047: do_init_module (STB_LOCAL)
ffffffff8113fe4b-ffffffff8113fe71: do_init_module.cold.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3494
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81148560-ffffffff811487a7: do_init_module (STB_LOCAL)
ffffffff8114b1c5-ffffffff8114b1ec: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811543e0-ffffffff81154627: do_init_module (STB_LOCAL)
ffffffff81156ef5-ffffffff81156f1c: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3568
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81165be0-ffffffff81165e4d: do_init_module (STB_LOCAL)
ffffffff81167bff-ffffffff81167c26: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3749
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811622f0-ffffffff81162575: do_init_module (STB_LOCAL)
ffffffff81be420c-ffffffff81be4233: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3647
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81162db0-ffffffff81163035: do_init_module (STB_LOCAL)
ffffffff81bd60b1-ffffffff81bd60d8: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3674
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81188330-ffffffff81188580: do_init_module (STB_LOCAL)
ffffffff81cb284e-ffffffff81cb288a: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2419
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8118e400-ffffffff8118e60a: do_init_module (STB_LOCAL)
ffffffff81e61873-ffffffff81e618ae: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2448
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811cad60-ffffffff811cafb2: do_init_module (STB_LOCAL)
ffffffff8205ab70-ffffffff8205ab85: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2493
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811de090-ffffffff811de316: do_init_module (STB_LOCAL)
ffffffff820d9420-ffffffff820d9435: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2504
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811f3d90-ffffffff811f4045: do_init_module (STB_LOCAL)
ffffffff821b4ca1-ffffffff821b4cb6: do_init_module.cold (STB_LOCAL)
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
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c35a8)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000101c35a8-ffff8000101c37ec: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040a78c)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c040a78c-c040a9f0: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000229c40)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c000000000229c40-c000000000229f14: do_init_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000144488)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffe000144488-ffffffe000144682: do_init_module (STB_LOCAL)
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
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114ca00-ffffffff8114cc47: do_init_module (STB_LOCAL)
ffffffff8114f515-ffffffff8114f53c: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8113fcb0-ffffffff8113fef7: do_init_module (STB_LOCAL)
ffffffff811427c5-ffffffff811427ec: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8114a8b0-ffffffff8114aaf7: do_init_module (STB_LOCAL)
ffffffff8114d3c5-ffffffff8114d3ec: do_init_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_init_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3561
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811575a0-ffffffff811577e7: do_init_module (STB_LOCAL)
ffffffff8115a18c-ffffffff8115a1b3: do_init_module.cold (STB_LOCAL)
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
