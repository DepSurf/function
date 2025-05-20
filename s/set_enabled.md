# Function: <code>set_enabled</code>

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
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828cd223)
Location: security/security.c:86
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
```
**Symbols:**

```
ffffffff828cd223-ffffffff828cd272: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828e6c62)
Location: security/security.c:82
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_init
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
```
**Symbols:**

```
ffffffff828e6c62-ffffffff828e6cb1: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828ef74d)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff828ef74d-ffffffff828ef79c: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d04959)
Location: security/security.c:115
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff82d04959-ffffffff82d049a8: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82ff1d26)
Location: security/security.c:117
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff82ff1d26-ffffffff82ff1d75: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff831fc6b0)
Location: security/security.c:118
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff831fc6b0-ffffffff831fc6ff: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff832e3702)
Location: security/security.c:118
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff832e3702-ffffffff832e3751: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83499b29)
Location: security/security.c:122
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
  - security/security.c:prepare_lsm
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff83499b29-ffffffff83499b82: set_enabled (STB_LOCAL)
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
In security/security.c (ffffffff83ed0174)
Location: security/security.c:126
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff836f5234)
Location: security/security.c:127
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
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
In security/security.c (ffffffff83928584)
Location: security/security.c:133
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffff800011469664)
Location: security/security.c:83
Inline: True
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffff800011469664-ffff8000114696e0: set_enabled.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c1541f98)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
c1541f98-c1542018: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (c0000000013977fc)
Location: security/security.c:83
Inline: True
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
c0000000013977fc-c000000001397874: set_enabled.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffe00002486a)
Location: security/security.c:83
Inline: True
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffe00002486a-ffffffe0000248d4: set_enabled.isra.0 (STB_LOCAL)
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
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d8601)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff828d8601-ffffffff828d8650: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d0d1d)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff828d0d1d-ffffffff828d0d6c: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828eb381)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff828eb381-ffffffff828eb3d0: set_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_enabled(struct lsm_info *lsm, bool enabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828f0797)
Location: security/security.c:83
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:prepare_lsm
```
**Symbols:**

```
ffffffff828f0797-ffffffff828f07e6: set_enabled (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
