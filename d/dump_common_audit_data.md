# Function: <code>dump_common_audit_data</code>

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
In security/lsm_audit.c (ffffffff81366475)
Location: security/lsm_audit.c:211
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
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
In security/lsm_audit.c (ffffffff8139c555)
Location: security/lsm_audit.c:211
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
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
In security/lsm_audit.c (ffffffff813b3105)
Location: security/lsm_audit.c:211
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
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
In security/lsm_audit.c (ffffffff813c9acf)
Location: security/lsm_audit.c:211
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff813eff61)
Location: security/lsm_audit.c:211
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81420af0)
Location: security/lsm_audit.c:211
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81420af0-ffffffff8142125f: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8143d140)
Location: security/lsm_audit.c:211
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8143d140-ffffffff8143d8fd: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8146ad30)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8146ad30-ffffffff8146b4bc: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81484b10)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81484b10-ffffffff8148529c: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814dac60)
Location: security/lsm_audit.c:209
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff814dac60-ffffffff814db435: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814f80e0)
Location: security/lsm_audit.c:209
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff814f80e0-ffffffff814f88c9: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff814fee20)
Location: security/lsm_audit.c:209
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff814fee20-ffffffff814ff637: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81559e70)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81559e70-ffffffff8155a6a8: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff815f4b40)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff815f4b40-ffffffff815f53f8: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff816a5610)
Location: security/lsm_audit.c:197
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff816a5610-ffffffff816a5ec8: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff816ddff0)
Location: security/lsm_audit.c:197
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff816ddff0-ffffffff816de8ae: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8171abb0)
Location: security/lsm_audit.c:197
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8171abb0-ffffffff8171b472: dump_common_audit_data (STB_LOCAL)
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
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffff800010576fd8)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffff800010576fd8-ffff80001057774c: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (c0729d78)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
c0729d78-c072a590: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (c0000000006e0480)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
c0000000006e0480-c0000000006e0dd8: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffe0003c9530)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffe0003c9530-ffffffe0003c9ca0: dump_common_audit_data (STB_LOCAL)
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
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8147d0f0)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8147d0f0-ffffffff8147d87c: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff8146db10)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8146db10-ffffffff8146e29c: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81479190)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81479190-ffffffff8147991c: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer *ab, struct common_audit_data *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/lsm_audit.c (ffffffff81490c40)
Location: security/lsm_audit.c:208
Inline: False
Direct callers:
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81490c40-ffffffff814913cc: dump_common_audit_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
