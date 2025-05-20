# Function: <code>tomoyo_find_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813745f0)
Location: security/tomoyo/util.c:597
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff813745f0-ffffffff81374689: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813aaa00)
Location: security/tomoyo/util.c:597
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff813aaa00-ffffffff813aaa99: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813c1580)
Location: security/tomoyo/util.c:597
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff813c1580-ffffffff813c1619: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813d7f00)
Location: security/tomoyo/util.c:599
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff813d7f00-ffffffff813d7f99: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff813fe350)
Location: security/tomoyo/util.c:579
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff813fe350-ffffffff813fe3e9: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8142f240)
Location: security/tomoyo/util.c:579
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8142f240-ffffffff8142f2d9: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8144bc60)
Location: security/tomoyo/util.c:579
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8144bc60-ffffffff8144bcf9: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814799c0)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff814799c0-ffffffff81479a5c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814936c0)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff814936c0-ffffffff8149375c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff814eaa90)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff814eaa90-ffffffff814eab2c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81507e90)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff81507e90-ffffffff81507f2c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8150ea10)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8150ea10-ffffffff8150eaab: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (0)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff81cd61a3-ffffffff81cd61b7: tomoyo_find_domain.cold (STB_LOCAL)
ffffffff8156c560-ffffffff8156c607: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (0)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff81e88f89-ffffffff81e88f9e: tomoyo_find_domain.cold (STB_LOCAL)
ffffffff816088f0-ffffffff816089a7: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (0)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff82074a1a-ffffffff82074a2f: tomoyo_find_domain.cold (STB_LOCAL)
ffffffff816ba1a0-ffffffff816ba257: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (0)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff820f4571-ffffffff820f4586: tomoyo_find_domain.cold (STB_LOCAL)
ffffffff816f2b40-ffffffff816f2bf7: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/util.c (0)
Location: security/tomoyo/util.c:612
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/common.c:tomoyo_select_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff821d19b6-ffffffff821d19cb: tomoyo_find_domain.cold (STB_LOCAL)
ffffffff8172f900-ffffffff8172f9b7: tomoyo_find_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffff800010588a18)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffff800010588a18-ffff800010588af0: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0739e60)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
c0739e60-c0739f28: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (c0000000006f9160)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
c0000000006f9160-c0000000006f9404: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffe0003d79fc)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffe0003d79fc-ffffffe0003d7a7a: tomoyo_find_domain (STB_GLOBAL)
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
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8148bca0)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8148bca0-ffffffff8148bd3c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8147c6c0)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8147c6c0-ffffffff8147c75c: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff81487d40)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff81487d40-ffffffff81487ddc: tomoyo_find_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tomoyo_domain_info *tomoyo_find_domain(const char *domainname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/util.c (ffffffff8149f880)
Location: security/tomoyo/util.c:590
Inline: False
Direct callers:
  - security/tomoyo/common.c:tomoyo_write_control
  - security/tomoyo/common.c:tomoyo_write_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
```
**Symbols:**

```
ffffffff8149f880-ffffffff8149f91c: tomoyo_find_domain (STB_GLOBAL)
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
