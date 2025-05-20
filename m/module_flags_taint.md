# Function: <code>module_flags_taint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81105bf0)
Location: kernel/module.c:1133
Inline: True
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff81105bf0-ffffffff81105c48: module_flags_taint.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8110d4e0)
Location: kernel/module.c:1138
Inline: True
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff8110d4e0-ffffffff8110d538: module_flags_taint.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811137f0)
Location: kernel/module.c:1141
Inline: False
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff811137f0-ffffffff81113830: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114ce0)
Location: kernel/module.c:1163
Inline: False
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff81114ce0-ffffffff81114d20: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81120250)
Location: kernel/module.c:1171
Inline: False
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff81120250-ffffffff811202b3: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112dce0)
Location: kernel/module.c:1170
Inline: False
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff8112dce0-ffffffff8112dd43: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811395d0)
Location: kernel/module.c:1171
Inline: False
Direct callers:
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff811395d0-ffffffff81139633: module_flags_taint (STB_LOCAL)
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
In kernel/module.c (ffffffff811452ef)
Location: kernel/module.c:1167
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150dff)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162e90)
Location: kernel/module.c:1184
Inline: False
Direct callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff81162e90-ffffffff81162ee3: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f1c0)
Location: kernel/module.c:1216
Inline: False
Direct callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff8115f1c0-ffffffff8115f213: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115fc70)
Location: kernel/module.c:1124
Inline: False
Direct callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff8115fc70-ffffffff8115fcc3: module_flags_taint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t module_flags_taint(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1124
Inline: False
Direct callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
**Symbols:**

```
ffffffff81184da0-ffffffff81184e71: module_flags_taint (STB_LOCAL)
ffffffff81cb251a-ffffffff81cb253f: module_flags_taint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t module_flags_taint(long unsigned int taints, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:872
Inline: False
Direct callers:
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:show_taint
```
**Symbols:**

```
ffffffff81e61829-ffffffff81e61846: module_flags_taint.cold (STB_LOCAL)
ffffffff8118de00-ffffffff8118deba: module_flags_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t module_flags_taint(long unsigned int taints, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:875
Inline: False
Direct callers:
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:show_taint
```
**Symbols:**

```
ffffffff8205ab3e-ffffffff8205ab5b: module_flags_taint.cold (STB_LOCAL)
ffffffff811ca9a0-ffffffff811caa5a: module_flags_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t module_flags_taint(long unsigned int taints, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:873
Inline: False
Direct callers:
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:show_taint
```
**Symbols:**

```
ffffffff820d93ef-ffffffff820d940c: module_flags_taint.cold (STB_LOCAL)
ffffffff811ddbf0-ffffffff811ddcaa: module_flags_taint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t module_flags_taint(long unsigned int taints, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:873
Inline: False
Direct callers:
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:module_flags
  - kernel/module/main.c:show_taint
```
**Symbols:**

```
ffffffff821b4c70-ffffffff821b4c8d: module_flags_taint.cold (STB_LOCAL)
ffffffff811f38f0-ffffffff811f39aa: module_flags_taint (STB_GLOBAL)
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
In kernel/module.c (ffff8000101bfc68)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
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
In kernel/module.c (c04073f0)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
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
In kernel/module.c (c000000000225590)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
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
In kernel/module.c (ffffffe000141fde)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114941f)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c6cf)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811472cf)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153edf)
Location: kernel/module.c:1181
Inline: True
Inline callers:
  - kernel/module.c:module_flags
  - kernel/module.c:show_taint
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int taints</code>
</li>
<li>
<b>Param removed. </b>
<code>struct module *mod</code>
</li>
</ul>
</details>
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
