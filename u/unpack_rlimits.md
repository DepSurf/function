# Function: <code>unpack_rlimits</code>

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
In security/apparmor/policy_unpack.c (ffffffff81382199)
Location: security/apparmor/policy_unpack.c:464
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813bbdd8)
Location: security/apparmor/policy_unpack.c:474
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813d32e8)
Location: security/apparmor/policy_unpack.c:474
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff813e5efc)
Location: security/apparmor/policy_unpack.c:531
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8140d0ec)
Location: security/apparmor/policy_unpack.c:531
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8143ed2b)
Location: security/apparmor/policy_unpack.c:577
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8145bc44)
Location: security/apparmor/policy_unpack.c:545
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8148938d)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814a3237)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff814fdba0)
Location: security/apparmor/policy_unpack.c:632
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff814fdba0-ffffffff814fdd07: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8151ae00)
Location: security/apparmor/policy_unpack.c:632
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8151ae00-ffffffff8151af67: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81521540)
Location: security/apparmor/policy_unpack.c:632
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81521540-ffffffff815216a7: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_profile *profile);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8157f6e0)
Location: security/apparmor/policy_unpack.c:632
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8157f6e0-ffffffff8157f866: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_ruleset *rules);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8161dfa0)
Location: security/apparmor/policy_unpack.c:643
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8161dfa0-ffffffff8161e144: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_ruleset *rules);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff816d13a0)
Location: security/apparmor/policy_unpack.c:611
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff816d13a0-ffffffff816d1544: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_ruleset *rules);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff8170a2b0)
Location: security/apparmor/policy_unpack.c:622
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff8170a2b0-ffffffff8170a442: unpack_rlimits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool unpack_rlimits(struct aa_ext *e, struct aa_ruleset *rules);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/policy_unpack.c (ffffffff81747db0)
Location: security/apparmor/policy_unpack.c:625
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:unpack_profile
```
**Symbols:**

```
ffffffff81747db0-ffffffff81747f42: unpack_rlimits (STB_LOCAL)
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
In security/apparmor/policy_unpack.c (ffff800010598f9c)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (c074a250)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (c000000000710080)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffe0003e57f2)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8149b817)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff8148c237)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814978b7)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
In security/apparmor/policy_unpack.c (ffffffff814afa07)
Location: security/apparmor/policy_unpack.c:567
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:unpack_profile
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aa_ruleset *rules</code>
</li>
<li>
<b>Param removed. </b>
<code>struct aa_profile *profile</code>
</li>
</ul>
</details>
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
