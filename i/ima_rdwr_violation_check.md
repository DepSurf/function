# Function: <code>ima_rdwr_violation_check</code>

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
In security/integrity/ima/ima_main.c (ffffffff81397543)
Location: security/integrity/ima/ima_main.c:80
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff813d3619)
Location: security/integrity/ima/ima_main.c:79
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ima_rdwr_violation_check(struct file *file, struct integrity_iint_cache *iint, int must_measure, char **pathbuf, const char **pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813eabc0)
Location: security/integrity/ima/ima_main.c:79
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813eabc0-ffffffff813eace3: ima_rdwr_violation_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ima_rdwr_violation_check(struct file *file, struct integrity_iint_cache *iint, int must_measure, char **pathbuf, const char **pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff813f6ef0)
Location: security/integrity/ima/ima_main.c:79
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff813f6ef0-ffffffff813f7014: ima_rdwr_violation_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ima_rdwr_violation_check(struct file *file, struct integrity_iint_cache *iint, int must_measure, char **pathbuf, const char **pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8141f010)
Location: security/integrity/ima/ima_main.c:83
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
**Symbols:**

```
ffffffff8141f010-ffffffff8141f134: ima_rdwr_violation_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814515f3)
Location: security/integrity/ima/ima_main.c:83
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff8146e44c)
Location: security/integrity/ima/ima_main.c:85
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff8149bd1a)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff814b5df3)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff81515505)
Location: security/integrity/ima/ima_main.c:104
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff815325ed)
Location: security/integrity/ima/ima_main.c:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff8153aa24)
Location: security/integrity/ima/ima_main.c:110
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff815993d6)
Location: security/integrity/ima/ima_main.c:115
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8163e314)
Location: security/integrity/ima/ima_main.c:115
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff816f5f40)
Location: security/integrity/ima/ima_main.c:115
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8172fdf6)
Location: security/integrity/ima/ima_main.c:115
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff81770784)
Location: security/integrity/ima/ima_main.c:116
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffff8000105ae3c8)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c075d8f0)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (c00000000072d1ec)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffe0003f6636)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff814ae3d3)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (ffffffff8149edf3)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff814aa473)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
In security/integrity/ima/ima_main.c (ffffffff814c2eb3)
Location: security/integrity/ima/ima_main.c:106
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
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
</ul>
