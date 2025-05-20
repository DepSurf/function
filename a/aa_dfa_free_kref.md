# Function: <code>aa_dfa_free_kref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81379030)
Location: security/apparmor/match.c:212
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff81379030-ffffffff81379040: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813b1e07)
Location: security/apparmor/match.c:216
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff813b1dd0-ffffffff813b1de0: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813c8fc7)
Location: security/apparmor/match.c:216
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff813c8f90-ffffffff813c8fa0: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813de5e0)
Location: security/apparmor/match.c:216
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
**Symbols:**

```
ffffffff813de5e0-ffffffff813de628: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81404f70)
Location: security/apparmor/match.c:216
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
**Symbols:**

```
ffffffff81404f70-ffffffff81404fb8: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81436050)
Location: security/apparmor/match.c:267
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff81436050-ffffffff81436097: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81452c70)
Location: security/apparmor/match.c:267
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff81452c70-ffffffff81452cb7: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81480620)
Location: security/apparmor/match.c:263
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff81480620-ffffffff81480667: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149a320)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff8149a320-ffffffff8149a367: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f2dcb)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff814f2e20-ffffffff814f2e67: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8150ff9b)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff8150fff0-ffffffff81510037: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8151682b)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff81516880-ffffffff815168c7: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8157482b)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff81574880-ffffffff815748c7: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816122b7)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
**Symbols:**

```
ffffffff81612350-ffffffff816123a3: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff83ed3707)
Location: security/apparmor/match.c:288
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
Direct callers:
  - security/apparmor/notify.c:free_listener
```
**Symbols:**

```
ffffffff816c4ff0-ffffffff816c5043: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff816fda00)
Location: security/apparmor/match.c:244
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/notify.c:free_listener
```
**Symbols:**

```
ffffffff816fda00-ffffffff816fda86: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8173af60)
Location: security/apparmor/match.c:244
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/notify.c:free_listener
```
**Symbols:**

```
ffffffff8173af60-ffffffff8173afe6: aa_dfa_free_kref (STB_GLOBAL)
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
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff8000105903c0)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffff8000105903c0-ffff800010590414: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c07410e4)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
c07410e4-c074112c: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c000000000703950)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
c000000000703950-c0000000007039d4: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003dde80)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffe0003dde80-ffffffe0003dded2: aa_dfa_free_kref (STB_GLOBAL)
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
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81492900)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff81492900-ffffffff81492947: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81483320)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff81483320-ffffffff81483367: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148e9a0)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff8148e9a0-ffffffff8148e9e7: aa_dfa_free_kref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aa_dfa_free_kref(struct kref *kref);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a68b0)
Location: security/apparmor/match.c:278
Inline: False
Direct callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
**Symbols:**

```
ffffffff814a68b0-ffffffff814a68f7: aa_dfa_free_kref (STB_GLOBAL)
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
