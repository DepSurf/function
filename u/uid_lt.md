# Function: <code>uid_lt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff8112d562)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81137292)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811387f2)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff813f91d0)
Location: include/linux/uidgid.h:90
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:90
Inline: True
```
**Symbols:**

```
ffffffff813f91d0-ffffffff813f91db: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811454f1)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81421660)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff81421660-ffffffff8142166b: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153e91)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81453b90)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff81453b90-ffffffff81453b96: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81160c31)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81470d60)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff81470d60-ffffffff81470d66: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116d295)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149e750)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff8149e750-ffffffff8149e756: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81179135)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b8c00)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff814b8c00-ffffffff814b8c06: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d75be)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8118c175)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff81496a3f)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81518860)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a3f8a8)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81518860-ffffffff81518866: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d23be)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81189395)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff814b44af)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81535820)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a42514)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81535820-ffffffff81535826: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810d3f9e)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8118a205)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff814ba2cf)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153de50)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a27224)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff8153de50-ffffffff8153de56: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff810e711e)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811b2cc5)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff81512aff)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159cd20)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81adbfb4)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff8159cd20-ffffffff8159cd26: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81101098)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/cred.c:cred_fscmp
```
```
In kernel/auditfilter.c (ffffffff811e5085)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff815a4ee6)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/integrity/ima/ima_policy.c (ffffffff81641ef0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81c5d2df)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81641ef0-ffffffff81641efe: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81126198)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/cred.c:cred_fscmp
```
```
In kernel/auditfilter.c (ffffffff8122b0c5)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff8164ecc6)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/audit.c (ffffffff816c1a11)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff816f9fc0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81e13a8f)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff816f9fc0-ffffffff816f9fce: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff81133648)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/cred.c:cred_fscmp
```
```
In kernel/auditfilter.c (ffffffff8124172d)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (ffffffff81687526)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/audit.c (ffffffff816fa001)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff817340f0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81e873cf)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff817340f0-ffffffff817340fe: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (ffffffff8113e5b8)
Location: include/linux/uidgid.h:83
Inline: True
Inline callers:
  - kernel/cred.c:cred_fscmp
```
```
In kernel/auditfilter.c (ffffffff8125b55d)
Location: include/linux/uidgid.h:83
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:83
Inline: True
```
```
In security/keys/key.c (ffffffff816c3a06)
Location: include/linux/uidgid.h:83
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/apparmor/audit.c (ffffffff81736da1)
Location: include/linux/uidgid.h:83
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774be0)
Location: include/linux/uidgid.h:83
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81f493df)
Location: include/linux/uidgid.h:83
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81774be0-ffffffff81774bee: uid_lt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffff8000101ee338)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffff8000105b0f28)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffff8000105b0f28-ffff8000105b0f34: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (c042e434)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (c07605bc)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
c07605bc-c07605d8: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (c000000000260f50)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (c000000000730de0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
c000000000730de0-c000000000730df4: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffe000162532)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f89bc)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffe0003f89bc-ffffffe0003f89d0: uid_lt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81171755)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b11e0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff814b11e0-ffffffff814b11e6: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811648f5)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a1c00)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff814a1c00-ffffffff814a1c06: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116f525)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ad270)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff814ad270-ffffffff814ad276: uid_lt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_lt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8117cd15)
Location: include/linux/uidgid.h:91
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In fs/quota/kqid.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c5cc0)
Location: include/linux/uidgid.h:91
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:91
Inline: True
```
**Symbols:**

```
ffffffff814c5cc0-ffffffff814c5cc6: uid_lt (STB_LOCAL)
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
