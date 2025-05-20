# Function: <code>may_change_ptraced_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8137a590)
Location: security/apparmor/domain.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
```
**Symbols:**

```
ffffffff8137a590-ffffffff8137a629: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813b3550)
Location: security/apparmor/domain.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813b3550-ffffffff813b3603: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813ca760)
Location: security/apparmor/domain.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813ca760-ffffffff813ca813: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff813dffe0)
Location: security/apparmor/domain.c:62
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff813dffe0-ffffffff813e0071: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81406760)
Location: security/apparmor/domain.c:62
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81406760-ffffffff814067f7: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81437290)
Location: security/apparmor/domain.c:63
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81437290-ffffffff8143732d: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81454b10)
Location: security/apparmor/domain.c:63
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81454b10-ffffffff81454bad: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814824c0)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814824c0-ffffffff81482553: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8149c080)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff8149c080-ffffffff8149c113: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814f42f0)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff814f42f0-ffffffff814f43a1: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81511430)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81511430-ffffffff815114e9: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81517da0)
Location: security/apparmor/domain.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81517da0-ffffffff81517e59: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81575da0)
Location: security/apparmor/domain.c:61
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81575da0-ffffffff81575e59: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81613480)
Location: security/apparmor/domain.c:42
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81613480-ffffffff81613557: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_change_ptraced_domain(const struct cred *to_cred, struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816c60f0)
Location: security/apparmor/domain.c:43
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816c60f0-ffffffff816c6218: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_change_ptraced_domain(const struct cred *to_cred, struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff816feec0)
Location: security/apparmor/domain.c:43
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff816feec0-ffffffff816fefe8: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_change_ptraced_domain(const struct cred *to_cred, struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff8173c450)
Location: security/apparmor/domain.c:43
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8173c450-ffffffff8173c579: may_change_ptraced_domain (STB_LOCAL)
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
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffff800010591b90)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffff800010591b90-ffff800010591c50: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c07427a4)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c07427a4-c0742858: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (c000000000705ae0)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
c000000000705ae0-c000000000705c08: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffe0003df3ca)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffe0003df3ca-ffffffe0003df45a: may_change_ptraced_domain (STB_LOCAL)
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
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81494660)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81494660-ffffffff814946f3: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81485080)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81485080-ffffffff81485113: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff81490700)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff81490700-ffffffff81490793: may_change_ptraced_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int may_change_ptraced_domain(struct aa_label *to_label, const char **info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/domain.c (ffffffff814a8610)
Location: security/apparmor/domain.c:59
Inline: False
Direct callers:
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_profile
  - security/apparmor/domain.c:aa_change_hat
  - security/apparmor/domain.c:apparmor_bprm_set_creds
```
**Symbols:**

```
ffffffff814a8610-ffffffff814a86bc: may_change_ptraced_domain (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred *to_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>to_label, info</code> ➡️ <code>to_cred, to_label, info</code>
</li>
</ul>
</details>
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
