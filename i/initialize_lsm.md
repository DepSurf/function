# Function: <code>initialize_lsm</code>

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
In security/security.c (ffffffff828cd971)
Location: security/security.c:207
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
In security/security.c (ffffffff828e73a2)
Location: security/security.c:203
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
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828efc20)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828efc20-ffffffff828efc74: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82d04d13)
Location: security/security.c:236
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff82d04d13-ffffffff82d04d65: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82ff20e0)
Location: security/security.c:238
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff82ff20e0-ffffffff82ff2132: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff831fca6a)
Location: security/security.c:240
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff831fca6a-ffffffff831fcabc: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff832e3b27)
Location: security/security.c:240
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff832e3b27-ffffffff832e3b97: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83499fa4)
Location: security/security.c:244
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff83499fa4-ffffffff8349a020: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff83ecfec0)
Location: security/security.c:249
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff83ecfec0-ffffffff83ecff52: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff836f4f80)
Location: security/security.c:250
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff836f4f80-ffffffff836f5012: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff839282d0)
Location: security/security.c:274
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff839282d0-ffffffff83928362: initialize_lsm (STB_LOCAL)
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
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800011469a94)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffff800011469a94-ffff800011469b08: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c1542610)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
c1542610-c15426a8: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000001397d28)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
c000000001397d28-c000000001397dd0: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe000024c24)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffe000024c24-ffffffe000024c84: initialize_lsm (STB_LOCAL)
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
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d8ad4)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828d8ad4-ffffffff828d8b28: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828d11f0)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828d11f0-ffffffff828d1244: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828eb854)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828eb854-ffffffff828eb8a8: initialize_lsm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void initialize_lsm(struct lsm_info *lsm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828f0c6a)
Location: security/security.c:204
Inline: False
Direct callers:
  - security/security.c:early_security_init
  - security/security.c:ordered_lsm_init
```
**Symbols:**

```
ffffffff828f0c6a-ffffffff828f0cbe: initialize_lsm (STB_LOCAL)
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
