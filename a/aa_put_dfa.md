# Function: <code>aa_put_dfa</code>

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
In security/apparmor/match.c (ffffffff8137904c)
Location: security/apparmor/include/match.h:155
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8137f960)
Location: security/apparmor/include/match.h:155
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:155
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
In security/apparmor/match.c (ffffffff813b1dec)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff813b91ea)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:156
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
In security/apparmor/match.c (ffffffff813c8fac)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff813d05aa)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff813de63c)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff813e3c39)
Location: security/apparmor/include/match.h:156
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:156
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81404fcc)
Location: security/apparmor/include/match.h:156
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8140aa57)
Location: security/apparmor/include/match.h:156
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814360ad)
Location: security/apparmor/include/match.h:181
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8143c275)
Location: security/apparmor/include/match.h:181
Inline: True
```
```
In security/apparmor/policy_unpack.c (0)
Location: security/apparmor/include/match.h:181
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81452ccd)
Location: security/apparmor/include/match.h:181
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff814590e5)
Location: security/apparmor/include/match.h:181
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148067d)
Location: security/apparmor/include/match.h:177
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff81486863)
Location: security/apparmor/include/match.h:177
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149a37d)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff814a0713)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814f2d54)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff814fa6f9)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8150ff24)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff81517479)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815167b4)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8151dd29)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff815747b4)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8157be25)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff81612264)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff8161a4d2)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
  - security/apparmor/policy.c:aa_free_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff83ed36b4)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff816ccf3c)
Location: security/apparmor/include/match.h:183
Inline: True
```
```
In security/apparmor/notify.c (ffffffff816e9dc2)
Location: security/apparmor/include/match.h:183
Inline: True
Inline callers:
  - security/apparmor/notify.c:free_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff81705f9d)
Location: security/apparmor/include/match.h:177
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff836f8c05)
Location: security/apparmor/include/match.h:177
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
```
```
In security/apparmor/notify.c (ffffffff81723eb2)
Location: security/apparmor/include/match.h:177
Inline: True
Inline callers:
  - security/apparmor/notify.c:free_listener
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/policy.c (ffffffff817438ad)
Location: security/apparmor/include/match.h:177
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8392c102)
Location: security/apparmor/include/match.h:177
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:apparmor_init
  - security/apparmor/lsm.c:aa_setup_dfa_engine
  - security/apparmor/lsm.c:aa_setup_dfa_engine
```
```
In security/apparmor/notify.c (ffffffff817651b2)
Location: security/apparmor/include/match.h:177
Inline: True
Inline callers:
  - security/apparmor/notify.c:free_listener
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffff800010590434)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffff8000105964d0)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c074114c)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (c07475c4)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (c0000000007039f8)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (c00000000070c0b8)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffe0003ddeec)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffe0003e3286)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8149295d)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff81498cf3)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148337d)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff81489713)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff8148e9fd)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff81494d93)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/match.c (ffffffff814a690d)
Location: security/apparmor/include/match.h:176
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_teardown_dfa_engine
  - security/apparmor/match.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy.c (ffffffff814acdb3)
Location: security/apparmor/include/match.h:176
Inline: True
```
</details>
</li>
</ul>

## Differences
