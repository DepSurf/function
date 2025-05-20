# Function: <code>kdb_getstr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81133370)
Location: kernel/debug/kdb/kdb_io.c:442
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff81133370-ffffffff811333ca: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8113b790)
Location: kernel/debug/kdb/kdb_io.c:442
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff8113b790-ffffffff8113b7ea: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81145540)
Location: kernel/debug/kdb/kdb_io.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff81145540-ffffffff8114559a: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811472c0)
Location: kernel/debug/kdb/kdb_io.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
  - kernel/debug/kdb/kdb_main.c:kdb_main_loop
```
**Symbols:**

```
ffffffff811472c0-ffffffff8114731a: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81153b40)
Location: kernel/debug/kdb/kdb_io.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81153b40-ffffffff81153b9a: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81162660)
Location: kernel/debug/kdb/kdb_io.c:443
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81162660-ffffffff811626ba: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8116f540)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8116f540-ffffffff8116f59a: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8117c2e0)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8117c2e0-ffffffff8117c33c: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81188180)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81188180-ffffffff811881dc: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8119bbfd)
Location: kernel/debug/kdb/kdb_io.c:436
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8119c6b0-ffffffff8119c70c: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:436
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81be4e14-ffffffff81be4e2c: kdb_getstr.cold (STB_LOCAL)
ffffffff811997d0-ffffffff81199861: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:436
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81bd6c88-ffffffff81bd6ca0: kdb_getstr.cold (STB_LOCAL)
ffffffff8119a5e0-ffffffff8119a671: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:436
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81cb3cbe-ffffffff81cb3cd6: kdb_getstr.cold (STB_LOCAL)
ffffffff811c4450-ffffffff811c44e1: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (0)
Location: kernel/debug/kdb/kdb_io.c:435
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81e64b68-ffffffff81e64b80: kdb_getstr.cold (STB_LOCAL)
ffffffff811f7c70-ffffffff811f7d09: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8123f010)
Location: kernel/debug/kdb/kdb_io.c:435
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8123f010-ffffffff8123f0b9: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff81256080)
Location: kernel/debug/kdb/kdb_io.c:449
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff81256080-ffffffff81256129: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8126ff00)
Location: kernel/debug/kdb/kdb_io.c:449
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8126ff00-ffffffff8126ffa9: kdb_getstr (STB_GLOBAL)
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
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffff8000101fe250)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffff8000101fe250-ffff8000101fe2c8: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c043e3a0)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
c043e3a0-c043e408: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (c000000000277040)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
c000000000277040-c000000000277124: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811807a0)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff811807a0-ffffffff811807fc: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff811738e0)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff811738e0-ffffffff8117393c: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8117e570)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8117e570-ffffffff8117e5cc: kdb_getstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kdb_getstr(char *buffer, size_t bufsize, const char *prompt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_io.c (ffffffff8118be90)
Location: kernel/debug/kdb/kdb_io.c:446
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:vkdb_printf
```
**Symbols:**

```
ffffffff8118be90-ffffffff8118beec: kdb_getstr (STB_GLOBAL)
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
