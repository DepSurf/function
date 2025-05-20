# Function: <code>ima_add_digest_entry</code>

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
In security/integrity/ima/ima_queue.c (ffffffff81397194)
Location: security/integrity/ima/ima_queue.c:71
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
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
In security/integrity/ima/ima_queue.c (ffffffff813d31ea)
Location: security/integrity/ima/ima_queue.c:72
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813ea820)
Location: security/integrity/ima/ima_queue.c:96
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff813ea820-ffffffff813ea944: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff813f6b70)
Location: security/integrity/ima/ima_queue.c:96
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff813f6b70-ffffffff813f6c86: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8141ec90)
Location: security/integrity/ima/ima_queue.c:96
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8141ec90-ffffffff8141eda6: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:96
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81450f30-ffffffff81451029: ima_add_digest_entry (STB_LOCAL)
ffffffff81451246-ffffffff8145125d: ima_add_digest_entry.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:95
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8146df10-ffffffff8146e009: ima_add_digest_entry (STB_LOCAL)
ffffffff8146e236-ffffffff8146e24d: ima_add_digest_entry.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8149b5e0-ffffffff8149b6d9: ima_add_digest_entry (STB_LOCAL)
ffffffff8149b96a-ffffffff8149b981: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff814b5820-ffffffff814b5919: ima_add_digest_entry (STB_LOCAL)
ffffffff814b5bba-ffffffff814b5bd1: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81514ec0-ffffffff81514fc5: ima_add_digest_entry (STB_LOCAL)
ffffffff815151ad-ffffffff815151c4: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81531f30-ffffffff81532035: ima_add_digest_entry (STB_LOCAL)
ffffffff81bf1b56-ffffffff81bf1b6d: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8153a300-ffffffff8153a405: ima_add_digest_entry (STB_LOCAL)
ffffffff81be3b74-ffffffff81be3b8b: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff81598c80-ffffffff81598d87: ima_add_digest_entry (STB_LOCAL)
ffffffff81cd6d4c-ffffffff81cd6d63: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8163d6a0-ffffffff8163d7b9: ima_add_digest_entry (STB_LOCAL)
ffffffff81e89f7f-ffffffff81e89f95: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff816f51d0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff816f51d0-ffffffff816f52fc: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8172f2d0)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8172f2d0-ffffffff8172f3fd: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffff8176fc30)
Location: security/integrity/ima/ima_queue.c:93
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8176fc30-ffffffff8176fd8e: ima_add_digest_entry (STB_LOCAL)
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
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffff8000105adc90)
Location: security/integrity/ima/ima_queue.c:94
Inline: True
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffff8000105adc90-ffff8000105addbc: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (c075d378)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
c075d378-c075d498: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (c00000000072c800)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
c00000000072c800-c00000000072c990: ima_add_digest_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_queue.c (ffffffe0003f600e)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffe0003f600e-ffffffe0003f6108: ima_add_digest_entry (STB_LOCAL)
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
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff814ade00-ffffffff814adef9: ima_add_digest_entry (STB_LOCAL)
ffffffff814ae19a-ffffffff814ae1b1: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff8149e820-ffffffff8149e919: ima_add_digest_entry (STB_LOCAL)
ffffffff8149ebba-ffffffff8149ebd1: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff814a9ea0-ffffffff814a9f99: ima_add_digest_entry (STB_LOCAL)
ffffffff814aa23a-ffffffff814aa251: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_add_digest_entry(struct ima_template_entry *entry, bool update_htable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_queue.c (0)
Location: security/integrity/ima/ima_queue.c:94
Inline: False
Direct callers:
  - security/integrity/ima/ima_queue.c:ima_restore_measurement_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
**Symbols:**

```
ffffffff814c28f0-ffffffff814c29e9: ima_add_digest_entry (STB_LOCAL)
ffffffff814c2c7a-ffffffff814c2c91: ima_add_digest_entry.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
