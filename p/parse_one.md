# Function: <code>parse_one</code>

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
In kernel/params.c (ffffffff8109fb48)
Location: kernel/params.c:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a323f)
Location: kernel/params.c:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a82ff)
Location: kernel/params.c:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a51e6)
Location: kernel/params.c:120
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810ab8a9)
Location: kernel/params.c:126
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810b24c9)
Location: kernel/params.c:126
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810bb5f9)
Location: kernel/params.c:126
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810c1521)
Location: kernel/params.c:114
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810c7911)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810cf840-ffffffff810cfa40: parse_one (STB_LOCAL)
ffffffff810cfe28-ffffffff810cfe3d: parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810ca390-ffffffff810ca590: parse_one (STB_LOCAL)
ffffffff81bdc1f8-ffffffff81bdc20d: parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810cbe50-ffffffff810cc050: parse_one (STB_LOCAL)
ffffffff81bce31b-ffffffff81bce330: parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810df050-ffffffff810df24a: parse_one (STB_LOCAL)
ffffffff81ca5659-ffffffff81ca566e: parse_one.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff810f8ec0)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810f8ec0-ffffffff810f90b2: parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111ba70)
Location: kernel/params.c:115
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff8111ba70-ffffffff8111bc62: parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, int (*handle_unknown)(char *, char *, const char *, void *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81128cc0)
Location: kernel/params.c:116
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81128cc0-ffffffff81128eb2: parse_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_one(char *param, char *val, const char *doing, const struct kernel_param *params, unsigned int num_params, s16 min_level, s16 max_level, void *arg, parse_unknown_fn handle_unknown);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81133340)
Location: kernel/params.c:117
Inline: False
Direct callers:
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff81133340-ffffffff81133532: parse_one (STB_LOCAL)
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
In kernel/params.c (ffff800010126b94)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (c0379548)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (c000000000171088)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffe0000de468)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810c1c91)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810b047a)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810c11e1)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810c9611)
Location: kernel/params.c:115
Inline: True
Inline callers:
  - kernel/params.c:parse_args
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*handle_unknown)(char *, char *, const char *, void *)</code> ➡️ <code>parse_unknown_fn handle_unknown</code>
</li>
</ul>
</details>
</li>
</ul>
