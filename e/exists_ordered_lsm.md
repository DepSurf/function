# Function: <code>exists_ordered_lsm</code>

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
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828cd272)
Location: security/security.c:109
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828cd272-ffffffff828cd29d: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828e6cb1)
Location: security/security.c:105
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828e6cb1-ffffffff828e6cdc: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828ef79c)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828ef79c-ffffffff828ef7c7: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d049a8)
Location: security/security.c:138
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff82d049a8-ffffffff82d049d3: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82ff1d75)
Location: security/security.c:140
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff82ff1d75-ffffffff82ff1da0: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff831fc6ff)
Location: security/security.c:141
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff831fc6ff-ffffffff831fc72a: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff832e3751)
Location: security/security.c:141
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff832e3751-ffffffff832e377c: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83499b82)
Location: security/security.c:145
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff83499b82-ffffffff83499bb5: exists_ordered_lsm (STB_LOCAL)
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
In security/security.c (ffffffff83ed02a7)
Location: security/security.c:149
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
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
In security/security.c (ffffffff836f5360)
Location: security/security.c:150
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
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
In security/security.c (ffffffff839286b0)
Location: security/security.c:156
Inline: True
Inline callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
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
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800011469458)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffff800011469458-ffff80001146949c: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c1542018)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
c1542018-c154205c: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000001397600)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
c000000001397600-c000000001397640: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0000246bc)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffe0000246bc-ffffffe0000246f4: exists_ordered_lsm (STB_LOCAL)
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
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d8650)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828d8650-ffffffff828d867b: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d0d6c)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828d0d6c-ffffffff828d0d97: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828eb3d0)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828eb3d0-ffffffff828eb3fb: exists_ordered_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool exists_ordered_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828f07e6)
Location: security/security.c:106
Inline: False
Direct callers:
  - security/security.c:ordered_lsm_parse
  - security/security.c:ordered_lsm_parse
  - security/security.c:append_ordered_lsm
```
**Symbols:**

```
ffffffff828f07e6-ffffffff828f0811: exists_ordered_lsm (STB_LOCAL)
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
