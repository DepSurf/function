# Function: <code>pstore_record_init</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81380670)
Location: fs/pstore/platform.c:477
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81380670-ffffffff813806c7: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813a5680)
Location: fs/pstore/platform.c:477
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff813a5680-ffffffff813a56d3: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813d47e0)
Location: fs/pstore/platform.c:323
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff813d47e0-ffffffff813d482f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813eee00)
Location: fs/pstore/platform.c:383
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff813eee00-ffffffff813eee4f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8141b0c0)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8141b0c0-ffffffff8141b10f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81434f10)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81434f10-ffffffff81434f5f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81484f70)
Location: fs/pstore/platform.c:370
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814850b0-ffffffff81485102: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff814a26f0)
Location: fs/pstore/platform.c:370
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a2850-ffffffff814a28a2: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff814a8812)
Location: fs/pstore/platform.c:370
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a89a0-ffffffff814a89f2: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81500b42)
Location: fs/pstore/platform.c:370
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81500cd0-ffffffff81500d22: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81591d19)
Location: fs/pstore/platform.c:371
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81591fd0-ffffffff81592030: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8163958a)
Location: fs/pstore/platform.c:373
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_dump
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81639870-ffffffff816398d0: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816718e0)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff816718e0-ffffffff81671940: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816ad7b0)
Location: fs/pstore/platform.c:262
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff816ad7b0-ffffffff816ad810: pstore_record_init (STB_GLOBAL)
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
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffff80001051af58)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffff80001051af58-ffff80001051afa4: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c06d5380)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
c06d5380-c06d540c: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c000000000664e90)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
c000000000664e90-c000000000664f04: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffe000383fa2)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffe000383fa2-ffffffe000383ff2: pstore_record_init (STB_GLOBAL)
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
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8142d4f0)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8142d4f0-ffffffff8142d53f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8141df70)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff8141df70-ffffffff8141dfbf: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81429690)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81429690-ffffffff814296df: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pstore_record_init(struct pstore_record *record, struct pstore_info *psinfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81440550)
Location: fs/pstore/platform.c:373
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
  - fs/pstore/platform.c:pstore_dump
```
**Symbols:**

```
ffffffff81440550-ffffffff8144059f: pstore_record_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
