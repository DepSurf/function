# Function: <code>uid_gt</code>

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
Location: include/linux/uidgid.h:70
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:70
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
In kernel/auditfilter.c (ffffffff8112d56b)
Location: include/linux/uidgid.h:70
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:70
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
In kernel/auditfilter.c (ffffffff8113729b)
Location: include/linux/uidgid.h:70
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:70
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:70
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811387fb)
Location: include/linux/uidgid.h:70
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:70
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff813f91c0)
Location: include/linux/uidgid.h:70
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:70
Inline: True
```
**Symbols:**

```
ffffffff813f91c0-ffffffff813f91cb: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff811454f9)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81421650)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff81421650-ffffffff8142165b: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/auditfilter.c (ffffffff81153e99)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81453b80)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff81453b80-ffffffff81453b86: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81160c41)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81470d50)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff81470d50-ffffffff81470d56: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116d2c9)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149e740)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff8149e740-ffffffff8149e746: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81179169)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b8bf0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff814b8bf0-ffffffff814b8bf6: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8118c1a9)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81518850)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a3f8ad)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81518850-ffffffff81518856: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811893c9)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81535810)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a42519)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81535810-ffffffff81535816: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8118a236)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153de40)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81a27229)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff8153de40-ffffffff8153de46: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811b2cf6)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159cd10)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81adbfb9)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff8159cd10-ffffffff8159cd16: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811e50d4)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81641ed0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81c5d2e4)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81641ed0-ffffffff81641ede: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8122b114)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff816f9f80)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81e13a94)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff816f9f80-ffffffff816f9f8e: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81241707)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff817340b0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81e873d4)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff817340b0-ffffffff817340be: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:63
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8125b537)
Location: include/linux/uidgid.h:63
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:63
Inline: True
```
```
In security/apparmor/audit.c (0)
Location: include/linux/uidgid.h:63
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81774ba0)
Location: include/linux/uidgid.h:63
Inline: False
```
```
In net/core/fib_rules.c (ffffffff81f493e4)
Location: include/linux/uidgid.h:63
Inline: True
Inline callers:
  - net/core/fib_rules.c:fib_rules_lookup
```
**Symbols:**

```
ffffffff81774ba0-ffffffff81774bae: uid_gt (STB_LOCAL)
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
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffff8000101ee394)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffff8000105b0f18)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffff8000105b0f18-ffff8000105b0f24: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (c042e444)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (c07605a0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
c07605a0-c07605bc: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (c000000000260f70)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (c000000000730dc0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
c000000000730dc0-c000000000730dd4: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffe000162544)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f89a8)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffe0003f89a8-ffffffe0003f89bc: uid_gt (STB_LOCAL)
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
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81171789)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b11d0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff814b11d0-ffffffff814b11d6: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81164929)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a1bf0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff814a1bf0-ffffffff814a1bf6: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116f559)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ad260)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff814ad260-ffffffff814ad266: uid_gt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool uid_gt(kuid_t left, kuid_t right);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cred.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8117cd49)
Location: include/linux/uidgid.h:71
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In security/keys/key.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c5cb0)
Location: include/linux/uidgid.h:71
Inline: False
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:71
Inline: True
```
**Symbols:**

```
ffffffff814c5cb0-ffffffff814c5cb6: uid_gt (STB_LOCAL)
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
