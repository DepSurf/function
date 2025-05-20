# Function: <code>kallsyms_symbol_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff81137b80)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81137b80-ffffffff81137d16: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff81140050)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81140050-ffffffff811401fd: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff81149e40)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81149e40-ffffffff81149fed: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff8114bca0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8114bca0-ffffffff8114bee2: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff81158570)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81158570-ffffffff81158787: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff811684de-ffffffff81168502: kallsyms_symbol_complete.cold.8 (STB_LOCAL)
ffffffff81167190-ffffffff8116739b: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8117531e-ffffffff81175342: kallsyms_symbol_complete.cold.8 (STB_LOCAL)
ffffffff81173ef0-ffffffff8117417e: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8118206f-ffffffff81182093: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff81180c90-ffffffff81180ee8: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8118dedf-ffffffff8118df03: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff8118cb00-ffffffff8118cd58: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff811a29bf-ffffffff811a29e3: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff811a1810-ffffffff811a1a49: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81be4e5c-ffffffff81be4e8c: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff8119e960-ffffffff8119ebc8: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:176
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81bd6cd0-ffffffff81bd6d00: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff8119f4c0-ffffffff8119f728: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:127
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81cb3d73-ffffffff81cb3da3: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff811c92a0-ffffffff811c95d5: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:126
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81e64c23-ffffffff81e64c53: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff811fcdd0-ffffffff811fd133: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff812444f0)
Location: kernel/debug/kdb/kdb_support.c:126
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff812444f0-ffffffff8124487d: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff8125b5d0)
Location: kernel/debug/kdb/kdb_support.c:126
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8125b5d0-ffffffff8125b8c9: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffffffff81275510)
Location: kernel/debug/kdb/kdb_support.c:126
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81275510-ffffffff81275809: kallsyms_symbol_complete (STB_GLOBAL)
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
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (ffff800010203ec0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffff800010203ec0-ffff800010204078: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (c0442d48)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
c0442d48-c0442eec: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (c00000000027e760)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
c00000000027e760-c00000000027e9e4: kallsyms_symbol_complete (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff811864ff-ffffffff81186523: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff81185120-ffffffff81185378: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff8117963f-ffffffff81179663: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff81178260-ffffffff811784b8: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff811842cf-ffffffff811842f3: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff81182ef0-ffffffff81183148: kallsyms_symbol_complete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kallsyms_symbol_complete(char *prefix_name, int max_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/kdb/kdb_support.c (0)
Location: kernel/debug/kdb/kdb_support.c:186
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_io.c:kdb_read
```
**Symbols:**

```
ffffffff81191c1f-ffffffff81191c43: kallsyms_symbol_complete.cold (STB_LOCAL)
ffffffff81190830-ffffffff81190a88: kallsyms_symbol_complete (STB_GLOBAL)
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
