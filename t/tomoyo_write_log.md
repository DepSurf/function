# Function: <code>tomoyo_write_log</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81367840)
Location: security/tomoyo/audit.c:411
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff81367840-ffffffff813678fc: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8139d930)
Location: security/tomoyo/audit.c:411
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8139d930-ffffffff8139d9ec: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813b4510)
Location: security/tomoyo/audit.c:411
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff813b4510-ffffffff813b45cc: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813caeb0)
Location: security/tomoyo/audit.c:411
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff813caeb0-ffffffff813caf61: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff813f1340)
Location: security/tomoyo/audit.c:412
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff813f1340-ffffffff813f13f1: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81422280)
Location: security/tomoyo/audit.c:412
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff81422280-ffffffff8142233c: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8143e8e0)
Location: security/tomoyo/audit.c:412
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8143e8e0-ffffffff8143e99c: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146c530)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8146c530-ffffffff8146c5ee: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81486310)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff81486310-ffffffff814863ce: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814dc500)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff814dc500-ffffffff814dc5be: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff814f9940)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff814f9940-ffffffff814f99fe: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81500680)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff81500680-ffffffff8150073e: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8155b920)
Location: security/tomoyo/audit.c:420
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8155b920-ffffffff8155b9de: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff815f67f0)
Location: security/tomoyo/audit.c:420
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff815f67f0-ffffffff815f68d1: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816a7320)
Location: security/tomoyo/audit.c:420
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff816a7320-ffffffff816a73e8: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff816dfd20)
Location: security/tomoyo/audit.c:420
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff816dfd20-ffffffff816dfde8: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8171c9a0)
Location: security/tomoyo/audit.c:420
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8171c9a0-ffffffff8171ca68: tomoyo_write_log (STB_GLOBAL)
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
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffff800010578780)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffff800010578780-ffff80001057885c: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (c072b6e4)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
c072b6e4-c072b774: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (c0000000006e2360)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
c0000000006e2360-c0000000006e2418: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffe0003cac3e)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffe0003cac3e-ffffffe0003caca4: tomoyo_write_log (STB_GLOBAL)
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
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8147e8f0)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8147e8f0-ffffffff8147e9ae: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8146f310)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8146f310-ffffffff8146f3ce: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff8147a990)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff8147a990-ffffffff8147aa4e: tomoyo_write_log (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_write_log(struct tomoyo_request_info *r, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/audit.c (ffffffff81492470)
Location: security/tomoyo/audit.c:419
Inline: False
Direct callers:
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/domain.c:tomoyo_assign_domain
  - security/tomoyo/util.c:tomoyo_domain_quota_is_ok
```
**Symbols:**

```
ffffffff81492470-ffffffff8149252e: tomoyo_write_log (STB_GLOBAL)
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
