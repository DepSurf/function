# Function: <code>start_generic_opal_session</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff8145df50)
Location: block/sed-opal.c:1228
Inline: False
Direct callers:
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8145df50-ffffffff8145e31c: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81489d30)
Location: block/sed-opal.c:1240
Inline: False
Direct callers:
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff81489d30-ffffffff8148a0fc: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814bea40)
Location: block/sed-opal.c:1257
Inline: False
Direct callers:
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff814bea40-ffffffff814bee01: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff814d2fb0)
Location: block/sed-opal.c:1257
Inline: False
Direct callers:
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff814d2fb0-ffffffff814d3371: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff814ffe55)
Location: block/sed-opal.c:1322
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff814ffc30-ffffffff814ffdf2: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8151dda5)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8151db80-ffffffff8151dd42: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8157fe15)
Location: block/sed-opal.c:1398
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8157fb70-ffffffff8157fd2c: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8159ce55)
Location: block/sed-opal.c:1398
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8159cbb0-ffffffff8159cd6c: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff815a3975)
Location: block/sed-opal.c:1398
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff815a36d0-ffffffff815a388f: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8160c385)
Location: block/sed-opal.c:1398
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8160c090-ffffffff8160c298: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff816c0070)
Location: block/sed-opal.c:1398
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff816c0070-ffffffff816c02a2: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817812d0)
Location: block/sed-opal.c:1438
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff817812d0-ffffffff81781502: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff817c11d0)
Location: block/sed-opal.c:1575
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff817c11d0-ffffffff817c140c: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffff81805350)
Location: block/sed-opal.c:1692
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff81805350-ffffffff8180558c: start_generic_opal_session (STB_LOCAL)
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
In block/sed-opal.c (ffff800010626a9c)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffff800010626810-ffff8000106269f8: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (c07ce424)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
c07ce1ac-c07ce398: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (c0000000007c7500)
Location: block/sed-opal.c:1327
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
c0000000007c7500-c0000000007c77d8: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int start_generic_opal_session(struct opal_dev *dev, enum opal_uid auth, enum opal_uid sp_type, const char *key, u8 key_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/sed-opal.c (ffffffe000457960)
Location: block/sed-opal.c:1327
Inline: False
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffe000457960-ffffffe000457b88: start_generic_opal_session (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81516385)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff81516160-ffffffff81516322: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81506695)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff81506470-ffffffff81506632: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff81512415)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff815121f0-ffffffff815123b2: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/sed-opal.c (ffffffff8152bbd5)
Location: block/sed-opal.c:1327
Inline: True
Inline callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
Direct callers:
  - block/sed-opal.c:start_PSID_opal_session
  - block/sed-opal.c:start_admin1LSP_opal_session
  - block/sed-opal.c:start_anybodyASP_opal_session
```
**Symbols:**

```
ffffffff8152b9b0-ffffffff8152bb72: start_generic_opal_session.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
