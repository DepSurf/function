# Function: <code>add_bytestring_header</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814feea0)
Location: block/sed-opal.c:606
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff814feea0-ffffffff814fef8c: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8151cdf0)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff8151cdf0-ffffffff8151cedc: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8157d390)
Location: block/sed-opal.c:609
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff8157d390-ffffffff8157d48a: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8159a3d0)
Location: block/sed-opal.c:609
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff8159a3d0-ffffffff8159a4ca: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815a0ec0)
Location: block/sed-opal.c:609
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff815a0ec0-ffffffff815a0fbc: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816098a0)
Location: block/sed-opal.c:609
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff816098a0-ffffffff81609a15: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816bda30)
Location: block/sed-opal.c:609
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff816bda30-ffffffff816bdbb4: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8177e7c0)
Location: block/sed-opal.c:649
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff8177e7c0-ffffffff8177e8d2: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817bdfa0)
Location: block/sed-opal.c:657
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff817bdfa0-ffffffff817be0b2: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81802c60)
Location: block/sed-opal.c:770
Inline: False
Direct callers:
  - block/sed-opal.c:generic_table_write_data
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff81802c60-ffffffff81802d72: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffff8000106259a0)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffff8000106259a0-ffff800010625acc: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c07cd444)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
c07cd444-c07cd56c: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c6870)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
c0000000007c6870-c0000000007c69f0: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000456bfc)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffe000456bfc-ffffffe000456ce8: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815153d0)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff815153d0-ffffffff815154bc: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff815056e0)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff815056e0-ffffffff815057cc: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81511460)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff81511460-ffffffff8151154c: add_bytestring_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u8 *add_bytestring_header(int *err, struct opal_dev *cmd, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8152ac20)
Location: block/sed-opal.c:607
Inline: True
Direct callers:
  - block/sed-opal.c:write_shadow_mbr
  - block/sed-opal.c:add_token_bytestring
```
**Symbols:**

```
ffffffff8152ac20-ffffffff8152ad0c: add_bytestring_header (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
