# Function: <code>check_modinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81107d30)
Location: kernel/module.c:2849
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110f16b)
Location: kernel/module.c:2940
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81116a18)
Location: kernel/module.c:2955
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81117f8c)
Location: kernel/module.c:2998
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112356c)
Location: kernel/module.c:3016
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81131aa2)
Location: kernel/module.c:3039
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113d0f7)
Location: kernel/module.c:3033
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148887)
Location: kernel/module.c:3041
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81152b10-ffffffff81152d41: check_modinfo (STB_LOCAL)
ffffffff81156e0e-ffffffff81156eb9: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81163d60-ffffffff81163ee5: check_modinfo (STB_LOCAL)
ffffffff81167b3e-ffffffff81167ba9: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3287
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811608e0-ffffffff81160a91: check_modinfo (STB_LOCAL)
ffffffff81be4127-ffffffff81be4192: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3206
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81160b20-ffffffff81160d86: check_modinfo (STB_LOCAL)
ffffffff81bd5f2f-ffffffff81bd5fb1: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3228
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81185ce0-ffffffff81185f55: check_modinfo (STB_LOCAL)
ffffffff81cb2645-ffffffff81cb26dc: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1950
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8118c070-ffffffff8118c2b0: check_modinfo (STB_LOCAL)
ffffffff81e615ef-ffffffff81e61689: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1953
Inline: False
Direct callers:
  - kernel/module/main.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811c8870-ffffffff811c8b96: check_modinfo (STB_LOCAL)
ffffffff8205ab14-ffffffff8205ab29: check_modinfo.cold (STB_LOCAL)
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
In kernel/module/main.c (ffffffff811dd8fa)
Location: kernel/module/main.c:2068
Inline: True
Inline callers:
  - kernel/module/main.c:early_mod_check
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
In kernel/module/main.c (ffffffff811f35fa)
Location: kernel/module/main.c:2076
Inline: True
Inline callers:
  - kernel/module/main.c:early_mod_check
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
In kernel/module.c (ffff8000101c396c)
Location: kernel/module.c:3108
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (c040ab14)
Location: kernel/module.c:3108
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022a0f8)
Location: kernel/module.c:3108
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffe0001447b6)
Location: kernel/module.c:3108
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8114b130-ffffffff8114b361: check_modinfo (STB_LOCAL)
ffffffff8114f42e-ffffffff8114f4d9: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8113e3e0-ffffffff8113e611: check_modinfo (STB_LOCAL)
ffffffff811426de-ffffffff81142789: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81148fe0-ffffffff81149211: check_modinfo (STB_LOCAL)
ffffffff8114d2de-ffffffff8114d389: check_modinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_modinfo(struct module *mod, struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3108
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81155ca0-ffffffff81155ed1: check_modinfo (STB_LOCAL)
ffffffff8115a0a5-ffffffff8115a150: check_modinfo.cold (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
