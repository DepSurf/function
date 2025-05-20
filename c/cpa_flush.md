# Function: <code>cpa_flush</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107ee80)
Location: arch/x86/mm/pageattr.c:342
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff8107ee80-ffffffff8107efb1: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082750)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff81082750-ffffffff81082879: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083810)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff81083810-ffffffff8108394a: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d2e0)
Location: arch/x86/mm/pat/set_memory.c:352
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
**Symbols:**

```
ffffffff8108d2e0-ffffffff8108d448: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108d1b0)
Location: arch/x86/mm/pat/set_memory.c:352
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
**Symbols:**

```
ffffffff8108d1b0-ffffffff8108d318: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dd60)
Location: arch/x86/mm/pat/set_memory.c:360
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
**Symbols:**

```
ffffffff8108dd60-ffffffff8108ded1: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:360
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_dec
```
**Symbols:**

```
ffffffff8109d650-ffffffff8109d7ec: cpa_flush (STB_LOCAL)
ffffffff81ca12bd-ffffffff81ca12ee: cpa_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:363
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
```
**Symbols:**

```
ffffffff810b0ee0-ffffffff810b10be: cpa_flush (STB_LOCAL)
ffffffff81e508a8-ffffffff81e508d9: cpa_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:398
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
```
**Symbols:**

```
ffffffff810cb610-ffffffff810cb7dd: cpa_flush (STB_LOCAL)
ffffffff82054d26-ffffffff82054d57: cpa_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:399
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
```
**Symbols:**

```
ffffffff810cec30-ffffffff810cedfd: cpa_flush (STB_LOCAL)
ffffffff820d32fc-ffffffff820d332d: cpa_flush.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/mm/pat/set_memory.c:399
Inline: False
Direct callers:
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
  - arch/x86/mm/pat/set_memory.c:__set_memory_enc_pgtable
```
**Symbols:**

```
ffffffff810d7310-ffffffff810d74dd: cpa_flush (STB_LOCAL)
ffffffff821ae16a-ffffffff821ae19b: cpa_flush.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81082810)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff81082810-ffffffff8108294a: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071590)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff81071590-ffffffff810716bc: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810827c0)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810827c0-ffffffff810828fa: cpa_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpa_flush(struct cpa_data *data, int cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810848e0)
Location: arch/x86/mm/pageattr.c:343
Inline: False
Direct callers:
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:__set_memory_enc_dec
  - arch/x86/mm/pageattr.c:change_page_attr_set_clr
```
**Symbols:**

```
ffffffff810848e0-ffffffff81084a1a: cpa_flush (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
