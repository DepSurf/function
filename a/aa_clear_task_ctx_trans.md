# Function: <code>aa_clear_task_ctx_trans</code>

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
In security/apparmor/context.c (ffffffff813774f4)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_replace_current_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_restore_previous_label
```
```
In security/apparmor/domain.c (ffffffff8137d008)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/context.c (ffffffff813b05ac)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff813b65c9)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/context.c (ffffffff813c772c)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff813cd92f)
Location: security/apparmor/include/context.h:197
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/context.c (ffffffff813dcfa2)
Location: security/apparmor/include/context.h:239
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff813e1f8f)
Location: security/apparmor/include/context.h:239
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/context.c (ffffffff81403b00)
Location: security/apparmor/include/context.h:239
Inline: True
Inline callers:
  - security/apparmor/context.c:aa_restore_previous_label
  - security/apparmor/context.c:aa_set_current_onexec
  - security/apparmor/context.c:aa_replace_current_label
```
```
In security/apparmor/domain.c (ffffffff81408c07)
Location: security/apparmor/include/context.h:239
Inline: True
Inline callers:
  - security/apparmor/domain.c:apparmor_bprm_set_creds
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
In security/apparmor/task.c (ffffffff81434c4c)
Location: security/apparmor/include/task.h:83
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff81440d8a)
Location: security/apparmor/include/task.h:83
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8145183e)
Location: security/apparmor/include/task.h:73
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8145dd11)
Location: security/apparmor/include/task.h:73
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8147f24d)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8148b441)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff81498f4d)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff814a5301)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff814f1550)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff81500581)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8150e7f0)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8151d931)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff815151ec)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff81524141)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8157319c)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff81582461)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8161048c)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff816216e1)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff816c2eec)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff816d5021)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff816fba9c)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8170e0e1)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff81738a52)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8174c051)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffff80001058ebbc)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffff80001059b490)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (c073fa48)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (c074c460)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (c000000000701a28)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (c00000000071314c)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffe0003dc9fc)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffe0003e6c98)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8149152d)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8149d8e1)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff81481f4d)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff8148e301)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff8148d5cd)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff81499981)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
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
In security/apparmor/task.c (ffffffff814a549c)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_restore_previous_label
  - security/apparmor/task.c:aa_replace_current_label
```
```
In security/apparmor/lsm.c (ffffffff814b1b31)
Location: security/apparmor/include/task.h:69
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_bprm_committed_creds
```
</details>
</li>
</ul>

## Differences
