# Function: <code>cont_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7040)
Location: kernel/printk/printk.c:1597
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810d7040-ffffffff810d716a: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dbf90)
Location: kernel/printk/printk.c:1674
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810dbf90-ffffffff810dc0c0: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2f00)
Location: kernel/printk/printk.c:1603
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e2f00-ffffffff810e2ff3: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2000)
Location: kernel/printk/printk.c:1630
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810e2000-ffffffff810e20f3: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea0e0)
Location: kernel/printk/printk.c:1618
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:vprintk_emit
```
**Symbols:**

```
ffffffff810ea0e0-ffffffff810ea1d3: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f23b0)
Location: kernel/printk/printk.c:1762
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff810f23b0-ffffffff810f24c0: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool cont_add(int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fd800)
Location: kernel/printk/printk.c:1781
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff810fd800-ffffffff810fd8c6: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81106250)
Location: kernel/printk/printk.c:1831
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81106250-ffffffff8110630b: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811125e0)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff811125e0-ffffffff8111269b: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111de00)
Location: kernel/printk/printk.c:1866
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8111de00-ffffffff8111debe: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172758)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffff800010172758-ffff80001017285c: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c5490)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
c03c5490-c03c5548: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cbff0)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
c0000000001cbff0-c0000000001cc14c: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010eb34)
Location: kernel/printk/printk.c:1841
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffe00010eb34-ffffffe00010ec00: cont_add (STB_LOCAL)
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
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110abc0)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff8110abc0-ffffffff8110ac7b: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fbb70)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff810fbb70-ffffffff810fbc2b: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81108ab0)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81108ab0-ffffffff81108b6b: cont_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cont_add(u32 caller_id, int facility, int level, enum log_flags flags, const char *text, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81113e50)
Location: kernel/printk/printk.c:1841
Inline: False
Direct callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:vprintk_store
```
**Symbols:**

```
ffffffff81113e50-ffffffff81113f0b: cont_add (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum log_flags flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>facility, level, text, len</code> ➡️ <code>facility, level, flags, text, len</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 caller_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>facility, level, flags, text, len</code> ➡️ <code>caller_id, facility, level, flags, text, len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
