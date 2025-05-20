# Function: <code>tomoyo_assign_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8136dbe0)
Location: security/tomoyo/domain.c:504
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8136dbe0-ffffffff8136de81: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813a3e90)
Location: security/tomoyo/domain.c:504
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813a3e90-ffffffff813a4132: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813baa10)
Location: security/tomoyo/domain.c:504
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813baa10-ffffffff813bacb2: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813d12b0)
Location: security/tomoyo/domain.c:506
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813d12b0-ffffffff813d156a: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff813f7770)
Location: security/tomoyo/domain.c:507
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff813f7770-ffffffff813f7a2a: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81428750)
Location: security/tomoyo/domain.c:507
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81428750-ffffffff814289fd: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81445000)
Location: security/tomoyo/domain.c:507
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81445000-ffffffff814452c3: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81472c70)
Location: security/tomoyo/domain.c:520
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81472c70-ffffffff81472f4e: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff8148ca10)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff8148ca10-ffffffff8148ccee: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff814e3d00)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff814e3d00-ffffffff814e3f79: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81501130)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81501130-ffffffff815013a9: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81507bb0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81507bb0-ffffffff81507e8e: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81cd5e63-ffffffff81cd5e77: tomoyo_assign_domain.cold (STB_LOCAL)
ffffffff81564db0-ffffffff8156509b: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81e88c3e-ffffffff81e88c52: tomoyo_assign_domain.cold (STB_LOCAL)
ffffffff81600580-ffffffff81600885: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff82074766-ffffffff8207477a: tomoyo_assign_domain.cold (STB_LOCAL)
ffffffff816b14c0-ffffffff816b17c5: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff820f42c0-ffffffff820f42d4: tomoyo_assign_domain.cold (STB_LOCAL)
ffffffff816e9ed0-ffffffff816ea1d0: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/domain.c (0)
Location: security/tomoyo/domain.c:522
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff821d1705-ffffffff821d1719: tomoyo_assign_domain.cold (STB_LOCAL)
ffffffff81726be0-ffffffff81726ee0: tomoyo_assign_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffff80001057ff10)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffff80001057ff10-ffff8000105801c4: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c07323d4)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c07323d4-c07326bc: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (c0000000006ed700)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
c0000000006ed700-c0000000006edadc: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffe0003d0c00)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffe0003d0c00-ffffffe0003d0e6c: tomoyo_assign_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81484ff0)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81484ff0-ffffffff814852ce: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81475a10)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81475a10-ffffffff81475cee: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81481090)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81481090-ffffffff8148136e: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_assign_domain(const char *domainname, const bool transit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/domain.c (ffffffff81498c00)
Location: security/tomoyo/domain.c:524
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/securityfs_if.c:tomoyo_write_self
```
**Symbols:**

```
ffffffff81498c00-ffffffff81498ede: tomoyo_assign_domain (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
