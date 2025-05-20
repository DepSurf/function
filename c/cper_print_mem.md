# Function: <code>cper_print_mem</code>

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
In drivers/firmware/efi/cper.c (ffffffff816d4079)
Location: drivers/firmware/efi/cper.c:308
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/firmware/efi/cper.c (ffffffff81737a39)
Location: drivers/firmware/efi/cper.c:308
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/firmware/efi/cper.c (ffffffff8176abd9)
Location: drivers/firmware/efi/cper.c:308
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
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
In drivers/firmware/efi/cper.c (ffffffff817890c7)
Location: drivers/firmware/efi/cper.c:431
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff817ffaf9)
Location: drivers/firmware/efi/cper.c:431
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff817ffaf9-ffffffff817ffc92: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81848a4a)
Location: drivers/firmware/efi/cper.c:313
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81848a4a-ffffffff81848ba6: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81874cba)
Location: drivers/firmware/efi/cper.c:326
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81874cba-ffffffff81874e16: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818b8eed)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818b8eed-ffffffff818b9049: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818eb8ed)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818eb8ed-ffffffff818eba49: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff819bf749)
Location: drivers/firmware/efi/cper.c:314
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81c2c4e1)
Location: drivers/firmware/efi/cper.c:328
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81c1e75e)
Location: drivers/firmware/efi/cper.c:326
Inline: True
Inline callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d2fa64)
Location: drivers/firmware/efi/cper.c:324
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81d2fa64-ffffffff81d2fbc9: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81efbd4d)
Location: drivers/firmware/efi/cper.c:350
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81efbd4d-ffffffff81efbee9: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81d64dd0)
Location: drivers/firmware/efi/cper.c:354
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81d64dd0-ffffffff81d65025: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81dcff00)
Location: drivers/firmware/efi/cper.c:354
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81dcff00-ffffffff81dd0155: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81e88c30)
Location: drivers/firmware/efi/cper.c:354
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81e88c30-ffffffff81e88e85: cper_print_mem (STB_LOCAL)
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
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffff800010b5ec1c)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffff800010b5ec1c-ffff800010b5edb4: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff81845fed)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81845fed-ffffffff81846149: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818e074d)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818e074d-ffffffff818e08a9: cper_print_mem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cper_print_mem(const char *pfx, const struct cper_sec_mem_err *mem, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper.c (ffffffff818fd1ed)
Location: drivers/firmware/efi/cper.c:314
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff818fd1ed-ffffffff818fd349: cper_print_mem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
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
