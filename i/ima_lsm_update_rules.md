# Function: <code>ima_lsm_update_rules</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813997d1)
Location: security/integrity/ima/ima_policy.c:181
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813d60a2)
Location: security/integrity/ima/ima_policy.c:193
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813ed972)
Location: security/integrity/ima/ima_policy.c:193
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff813f9d8e)
Location: security/integrity/ima/ima_policy.c:221
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81422221)
Location: security/integrity/ima/ima_policy.c:221
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81454923)
Location: security/integrity/ima/ima_policy.c:230
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81471bf3)
Location: security/integrity/ima/ima_policy.c:258
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_match_policy
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
In security/integrity/ima/ima_policy.c (ffffffff8149f51d)
Location: security/integrity/ima/ima_policy.c:321
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b9aed)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ima_lsm_update_rules();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81518b50)
Location: security/integrity/ima/ima_policy.c:380
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81518b50-ffffffff81518c63: ima_lsm_update_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ima_lsm_update_rules();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81535b90)
Location: security/integrity/ima/ima_policy.c:446
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81535b90-ffffffff81535cab: ima_lsm_update_rules (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ima_lsm_update_rules();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:455
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff8153e1f0-ffffffff8153e3a3: ima_lsm_update_rules (STB_LOCAL)
ffffffff81be3e3b-ffffffff81be3e51: ima_lsm_update_rules.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ima_lsm_update_rules();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:467
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff8159d300-ffffffff8159d6f9: ima_lsm_update_rules (STB_LOCAL)
ffffffff81cd70de-ffffffff81cd70f4: ima_lsm_update_rules.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ima_lsm_update_rules();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:484
Inline: False
Direct callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
**Symbols:**

```
ffffffff81642590-ffffffff81642991: ima_lsm_update_rules (STB_LOCAL)
ffffffff81e8a335-ffffffff81e8a34b: ima_lsm_update_rules.cold (STB_LOCAL)
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
In security/integrity/ima/ima_policy.c (ffffffff816fc9f7)
Location: security/integrity/ima/ima_policy.c:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
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
In security/integrity/ima/ima_policy.c (ffffffff81736a27)
Location: security/integrity/ima/ima_policy.c:505
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
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
In security/integrity/ima/ima_policy.c (ffffffff817774e7)
Location: security/integrity/ima/ima_policy.c:500
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b1e70)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c076152c)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c00000000073307c)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f97e2)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814b20cd)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814a2aed)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814ae15d)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff814c6bad)
Location: security/integrity/ima/ima_policy.c:324
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_lsm_policy_change
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
