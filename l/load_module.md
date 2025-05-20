# Function: <code>load_module</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81108790)
Location: kernel/module.c:3421
Inline: False
Direct callers:
  - kernel/module.c:SYSC_init_module
  - kernel/module.c:SYSC_finit_module
```
```
In drivers/md/dm-target.c (ffffffff816a749a)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81108790-ffffffff8110a38b: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110fc40)
Location: kernel/module.c:3574
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/module.c:SYSC_init_module
```
```
In drivers/md/dm-target.c (ffffffff817077fa)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff8110fc40-ffffffff81111a01: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81117520)
Location: kernel/module.c:3589
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/module.c:SYSC_init_module
```
```
In drivers/md/dm-target.c (ffffffff817396ca)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81117520-ffffffff8111918b: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81118bb0)
Location: kernel/module.c:3632
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/module.c:SYSC_init_module
```
```
In drivers/md/dm-target.c (ffffffff81752f4a)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81118bb0-ffffffff8111aac3: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81124140)
Location: kernel/module.c:3654
Inline: False
Direct callers:
  - kernel/module.c:SYSC_finit_module
  - kernel/module.c:SYSC_init_module
```
```
In drivers/md/dm-target.c (ffffffff817c519a)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81124140-ffffffff81126048: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags, bool can_do_ima_check);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3686
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8180ddea)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811324e0-ffffffff81133d92: load_module (STB_LOCAL)
ffffffff8113476b-ffffffff81134935: load_module.cold.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3686
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81839d2a)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff8113dbc0-ffffffff8113f57f: load_module (STB_LOCAL)
ffffffff8113fef8-ffffffff81140119: load_module.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3718
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8187c8bc)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81149680-ffffffff8114a894: load_module (STB_LOCAL)
ffffffff8114b299-ffffffff8114b4a7: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff818ae69c)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81155300-ffffffff811564f9: load_module (STB_LOCAL)
ffffffff81156f1c-ffffffff8115713e: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3792
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8197e90e)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811669d0-ffffffff811670ae: load_module (STB_LOCAL)
ffffffff81167c26-ffffffff81167cb9: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3988
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81982d1e)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81163100-ffffffff81163875: load_module (STB_LOCAL)
ffffffff81be425c-ffffffff81be4311: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3888
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8196713e)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81163b20-ffffffff8116462c: load_module (STB_LOCAL)
ffffffff81bd60fd-ffffffff81bd6232: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3900
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81a0f33e)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811891f0-ffffffff81189da0: load_module (STB_LOCAL)
ffffffff81cb28d2-ffffffff81cb2a5a: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2650
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/module/main.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81b77aa7)
Location: drivers/md/dm-target.c:45
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff8118f050-ffffffff8118fd18: load_module (STB_LOCAL)
ffffffff81e618ae-ffffffff81e61a6b: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2694
Inline: False
Direct callers:
  - kernel/module/main.c:__do_sys_finit_module
  - kernel/module/main.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81d14f87)
Location: drivers/md/dm-target.c:45
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811cbef0-ffffffff811ccc41: load_module (STB_LOCAL)
ffffffff8205ab85-ffffffff8205abd9: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2820
Inline: False
Direct callers:
  - kernel/module/main.c:init_module_from_file
  - kernel/module/main.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81d7e0f7)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811df480-ffffffff811e016c: load_module (STB_LOCAL)
ffffffff820d9435-ffffffff820d947b: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:2831
Inline: False
Direct callers:
  - kernel/module/main.c:init_module_from_file
  - kernel/module/main.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff81e356f7)
Location: drivers/md/dm-target.c:46
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811f51b0-ffffffff811f5e9c: load_module (STB_LOCAL)
ffffffff821b4cb6-ffffffff821b4cfc: load_module.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c4710)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffff800010b05160)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffff8000101c4710-ffff8000101c588c: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040b968)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__se_sys_finit_module
  - kernel/module.c:__se_sys_init_module
```
```
In drivers/md/dm-target.c (c0be4078)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
c040b968-c040cae4: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022b930)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (c000000000bf5420)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
c00000000022b930-c00000000022d36c: load_module (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014506e)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffe0006f4190)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffe00014506e-ffffffe0001461b4: load_module (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8185451c)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff8114d920-ffffffff8114eb19: load_module (STB_LOCAL)
ffffffff8114f53c-ffffffff8114f75e: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff8181bb2c)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff81140bd0-ffffffff81141dc9: load_module (STB_LOCAL)
ffffffff811427ec-ffffffff81142a0e: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff818a3b4c)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff8114b7d0-ffffffff8114c9c9: load_module (STB_LOCAL)
ffffffff8114d3ec-ffffffff8114d60e: load_module.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int load_module(struct load_info *info, const char *uargs, int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3785
Inline: False
Direct callers:
  - kernel/module.c:__do_sys_finit_module
  - kernel/module.c:__do_sys_init_module
```
```
In drivers/md/dm-target.c (ffffffff818bfd8c)
Location: drivers/md/dm-target.c:44
Inline: True
Inline callers:
  - drivers/md/dm-target.c:dm_get_target_type
```
**Symbols:**

```
ffffffff811584c0-ffffffff811596c8: load_module (STB_LOCAL)
ffffffff8115a1b3-ffffffff8115a3d5: load_module.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool can_do_ima_check</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool can_do_ima_check</code>
</li>
</ul>
</details>
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
