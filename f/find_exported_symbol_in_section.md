# Function: <code>find_exported_symbol_in_section</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:559
Inline: False
```
**Symbols:**

```
ffffffff811399a0-ffffffff81139a52: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8113fda6-ffffffff8113fdf8: find_exported_symbol_in_section.cold.73 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:555
Inline: False
```
**Symbols:**

```
ffffffff81144b50-ffffffff81144c01: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8114b0f6-ffffffff8114b136: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffff81150630-ffffffff811506f8: find_exported_symbol_in_section (STB_LOCAL)
ffffffff81156d76-ffffffff81156db8: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:569
Inline: False
```
**Symbols:**

```
ffffffff811610b0-ffffffff81161178: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8116797b-ffffffff811679bd: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:601
Inline: False
```
**Symbols:**

```
ffffffff8115d4a0-ffffffff8115d57d: find_exported_symbol_in_section (STB_LOCAL)
ffffffff81be3e55-ffffffff81be3e97: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e500)
Location: kernel/module.c:495
Inline: False
Direct callers:
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
```
**Symbols:**

```
ffffffff8115e500-ffffffff8115e5b5: find_exported_symbol_in_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:496
Inline: False
Direct callers:
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
  - kernel/module.c:find_symbol
```
**Symbols:**

```
ffffffff81183f80-ffffffff81184050: find_exported_symbol_in_section (STB_LOCAL)
ffffffff81cb2447-ffffffff81cb2464: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:271
Inline: False
Direct callers:
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
```
**Symbols:**

```
ffffffff8118b7e0-ffffffff8118b8b9: find_exported_symbol_in_section (STB_LOCAL)
ffffffff81e615ab-ffffffff81e615c0: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:269
Inline: False
Direct callers:
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
```
**Symbols:**

```
ffffffff811c7e60-ffffffff811c7f39: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8205aaff-ffffffff8205ab14: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:276
Inline: False
Direct callers:
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
```
**Symbols:**

```
ffffffff811dae60-ffffffff811daf39: find_exported_symbol_in_section (STB_LOCAL)
ffffffff820d9371-ffffffff820d9386: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:276
Inline: False
Direct callers:
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
  - kernel/module/main.c:find_symbol
```
**Symbols:**

```
ffffffff811f0b10-ffffffff811f0be9: find_exported_symbol_in_section (STB_LOCAL)
ffffffff821b4bf2-ffffffff821b4c07: find_exported_symbol_in_section.cold (STB_LOCAL)
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
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101bf408)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffff8000101bf408-ffff8000101bf51c: find_exported_symbol_in_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0406c38)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
c0406c38-c0406d60: find_exported_symbol_in_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000224c50)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
c000000000224c50-c000000000224df4: find_exported_symbol_in_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000141a3e)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffe000141a3e-ffffffe000141b48: find_exported_symbol_in_section (STB_LOCAL)
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
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffff81148c50-ffffffff81148d18: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8114f396-ffffffff8114f3d8: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffff8113bf00-ffffffff8113bfc8: find_exported_symbol_in_section (STB_LOCAL)
ffffffff81142646-ffffffff81142688: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffff81146b00-ffffffff81146bc8: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8114d246-ffffffff8114d288: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool find_exported_symbol_in_section(const struct symsearch *syms, struct module *owner, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:566
Inline: False
```
**Symbols:**

```
ffffffff81153710-ffffffff811537d8: find_exported_symbol_in_section (STB_LOCAL)
ffffffff8115a00d-ffffffff8115a04f: find_exported_symbol_in_section.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct find_symbol_arg *fsa</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
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
