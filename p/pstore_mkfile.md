# Function: <code>pstore_mkfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pstore_mkfile(enum pstore_type_id type, char *psname, u64 id, int count, char *data, bool compressed, size_t size, struct timespec time, struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8131fd90)
Location: fs/pstore/inode.c:301
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
```
**Symbols:**

```
ffffffff8131fd90-ffffffff813201fa: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pstore_mkfile(enum pstore_type_id type, char *psname, u64 id, int count, char *data, bool compressed, size_t size, struct timespec time, struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81355260)
Location: fs/pstore/inode.c:300
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
```
**Symbols:**

```
ffffffff81355260-ffffffff813556cc: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pstore_mkfile(enum pstore_type_id type, char *psname, u64 id, int count, char *data, bool compressed, size_t size, struct timespec time, struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8136b520)
Location: fs/pstore/inode.c:305
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
  - fs/pstore/platform.c:pstore_get_records
```
**Symbols:**

```
ffffffff8136b520-ffffffff8136b98c: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8137fb30)
Location: fs/pstore/inode.c:324
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff8137fb30-ffffffff8137fec5: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813a4b40)
Location: fs/pstore/inode.c:302
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff813a4b40-ffffffff813a4ed5: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813d3ee0)
Location: fs/pstore/inode.c:302
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff813d3ee0-ffffffff813d4276: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff813ee570)
Location: fs/pstore/inode.c:302
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff813ee570-ffffffff813ee7c5: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff8141ab8f-ffffffff8141aba2: pstore_mkfile.cold (STB_LOCAL)
ffffffff8141a820-ffffffff8141aa63: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81434690)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81434690-ffffffff814348da: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81484460)
Location: fs/pstore/inode.c:345
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81484460-ffffffff814846ae: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff814a1ab0)
Location: fs/pstore/inode.c:345
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a1ab0-ffffffff814a1cfe: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff814a7be0)
Location: fs/pstore/inode.c:345
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff814a7be0-ffffffff814a7e2e: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:345
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81cd25fb-ffffffff81cd2610: pstore_mkfile.cold (STB_LOCAL)
ffffffff814ffed0-ffffffff8150012c: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:345
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81e8574d-ffffffff81e85762: pstore_mkfile.cold (STB_LOCAL)
ffffffff81591050-ffffffff815912e4: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:346
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff82072af2-ffffffff82072b07: pstore_mkfile.cold (STB_LOCAL)
ffffffff81638630-ffffffff816388d1: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:346
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff820f2756-ffffffff820f276b: pstore_mkfile.cold (STB_LOCAL)
ffffffff81670a30-ffffffff81670cd1: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/inode.c (0)
Location: fs/pstore/inode.c:340
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff821cf9ec-ffffffff821cfa01: pstore_mkfile.cold (STB_LOCAL)
ffffffff816ac920-ffffffff816acc20: pstore_mkfile (STB_GLOBAL)
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
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffff80001051a400)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffff80001051a400-ffff80001051a6f0: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (c06d492c)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
c06d492c-c06d4b88: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (c000000000663d80)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
c000000000663d80-c00000000066403c: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffe000383580)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffe000383580-ffffffe000383772: pstore_mkfile (STB_GLOBAL)
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
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8142cc70)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff8142cc70-ffffffff8142ceba: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8141d6f0)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff8141d6f0-ffffffff8141d93a: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff81428e10)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff81428e10-ffffffff8142905a: pstore_mkfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pstore_mkfile(struct dentry *root, struct pstore_record *record);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/inode.c (ffffffff8143fcd0)
Location: fs/pstore/inode.c:290
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
**Symbols:**

```
ffffffff8143fcd0-ffffffff8143ff1a: pstore_mkfile (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *root</code>
</li>
<li>
<b>Param added. </b>
<code>struct pstore_record *record</code>
</li>
<li>
<b>Param removed. </b>
<code>enum pstore_type_id type</code>
</li>
<li>
<b>Param removed. </b>
<code>char *psname</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 id</code>
</li>
<li>
<b>Param removed. </b>
<code>int count</code>
</li>
<li>
<b>Param removed. </b>
<code>char *data</code>
</li>
<li>
<b>Param removed. </b>
<code>bool compressed</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec time</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pstore_info *psi</code>
</li>
</ul>
</details>
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
