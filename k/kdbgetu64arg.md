# Function: <code>kdbgetu64arg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811352a0)
Location: kernel/debug/kdb/kdb_main.c:357
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811352a0-ffffffff81135317: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8113d750)
Location: kernel/debug/kdb/kdb_main.c:357
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8113d750-ffffffff8113d7c7: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81147500)
Location: kernel/debug/kdb/kdb_main.c:356
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81147500-ffffffff81147577: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811492d0)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811492d0-ffffffff81149347: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81155b80)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81155b80-ffffffff81155bf7: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81164690)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81164690-ffffffff81164707: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811713a0)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811713a0-ffffffff81171417: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8117e100)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8117e100-ffffffff8117e177: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81189f80)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81189f80-ffffffff81189ff7: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119dc9c)
Location: kernel/debug/kdb/kdb_main.c:358
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8119eb00-ffffffff8119eb77: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119acdc)
Location: kernel/debug/kdb/kdb_main.c:358
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8119bbc0-ffffffff8119bc37: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8119bb1c)
Location: kernel/debug/kdb/kdb_main.c:385
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8119c920-ffffffff8119c997: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811c5a7c)
Location: kernel/debug/kdb/kdb_main.c:384
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811c6660-ffffffff811c66d7: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811f974c)
Location: kernel/debug/kdb/kdb_main.c:436
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811f9ff0-ffffffff811fa079: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81240c7c)
Location: kernel/debug/kdb/kdb_main.c:436
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff812415b0-ffffffff81241639: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81257d0c)
Location: kernel/debug/kdb/kdb_main.c:436
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81258640-ffffffff812586c9: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81271bfc)
Location: kernel/debug/kdb/kdb_main.c:435
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81272530-ffffffff812725b9: kdbgetu64arg (STB_GLOBAL)
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
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffff8000102012e0)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffff8000102012e0-ffff800010201384: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c0440340)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
c0440340-c04403e0: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (c00000000027a240)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
c00000000027a240-c00000000027a300: kdbgetu64arg (STB_GLOBAL)
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
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811825a0)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811825a0-ffffffff81182617: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff811756e0)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff811756e0-ffffffff81175757: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff81180370)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff81180370-ffffffff811803e7: kdbgetu64arg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kdbgetu64arg(const char *arg, u64 *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_main.c (ffffffff8118dc90)
Location: kernel/debug/kdb/kdb_main.c:359
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_main.c:kdb_rm
```
**Symbols:**

```
ffffffff8118dc90-ffffffff8118dd07: kdbgetu64arg (STB_GLOBAL)
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
