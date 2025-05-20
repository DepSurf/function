# Function: <code>mls_read_range_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81350700)
Location: security/selinux/ss/policydb.c:993
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:policydb_read
```
**Symbols:**

```
ffffffff81350700-ffffffff813508c7: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff81386750)
Location: security/selinux/ss/policydb.c:993
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81386750-ffffffff81386918: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff8139d200)
Location: security/selinux/ss/policydb.c:993
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff8139d200-ffffffff8139d3c8: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813b44f0)
Location: security/selinux/ss/policydb.c:995
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff813b44f0-ffffffff813b46c2: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff813da640)
Location: security/selinux/ss/policydb.c:995
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff813da640-ffffffff813da812: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:995
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff8140ab50-ffffffff8140ace2: mls_read_range_helper (STB_LOCAL)
ffffffff8140de46-ffffffff8140de94: mls_read_range_helper.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:1006
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81426ff0-ffffffff81427182: mls_read_range_helper (STB_LOCAL)
ffffffff8142aebd-ffffffff8142af0b: mls_read_range_helper.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:958
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81454850-ffffffff814549d6: mls_read_range_helper (STB_LOCAL)
ffffffff814587c5-ffffffff8145882b: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff8146e5f0-ffffffff8146e776: mls_read_range_helper (STB_LOCAL)
ffffffff81472565-ffffffff814725cb: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:946
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff814c3b50-ffffffff814c3cd4: mls_read_range_helper (STB_LOCAL)
ffffffff814c77d8-ffffffff814c783e: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:978
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff814e14a0-ffffffff814e1624: mls_read_range_helper (STB_LOCAL)
ffffffff81bf09e1-ffffffff81bf0a47: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:976
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff814e7800-ffffffff814e7984: mls_read_range_helper (STB_LOCAL)
ffffffff81be2b32-ffffffff81be2b98: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:976
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff81541090-ffffffff81541214: mls_read_range_helper (STB_LOCAL)
ffffffff81cd466f-ffffffff81cd46d5: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:970
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff815d9410-ffffffff815d95b3: mls_read_range_helper (STB_LOCAL)
ffffffff81e8757e-ffffffff81e875db: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816881d0)
Location: security/selinux/ss/policydb.c:970
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff816881d0-ffffffff816883ca: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816c12a0)
Location: security/selinux/ss/policydb.c:970
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff816c12a0-ffffffff816c149e: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffff816fdce0)
Location: security/selinux/ss/policydb.c:991
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffff816fdce0-ffffffff816fdede: mls_read_range_helper (STB_LOCAL)
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
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffff80001055e5f8)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffff80001055e5f8-ffff80001055e7a4: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c07121fc)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
c07121fc-c071238c: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (c0000000006bdaf0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
c0000000006bdaf0-c0000000006bdd14: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/policydb.c (ffffffe0003b3a06)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:context_read_and_validate
```
**Symbols:**

```
ffffffe0003b3a06-ffffffe0003b3b82: mls_read_range_helper (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81466bd0-ffffffff81466d56: mls_read_range_helper (STB_LOCAL)
ffffffff8146ab45-ffffffff8146abab: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81457600-ffffffff81457786: mls_read_range_helper (STB_LOCAL)
ffffffff8145b575-ffffffff8145b5db: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff81462c70-ffffffff81462df6: mls_read_range_helper (STB_LOCAL)
ffffffff81466be5-ffffffff81466c4b: mls_read_range_helper.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mls_read_range_helper(struct mls_range *r, void *fp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/policydb.c (0)
Location: security/selinux/ss/policydb.c:960
Inline: False
Direct callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:user_read
```
**Symbols:**

```
ffffffff8147a470-ffffffff8147a5f6: mls_read_range_helper (STB_LOCAL)
ffffffff8147e3c5-ffffffff8147e42b: mls_read_range_helper.cold (STB_LOCAL)
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
