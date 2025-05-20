# Function: <code>module_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105f40)
Location: kernel/module.c:3868
Inline: True
Direct callers:
  - kernel/module.c:m_show
  - kernel/module.c:print_modules
```
**Symbols:**

```
ffffffff81105f40-ffffffff81105feb: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d890)
Location: kernel/module.c:4039
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8110d890-ffffffff8110d93b: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811151a0)
Location: kernel/module.c:4060
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff811151a0-ffffffff81115246: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811161e0)
Location: kernel/module.c:4105
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff811161e0-ffffffff81116281: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121760)
Location: kernel/module.c:4127
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff81121760-ffffffff81121801: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112f250)
Location: kernel/module.c:4164
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8112f250-ffffffff8112f2f1: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113abe0)
Location: kernel/module.c:4202
Inline: True
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8113abe0-ffffffff8113ac81: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811452c0)
Location: kernel/module.c:4230
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff811452c0-ffffffff81145383: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81150dd0)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff81150dd0-ffffffff81150e93: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81162f20)
Location: kernel/module.c:4304
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff81162f20-ffffffff81162fc0: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f250)
Location: kernel/module.c:4535
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8115f250-ffffffff8115f2e3: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115fd00)
Location: kernel/module.c:4474
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8115fd00-ffffffff8115fd92: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81184eb0)
Location: kernel/module.c:4497
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff81184eb0-ffffffff81184f42: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff81190100)
Location: kernel/module/main.c:2974
Inline: False
Direct callers:
  - kernel/module/main.c:print_modules
  - kernel/module/procfs.c:m_show
```
**Symbols:**

```
ffffffff81190100-ffffffff811901a1: module_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf, bool show_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811cd0a0)
Location: kernel/module/main.c:2981
Inline: False
Direct callers:
  - kernel/module/main.c:print_modules
  - kernel/module/procfs.c:m_show
```
**Symbols:**

```
ffffffff811cd0a0-ffffffff811cd173: module_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf, bool show_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811e0980)
Location: kernel/module/main.c:3184
Inline: False
Direct callers:
  - kernel/module/main.c:print_modules
  - kernel/module/procfs.c:m_show
```
**Symbols:**

```
ffffffff811e0980-ffffffff811e0a53: module_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf, bool show_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f66b0)
Location: kernel/module/main.c:3195
Inline: False
Direct callers:
  - kernel/module/main.c:print_modules
  - kernel/module/procfs.c:m_show
```
**Symbols:**

```
ffffffff811f66b0-ffffffff811f6783: module_flags (STB_GLOBAL)
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
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bfc10)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffff8000101bfc10-ffff8000101bfd20: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407388)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
c0407388-c0407490: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000225510)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
c000000000225510-c000000000225638: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000141fae)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffe000141fae-ffffffe00014209c: module_flags (STB_LOCAL)
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
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811493f0)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff811493f0-ffffffff811494b3: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113c6a0)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff8113c6a0-ffffffff8113c763: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811472a0)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff811472a0-ffffffff81147363: module_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *module_flags(struct module *mod, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153eb0)
Location: kernel/module.c:4297
Inline: False
Direct callers:
  - kernel/module.c:print_modules
  - kernel/module.c:m_show
```
**Symbols:**

```
ffffffff81153eb0-ffffffff81153f73: module_flags (STB_LOCAL)
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
<code>bool show_state</code>
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
