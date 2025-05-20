# Function: <code>security_cred_getsecid</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f2d70)
Location: security/security.c:1026
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff813f2d70-ffffffff813f2db4: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8140e210)
Location: security/security.c:1618
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff8140e210-ffffffff8140e254: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143adc0)
Location: security/security.c:1637
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff8143adc0-ffffffff8143ae06: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81454bb0)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff81454bb0-ffffffff81454bf4: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814a8550)
Location: security/security.c:1844
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff814a8550-ffffffff814a85bd: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c5ae0)
Location: security/security.c:1846
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff814c5ae0-ffffffff814c5b4e: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cbd50)
Location: security/security.c:1896
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff814cbd50-ffffffff814cbdbe: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81524cd0)
Location: security/security.c:1904
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff81524cd0-ffffffff81524d3e: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815b8c60)
Location: security/security.c:1909
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff815b8c60-ffffffff815b8cd8: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81664310)
Location: security/security.c:1956
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff81664310-ffffffff81664388: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, struct lsmblob *blob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169c750)
Location: security/security.c:3114
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff8169c750-ffffffff8169c7f4: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816d7e30)
Location: security/security.c:3181
Inline: False
```
**Symbols:**

```
ffffffff816d7e30-ffffffff816d7e6b: security_cred_getsecid (STB_GLOBAL)
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
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff80001053fde0)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffff80001053fde0-ffff80001053fe38: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06f5ea0)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
c06f5ea0-c06f5ef8: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000691220)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
c000000000691220-c0000000006912b0: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe00039d0ee)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffe00039d0ee-ffffffe00039d132: security_cred_getsecid (STB_GLOBAL)
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
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144d190)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff8144d190-ffffffff8144d1d4: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143dbe0)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff8143dbe0-ffffffff8143dc24: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81449230)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff81449230-ffffffff81449274: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_cred_getsecid(const struct cred *c, u32 *secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81460600)
Location: security/security.c:1676
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_bprm_check
```
**Symbols:**

```
ffffffff81460600-ffffffff81460644: security_cred_getsecid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmblob *blob</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *secid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *secid</code>
</li>
<li>
<b>Param removed. </b>
<code>struct lsmblob *blob</code>
</li>
</ul>
</details>
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
