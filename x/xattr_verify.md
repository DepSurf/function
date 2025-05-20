# Function: <code>xattr_verify</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff814bbe0a)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8151bbe0)
Location: security/integrity/ima/ima_appraise.c:216
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff8151bbe0-ffffffff8151bd6d: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81538a50)
Location: security/integrity/ima/ima_appraise.c:232
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff81538a50-ffffffff81538bdd: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81541170)
Location: security/integrity/ima/ima_appraise.c:234
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff81541170-ffffffff815412f6: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff815a0ef0)
Location: security/integrity/ima/ima_appraise.c:235
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff815a0ef0-ffffffff815a1079: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81647010)
Location: security/integrity/ima/ima_appraise.c:277
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff81647010-ffffffff8164730b: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff816ff7d0)
Location: security/integrity/ima/ima_appraise.c:277
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff816ff7d0-ffffffff816ffacb: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff81739840)
Location: security/integrity/ima/ima_appraise.c:280
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff81739840-ffffffff81739b3e: xattr_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xattr_verify(enum ima_hooks func, struct integrity_iint_cache *iint, struct evm_ima_xattr_data *xattr_value, int xattr_len, enum integrity_status *status, const char **cause);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_appraise.c (ffffffff8177a360)
Location: security/integrity/ima/ima_appraise.c:279
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
```
**Symbols:**

```
ffffffff8177a360-ffffffff8177a65e: xattr_verify (STB_LOCAL)
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
In security/integrity/ima/ima_appraise.c (ffff8000105b47bc)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (c07638a0)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (c000000000736f48)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (ffffffe0003fb7c4)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (ffffffff814b43ea)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (ffffffff814a4e0a)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (ffffffff814b047a)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
In security/integrity/ima/ima_appraise.c (ffffffff814c8efa)
Location: security/integrity/ima/ima_appraise.c:210
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_appraise_measurement
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
