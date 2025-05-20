# Function: <code>validate_constant_table</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:301
Inline: False
```
**Symbols:**

```
ffffffff8130b4ca-ffffffff8130b550: validate_constant_table.cold (STB_LOCAL)
ffffffff8130b420-ffffffff8130b4ca: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffffffff8131e4ca-ffffffff8131e550: validate_constant_table.cold (STB_LOCAL)
ffffffff8131e420-ffffffff8131e4ca: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:320
Inline: False
```
**Symbols:**

```
ffffffff813584c9-ffffffff8135854f: validate_constant_table.cold (STB_LOCAL)
ffffffff81358390-ffffffff8135843a: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:320
Inline: False
```
**Symbols:**

```
ffffffff81bea95d-ffffffff81bea9e3: validate_constant_table.cold (STB_LOCAL)
ffffffff81364db0-ffffffff81364e5a: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:319
Inline: False
```
**Symbols:**

```
ffffffff81bdc970-ffffffff81bdc9f6: validate_constant_table.cold (STB_LOCAL)
ffffffff8136b800-ffffffff8136b8aa: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:318
Inline: False
```
**Symbols:**

```
ffffffff81cc4252-ffffffff81cc42d8: validate_constant_table.cold (STB_LOCAL)
ffffffff813ba4d0-ffffffff813ba57a: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:333
Inline: False
```
**Symbols:**

```
ffffffff81e76b66-ffffffff81e76bde: validate_constant_table.cold (STB_LOCAL)
ffffffff814401b0-ffffffff81440270: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff814cefa0)
Location: fs/fs_parser.c:334
Inline: False
```
**Symbols:**

```
ffffffff814cefa0-ffffffff814cf0d1: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81505200)
Location: fs/fs_parser.c:334
Inline: False
```
**Symbols:**

```
ffffffff81505200-ffffffff81505355: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffff81539ec0)
Location: fs/fs_parser.c:334
Inline: False
```
**Symbols:**

```
ffffffff81539ec0-ffffffff8153a015: validate_constant_table (STB_GLOBAL)
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
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffff8000103d66c8)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffff8000103d66c8-ffff8000103d681c: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c05b0290)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
c05b0290-c05b0408: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (c0000000004da660)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
c0000000004da660-c0000000004da990: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_parser.c (ffffffe00029034c)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffffffe00029034c-ffffffe00029045e: validate_constant_table (STB_GLOBAL)
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
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffffffff81316aaa-ffffffff81316b30: validate_constant_table.cold (STB_LOCAL)
ffffffff81316a00-ffffffff81316aaa: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffffffff8130769a-ffffffff81307720: validate_constant_table.cold (STB_LOCAL)
ffffffff813075f0-ffffffff8130769a: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool validate_constant_table(const struct constant_table *tbl, size_t tbl_size, int low, int high, int special);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fs_parser.c (0)
Location: fs/fs_parser.c:315
Inline: False
```
**Symbols:**

```
ffffffff813260ea-ffffffff81326170: validate_constant_table.cold (STB_LOCAL)
ffffffff81326040-ffffffff813260ea: validate_constant_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
