# Function: <code>module_arch_freeing_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811075b0)
Location: kernel/module.c:1981
Inline: True
Direct callers:
  - kernel/module.c:free_module
  - kernel/module.c:do_init_module
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff811075b0-ffffffff811075bb: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110ea80)
Location: kernel/module.c:2081
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8110ea80-ffffffff8110ea8b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811163a0)
Location: kernel/module.c:2093
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff811163a0-ffffffff811163ab: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2120
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81117860-ffffffff8111786b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2128
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81122e40-ffffffff81122e4b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2127
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81130ee0-ffffffff81130eeb: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2126
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8113c790-ffffffff8113c79b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81147e90)
Location: kernel/module.c:2128
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81147e90-ffffffff81147e9b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81153cd0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81153cd0-ffffffff81153cdb: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2177
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81165700-ffffffff8116570b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2239
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81161e70-ffffffff81161e7b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2149
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81162900-ffffffff8116290b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2151
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81187e70-ffffffff81187e7b: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1138
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff8118dfc0-ffffffff8118dfcf: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1141
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811cabc0-ffffffff811cabcf: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1196
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811dde90-ffffffff811dde9f: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (0)
Location: kernel/module/main.c:1196
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811f3b90-ffffffff811f3b9f: module_arch_freeing_init (STB_WEAK)
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
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffff8000101c30f0-ffff8000101c3108: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c040a2ec-c040a304: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (c0000000002296c0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
c0000000002296c0-c0000000002296cc: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffe000144094-ffffffe0001440ae: module_arch_freeing_init (STB_WEAK)
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
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114c2f0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8114c2f0-ffffffff8114c2fb: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113f5a0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8113f5a0-ffffffff8113f5ab: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a1a0)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff8114a1a0-ffffffff8114a1ab: module_arch_freeing_init (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void module_arch_freeing_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81156e80)
Location: kernel/module.c:2185
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
**Symbols:**

```
ffffffff81156e80-ffffffff81156e8b: module_arch_freeing_init (STB_WEAK)
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
