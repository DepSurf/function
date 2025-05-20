# Function: <code>ima_add_template_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813970f0)
Location: security/integrity/ima/ima_queue.c:108
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff813970f0-ffffffff81397335: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813d3130)
Location: security/integrity/ima/ima_queue.c:109
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff813d3130-ffffffff813d338e: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813ea980)
Location: security/integrity/ima/ima_queue.c:162
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff813ea980-ffffffff813eab7d: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813f6cc0)
Location: security/integrity/ima/ima_queue.c:162
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff813f6cc0-ffffffff813f6eae: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8141ede0)
Location: security/integrity/ima/ima_queue.c:162
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff8141ede0-ffffffff8141efce: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:162
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff8145125d-ffffffff8145128e: ima_add_template_entry.cold.5 (STB_LOCAL)
ffffffff81451060-ffffffff8145120a: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:161
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff8146e24d-ffffffff8146e27d: ima_add_template_entry.cold.5 (STB_LOCAL)
ffffffff8146e040-ffffffff8146e1f3: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff8149b981-ffffffff8149b9b2: ima_add_template_entry.cold (STB_LOCAL)
ffffffff8149b710-ffffffff8149b92f: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff814b5bd1-ffffffff814b5c02: ima_add_template_entry.cold (STB_LOCAL)
ffffffff814b5950-ffffffff814b5b79: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff815151c4-ffffffff815151f6: ima_add_template_entry.cold (STB_LOCAL)
ffffffff81515000-ffffffff81515158: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81bf1b6d-ffffffff81bf1b9f: ima_add_template_entry.cold (STB_LOCAL)
ffffffff81532070-ffffffff815321c8: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81be3b8b-ffffffff81be3bc1: ima_add_template_entry.cold (STB_LOCAL)
ffffffff8153a440-ffffffff8153a64c: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81cd6d63-ffffffff81cd6d99: ima_add_template_entry.cold (STB_LOCAL)
ffffffff81598dc0-ffffffff81598fe6: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81e89f95-ffffffff81e89fc9: ima_add_template_entry.cold (STB_LOCAL)
ffffffff8163d7f0-ffffffff8163da3d: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff816f5350)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff816f5350-ffffffff816f55d2: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8172f450)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff8172f450-ffffffff8172f6d7: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8176fde0)
Location: security/integrity/ima/ima_queue.c:159
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff8176fde0-ffffffff81770067: ima_add_template_entry (STB_GLOBAL)
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
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffff8000105addf0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffff8000105addf0-ffff8000105ae068: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (c075d4c8)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
c075d4c8-c075d748: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (c00000000072c9c0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
c00000000072c9c0-c00000000072cd08: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffe0003f6136)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffe0003f6136-ffffffe0003f6314: ima_add_template_entry (STB_GLOBAL)
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
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff814ae1b1-ffffffff814ae1e2: ima_add_template_entry.cold (STB_LOCAL)
ffffffff814adf30-ffffffff814ae159: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff8149ebd1-ffffffff8149ec02: ima_add_template_entry.cold (STB_LOCAL)
ffffffff8149e950-ffffffff8149eb79: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff814aa251-ffffffff814aa282: ima_add_template_entry.cold (STB_LOCAL)
ffffffff814a9fd0-ffffffff814aa1f9: ima_add_template_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_add_template_entry(struct ima_template_entry *entry, int violation, const char *op, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:164
Inline: False
Direct callers:
  - security/integrity/ima/ima_api.c:ima_store_template
```
**Symbols:**

```
ffffffff814c2c91-ffffffff814c2cc3: ima_add_template_entry.cold (STB_LOCAL)
ffffffff814c2a20-ffffffff814c2c37: ima_add_template_entry (STB_GLOBAL)
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
