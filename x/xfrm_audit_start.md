# Function: <code>xfrm_audit_start</code>

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
In net/xfrm/xfrm_policy.c (ffffffff817b1425)
Location: include/net/xfrm.h:694
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff817b8043)
Location: include/net/xfrm.h:694
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
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
In net/xfrm/xfrm_policy.c (ffffffff8181eaf5)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81825253)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81850375)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81856bb3)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff818740c5)
Location: include/net/xfrm.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff8187a533)
Location: include/net/xfrm.h:727
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff818f4635)
Location: include/net/xfrm.h:733
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff818fafa3)
Location: include/net/xfrm.h:733
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff8194ae05)
Location: include/net/xfrm.h:734
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819527c3)
Location: include/net/xfrm.h:734
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff8197d8a5)
Location: include/net/xfrm.h:746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81984d63)
Location: include/net/xfrm.h:746
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff819e6ce5)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819eefa3)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81a1ddc5)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25e73)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81b0fd05)
Location: include/net/xfrm.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b181c3)
Location: include/net/xfrm.h:669
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81b1cc25)
Location: include/net/xfrm.h:672
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b26933)
Location: include/net/xfrm.h:672
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81b0a9a5)
Location: include/net/xfrm.h:672
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14563)
Location: include/net/xfrm.h:672
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81bce185)
Location: include/net/xfrm.h:668
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8663)
Location: include/net/xfrm.h:668
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81d633c5)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6ec97)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81f2e065)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3a3a7)
Location: include/net/xfrm.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81f8f815)
Location: include/net/xfrm.h:695
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81f99dc7)
Location: include/net/xfrm.h:695
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff8205b9a5)
Location: include/net/xfrm.h:695
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff82067127)
Location: include/net/xfrm.h:695
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffff800010cd9630)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffff800010ce347c)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (c0de47a8)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c0deca60)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (c000000000dfb380)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (c000000000e06b84)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffe00082acb0)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffe000831c8c)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff819bd455)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819c5503)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff8197a245)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff819822f3)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81a27ed5)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2ff83)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
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
In net/xfrm/xfrm_policy.c (ffffffff81a33505)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_delete
  - net/xfrm/xfrm_policy.c:xfrm_audit_policy_add
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b903)
Location: include/net/xfrm.h:673
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_audit_state_icvfail
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound
  - net/xfrm/xfrm_state.c:xfrm_audit_state_notfound_simple
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay
  - net/xfrm/xfrm_state.c:xfrm_audit_state_replay_overflow
  - net/xfrm/xfrm_state.c:xfrm_audit_state_delete
  - net/xfrm/xfrm_state.c:xfrm_audit_state_add
```
</details>
</li>
</ul>

## Differences
