# Function: <code>ima_store_template</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81398640)
Location: security/integrity/ima/ima_api.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_add_violation
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff81398640-ffffffff8139878e: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813d4bf0)
Location: security/integrity/ima/ima_api.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff813d4bf0-ffffffff813d4d4b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813ec640)
Location: security/integrity/ima/ima_api.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff813ec640-ffffffff813ec79c: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff813f8a20)
Location: security/integrity/ima/ima_api.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff813f8a20-ffffffff813f8b8b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81420e50)
Location: security/integrity/ima/ima_api.c:88
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81420e50-ffffffff81420fbb: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:89
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81453b57-ffffffff81453b63: ima_store_template.cold.3 (STB_LOCAL)
ffffffff814533c0-ffffffff8145351f: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:89
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff81470d27-ffffffff81470d33: ima_store_template.cold.3 (STB_LOCAL)
ffffffff814705a0-ffffffff814706ff: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff8149e70c-ffffffff8149e718: ima_store_template.cold (STB_LOCAL)
ffffffff8149df60-ffffffff8149e0bb: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff814b8bbc-ffffffff814b8bc8: ima_store_template.cold (STB_LOCAL)
ffffffff814b83f0-ffffffff814b854b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8151816a)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff81518050-ffffffff815180ed: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8153513a)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff81535020-ffffffff815350bd: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8153d75a)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff8153d640-ffffffff8153d6dd: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8159c5da)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff8159c4c0-ffffffff8159c55d: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff81641619)
Location: security/integrity/ima/ima_api.c:103
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff816414e0-ffffffff8164158e: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff816f9609)
Location: security/integrity/ima/ima_api.c:103
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff816f94c0-ffffffff816f956e: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8173377c)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff81733630-ffffffff817336de: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffff8177419c)
Location: security/integrity/ima/ima_api.c:102
Inline: True
Inline callers:
  - security/integrity/ima/ima_api.c:ima_add_violation
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
```
**Symbols:**

```
ffffffff81774050-ffffffff817740fe: ima_store_template (STB_GLOBAL)
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
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffff8000105b06a8)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffff8000105b06a8-ffff8000105b07c4: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c075fd90)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
c075fd90-c075fe98: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (c000000000730350)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
c000000000730350-c0000000007304c0: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_api.c (ffffffe0003f82ee)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffe0003f82ee-ffffffe0003f83b0: ima_store_template (STB_GLOBAL)
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
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff814b119c-ffffffff814b11a8: ima_store_template.cold (STB_LOCAL)
ffffffff814b09d0-ffffffff814b0b2b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff814a1bbc-ffffffff814a1bc8: ima_store_template.cold (STB_LOCAL)
ffffffff814a13f0-ffffffff814a154b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff814ad22c-ffffffff814ad238: ima_store_template.cold (STB_LOCAL)
ffffffff814aca60-ffffffff814acbbb: ima_store_template (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_store_template(struct ima_template_entry *entry, int violation, struct inode *inode, const unsigned char *filename, int pcr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_api.c (0)
Location: security/integrity/ima/ima_api.c:91
Inline: False
Direct callers:
  - security/integrity/ima/ima_init.c:ima_add_boot_aggregate
  - security/integrity/ima/ima_main.c:process_buffer_measurement
  - security/integrity/ima/ima_api.c:ima_store_measurement
  - security/integrity/ima/ima_api.c:ima_add_violation
```
**Symbols:**

```
ffffffff814c5c7c-ffffffff814c5c88: ima_store_template.cold (STB_LOCAL)
ffffffff814c54b0-ffffffff814c560b: ima_store_template (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int pcr</code>
</li>
</ul>
</details>
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
