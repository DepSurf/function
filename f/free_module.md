# Function: <code>free_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811075c0)
Location: kernel/module.c:1986
Inline: False
Direct callers:
  - kernel/module.c:SyS_delete_module
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff811075c0-ffffffff81107899: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110ea90)
Location: kernel/module.c:2086
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff8110ea90-ffffffff8110ec26: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811163b0)
Location: kernel/module.c:2098
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff811163b0-ffffffff81116546: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81117870)
Location: kernel/module.c:2125
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff81117870-ffffffff81117a06: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81122e50)
Location: kernel/module.c:2133
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:SyS_delete_module
```
**Symbols:**

```
ffffffff81122e50-ffffffff81122fe9: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81130ef0)
Location: kernel/module.c:2132
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81130ef0-ffffffff8113109b: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c7a0)
Location: kernel/module.c:2131
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8113c7a0-ffffffff8113c94b: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147ea0)
Location: kernel/module.c:2133
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81147ea0-ffffffff81148033: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153ce0)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81153ce0-ffffffff81153e73: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81165710)
Location: kernel/module.c:2182
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81165710-ffffffff811658f3: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161e80)
Location: kernel/module.c:2244
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81161e80-ffffffff81162050: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162910)
Location: kernel/module.c:2156
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81162910-ffffffff81162ae0: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2158
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
```
**Symbols:**

```
ffffffff81187e80-ffffffff81188060: free_module (STB_LOCAL)
ffffffff81cb2821-ffffffff81cb2836: free_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1145
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff8118dfd0-ffffffff8118e13e: free_module (STB_LOCAL)
ffffffff81e61846-ffffffff81e6185b: free_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1146
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811cabe0-ffffffff811cad4e: free_module (STB_LOCAL)
ffffffff8205ab5b-ffffffff8205ab70: free_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1241
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811ddeb0-ffffffff811de071: free_module (STB_LOCAL)
ffffffff820d940c-ffffffff820d9420: free_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1241
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811f3bb0-ffffffff811f3d71: free_module (STB_LOCAL)
ffffffff821b4c8d-ffffffff821b4ca1: free_module.cold (STB_LOCAL)
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
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c3108)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__arm64_sys_delete_module
```
**Symbols:**

```
ffff8000101c3108-ffff8000101c32fc: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040a304)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
c040a304-c040a4f4: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002296d0)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
c0000000002296d0-c0000000002298e0: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe0001440ae)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__se_sys_delete_module
```
**Symbols:**

```
ffffffe0001440ae-ffffffe0001442ba: free_module (STB_LOCAL)
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
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114c300)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8114c300-ffffffff8114c493: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113f5b0)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8113f5b0-ffffffff8113f743: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a1b0)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff8114a1b0-ffffffff8114a343: free_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_module(struct module *mod);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156e90)
Location: kernel/module.c:2190
Inline: False
Direct callers:
  - kernel/module.c:do_init_module
  - kernel/module.c:__ia32_sys_delete_module
  - kernel/module.c:__x64_sys_delete_module
```
**Symbols:**

```
ffffffff81156e90-ffffffff8115703c: free_module (STB_LOCAL)
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
