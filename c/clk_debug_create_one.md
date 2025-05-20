# Function: <code>clk_debug_create_one</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e4f00)
Location: drivers/clk/clk.c:2105
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_debug_init
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff816e4f00-ffffffff816e5093: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749690)
Location: drivers/clk/clk.c:2134
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81749690-ffffffff81749823: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81531f10)
Location: drivers/clk/clk.c:2129
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81531f10-ffffffff815320a3: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545110)
Location: drivers/clk/clk.c:2155
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81545110-ffffffff815452d4: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8360)
Location: drivers/clk/clk.c:2272
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff815a8360-ffffffff815a852a: clk_debug_create_one (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff815e3f89)
Location: drivers/clk/clk.c:2612
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff815e1670-ffffffff815e17af: clk_debug_create_one.part.49 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff815fe377)
Location: drivers/clk/clk.c:2906
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff815fb7c0-ffffffff815fb91d: clk_debug_create_one.part.54 (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff8162f8c8)
Location: drivers/clk/clk.c:3090
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff8162dbe0-ffffffff8162dd63: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81651cc7)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff8164f8c0-ffffffff8164fa7f: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81700e70)
Location: drivers/clk/clk.c:3196
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff816fcb50-ffffffff816fcd15: clk_debug_create_one.part.0 (STB_LOCAL)
ffffffff8170280d-ffffffff81702828: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171e390)
Location: drivers/clk/clk.c:3243
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81719a90-ffffffff81719c55: clk_debug_create_one.part.0 (STB_LOCAL)
ffffffff81c040c7-ffffffff81c040e2: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ff420)
Location: drivers/clk/clk.c:3256
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff816fad90-ffffffff816faf55: clk_debug_create_one.part.0 (STB_LOCAL)
ffffffff81bf5a61-ffffffff81bf5a7c: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81779b96)
Location: drivers/clk/clk.c:3256
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81775510-ffffffff817756d5: clk_debug_create_one.part.0 (STB_LOCAL)
ffffffff81cf3010-ffffffff81cf302b: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clk_debug_create_one(struct clk_core *core, struct dentry *pdentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff818affe6)
Location: drivers/clk/clk.c:3314
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff818ab230-ffffffff818ab406: clk_debug_create_one.part.0 (STB_LOCAL)
ffffffff81ebb1b4-ffffffff81ebb1df: clk_debug_create_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fc32e)
Location: drivers/clk/clk.c:3504
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff819f68d0-ffffffff819f6aa6: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a44d78)
Location: drivers/clk/clk.c:3549
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81a3f070-ffffffff81a3f246: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a90888)
Location: drivers/clk/clk.c:3594
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81a8a9a0-ffffffff81a8ab79: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c2804)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffff8000107be830-ffff8000107be9fc: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (c08ed43c)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
c08eb040-c08eb218: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffe0005102da)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffe00050dc64-ffffffe00050de2e: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81617d27)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81615920-ffffffff81615adf: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160c257)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81609e50-ffffffff8160a00f: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81645b07)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff81643700-ffffffff816438bf: clk_debug_create_one.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81660097)
Location: drivers/clk/clk.c:3120
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_debug_init
```
**Symbols:**

```
ffffffff8165db40-ffffffff8165dcff: clk_debug_create_one.part.0 (STB_LOCAL)
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
</ul>
