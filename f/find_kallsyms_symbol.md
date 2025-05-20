# Function: <code>find_kallsyms_symbol</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113a230)
Location: kernel/module.c:3958
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff8113a230-ffffffff8113a3b6: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145940)
Location: kernel/module.c:3986
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff81145940-ffffffff81145ae4: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811514c0)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff811514c0-ffffffff81151664: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81161ae0)
Location: kernel/module.c:4060
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff81161ae0-ffffffff81161c6d: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115dbf0)
Location: kernel/module.c:4285
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff8115dbf0-ffffffff8115dd7d: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115ecb0)
Location: kernel/module.c:4189
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff8115ecb0-ffffffff8115ee3c: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81183d80)
Location: kernel/module.c:4202
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff81183d80-ffffffff81183f0c: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff81190f00)
Location: kernel/module/kallsyms.c:262
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
**Symbols:**

```
ffffffff81190f00-ffffffff811910e2: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811ce510)
Location: kernel/module/kallsyms.c:262
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_attrs
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
**Symbols:**

```
ffffffff811ce510-ffffffff811ce6f2: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811e26a0)
Location: kernel/module/kallsyms.c:256
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
**Symbols:**

```
ffffffff811e26a0-ffffffff811e28e2: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811f8430)
Location: kernel/module/kallsyms.c:256
Inline: False
Direct callers:
  - kernel/module/kallsyms.c:lookup_module_symbol_name
  - kernel/module/kallsyms.c:module_address_lookup
```
**Symbols:**

```
ffffffff811f8430-ffffffff811f8643: find_kallsyms_symbol (STB_LOCAL)
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
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c04c8)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffff8000101c04c8-ffff8000101c06a8: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0407af4)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
c0407af4-c0407cb0: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000226280)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
c000000000226280-c000000000226528: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014286e)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffe00014286e-ffffffe0001429ee: find_kallsyms_symbol (STB_LOCAL)
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
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81149ae0)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff81149ae0-ffffffff81149c84: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113cd90)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff8113cd90-ffffffff8113cf34: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147990)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff81147990-ffffffff81147b34: find_kallsyms_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *find_kallsyms_symbol(struct module *mod, long unsigned int addr, long unsigned int *size, long unsigned int *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811545a0)
Location: kernel/module.c:4053
Inline: False
Direct callers:
  - kernel/module.c:lookup_module_symbol_attrs
  - kernel/module.c:lookup_module_symbol_name
  - kernel/module.c:module_address_lookup
```
**Symbols:**

```
ffffffff811545a0-ffffffff81154744: find_kallsyms_symbol (STB_LOCAL)
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
