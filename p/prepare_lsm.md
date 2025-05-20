# Function: <code>prepare_lsm</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828cd694)
Location: security/security.c:188
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
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
In security/security.c (ffffffff828e70c6)
Location: security/security.c:184
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828efaf1)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828efaf1-ffffffff828efc20: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d04d65)
Location: security/security.c:217
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff82d04d65-ffffffff82d04e90: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82ff2132)
Location: security/security.c:219
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff82ff2132-ffffffff82ff225d: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff831fcabc)
Location: security/security.c:221
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff831fcabc-ffffffff831fcbf7: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff832e3b97)
Location: security/security.c:221
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff832e3b97-ffffffff832e3d03: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8349a020)
Location: security/security.c:225
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff8349a020-ffffffff8349a1a6: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83ed0470)
Location: security/security.c:230
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff83ed0470-ffffffff83ed05fc: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff836f5560)
Location: security/security.c:231
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff836f5560-ffffffff836f56ec: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff839288b0)
Location: security/security.c:255
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff839288b0-ffffffff83928a3c: prepare_lsm (STB_LOCAL)
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
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800011469950)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffff800011469950-ffff800011469a94: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c15424a8)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
c15424a8-c1542610: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000001397b84)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
c000000001397b84-c000000001397d28: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe000024ae2)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffe000024ae2-ffffffe000024c24: prepare_lsm (STB_LOCAL)
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
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d89a5)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828d89a5-ffffffff828d8ad4: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d10c1)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828d10c1-ffffffff828d11f0: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828eb725)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828eb725-ffffffff828eb854: prepare_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void prepare_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828f0b3b)
Location: security/security.c:185
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828f0b3b-ffffffff828f0c6a: prepare_lsm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
