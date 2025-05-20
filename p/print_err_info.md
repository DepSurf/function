# Function: <code>print_err_info</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff8184a86b)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
In drivers/firmware/efi/cper-x86.c (ffffffff8187774b)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
In drivers/firmware/efi/cper-x86.c (ffffffff818bbfb9)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
In drivers/firmware/efi/cper-x86.c (ffffffff818eea89)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff819c237f)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff819c237f-ffffffff819c261c: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81c2cc9b)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81c2cc9b-ffffffff81c2cf38: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81c1eec9)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81c1eec9-ffffffff81c1f166: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81d304c2)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81d304c2-ffffffff81d307b3: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81efc8ff)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81efc8ff-ffffffff81efcbf0: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81d68970)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81d68970-ffffffff81d68db6: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81dd3ba0)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81dd3ba0-ffffffff81dd3fe6: print_err_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_err_info(const char *pfx, u8 err_type, u64 check);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81e8bbb0)
Location: drivers/firmware/efi/cper-x86.c:184
Inline: False
Direct callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
```
**Symbols:**

```
ffffffff81e8bbb0-ffffffff81e8bff6: print_err_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper-x86.c (ffffffff81849119)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
In drivers/firmware/efi/cper-x86.c (ffffffff818e38b9)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
In drivers/firmware/efi/cper-x86.c (ffffffff81900529)
Location: drivers/firmware/efi/cper-x86.c:183
Inline: True
Inline callers:
  - drivers/firmware/efi/cper-x86.c:cper_print_proc_ia
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
