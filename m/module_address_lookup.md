# Function: <code>module_address_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110a620)
Location: kernel/module.c:3700
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8110a620-ffffffff8110a69c: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81111cd0)
Location: kernel/module.c:3871
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81111cd0-ffffffff81111d49: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81119450)
Location: kernel/module.c:3888
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81119450-ffffffff811194c9: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8111adb0)
Location: kernel/module.c:3933
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8111adb0-ffffffff8111ae26: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81126340)
Location: kernel/module.c:3955
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81126340-ffffffff811263b6: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811340f0)
Location: kernel/module.c:3988
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff811340f0-ffffffff81134166: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113f8d0)
Location: kernel/module.c:4017
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8113f8d0-ffffffff8113f946: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114abf0)
Location: kernel/module.c:4045
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8114abf0-ffffffff8114ac66: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156850)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81156850-ffffffff811568c6: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811673f0)
Location: kernel/module.c:4119
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff811673f0-ffffffff81167466: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164190)
Location: kernel/module.c:4350
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81164190-ffffffff81164206: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81164f60)
Location: kernel/module.c:4254
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81164f60-ffffffff81164fd6: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8118a120)
Location: kernel/module.c:4267
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_buildid
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8118a120-ffffffff8118a1cf: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff81191720)
Location: kernel/module/kallsyms.c:327
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_buildid
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81191720-ffffffff811917ee: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811cedb0)
Location: kernel/module/kallsyms.c:327
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_buildid
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff811cedb0-ffffffff811cee5f: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811e2fc0)
Location: kernel/module/kallsyms.c:324
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_buildid
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff811e2fc0-ffffffff811e306f: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, const unsigned char **modbuildid, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/kallsyms.c (ffffffff811f8d20)
Location: kernel/module/kallsyms.c:324
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup_buildid
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff811f8d20-ffffffff811f8dcf: module_address_lookup (STB_GLOBAL)
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
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c5c10)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffff8000101c5c10-ffff8000101c5cac: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040ce2c)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
c040ce2c-c040ce9c: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022d730)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
c00000000022d730-c00000000022d838: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe00014644c)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffe00014644c-ffffffe0001464c2: module_address_lookup (STB_GLOBAL)
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
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114ee70)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8114ee70-ffffffff8114eee6: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81142120)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81142120-ffffffff81142196: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114cd20)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff8114cd20-ffffffff8114cd96: module_address_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *module_address_lookup(long unsigned int addr, long unsigned int *size, long unsigned int *offset, char **modname, char *namebuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81159a20)
Location: kernel/module.c:4112
Inline: False
Direct callers:
  - kernel/kallsyms.c:kallsyms_lookup
  - kernel/kallsyms.c:kallsyms_lookup_size_offset
```
**Symbols:**

```
ffffffff81159a20-ffffffff81159aad: module_address_lookup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const unsigned char **modbuildid</code>
</li>
<li>
<b>Param reordered. </b>
<code>addr, size, offset, modname, namebuf</code> ➡️ <code>addr, size, offset, modname, modbuildid, namebuf</code>
</li>
</ul>
</details>
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
