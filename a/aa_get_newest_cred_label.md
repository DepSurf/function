# Function: <code>aa_get_newest_cred_label</code>

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
In security/apparmor/domain.c (ffffffff8137d998)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81383a96)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
  - security/apparmor/lsm.c:apparmor_file_open
```
```
In security/apparmor/resource.c (ffffffff81387501)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81388b66)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff813b712e)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813beb6b)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813c1fa1)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813c36ca)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff813ce42e)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813d5feb)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813d9441)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813dac5a)
Location: security/apparmor/include/context.h:79
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff813e262b)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff813e9ade)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff813ea6f6)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff813ebcac)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff8140931b)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8141143e)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff81411ff6)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814135ec)
Location: security/apparmor/include/context.h:90
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff8143a8f6)
Location: security/apparmor/include/cred.h:51
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81441627)
Location: security/apparmor/include/cred.h:51
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff814441b3)
Location: security/apparmor/include/cred.h:51
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81445935)
Location: security/apparmor/include/cred.h:51
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81457722)
Location: security/apparmor/include/cred.h:65
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8145f91e)
Location: security/apparmor/include/cred.h:65
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff81461266)
Location: security/apparmor/include/cred.h:65
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81462845)
Location: security/apparmor/include/cred.h:65
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81484ee0)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148ccbe)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff8148e557)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8148fb05)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff8149ee00)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814a6b7e)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff814a8417)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a99c5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff814f83c5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81504908)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff815057a7)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81507315)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81515515)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81520b78)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff815228d7)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff815243c5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff8151be96)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81526e28)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff81528ab7)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8152a5a5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81579f56)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff815850b8)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff81586da7)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81588945)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/task.c (ffffffff8160fd5b)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81618032)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81624a86)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff8162719f)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81629005)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/task.c (ffffffff816c277b)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff816caf52)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff816da744)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff816db1b3)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff816dd8df)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/task.c (ffffffff816fb32b)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81703a92)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81713ee4)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff817148a3)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81716eff)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/task.c (ffffffff817382db)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_get_task_label
```
```
In security/apparmor/domain.c (ffffffff81741294)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff81752994)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_task_kill
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff817532b3)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff81755a62)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffff800010594ce0)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffff80001059d4f0)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffff80001059eb3c)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffff8000105a03ec)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (c0745c44)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c074dcbc)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (c074f8cc)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c0751048)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (c000000000709ec4)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (c0000000007157f4)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (c00000000071865c)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (c00000000071a6dc)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffe0003e1e56)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffe0003e9898)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffe0003e9fde)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffe0003eb3ae)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff814973e0)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149f15e)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff814a09f7)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814a1fa5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81487e00)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8148fb7e)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff81491417)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814929c5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff81493480)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff8149b1fe)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff8149ca97)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff8149e045)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
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
In security/apparmor/domain.c (ffffffff814ab4f5)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/domain.c:aa_change_hat
```
```
In security/apparmor/lsm.c (ffffffff814b3692)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_capable
  - security/apparmor/lsm.c:apparmor_capget
```
```
In security/apparmor/resource.c (ffffffff814b5030)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/resource.c:aa_task_setrlimit
```
```
In security/apparmor/file.c (ffffffff814b6635)
Location: security/apparmor/include/cred.h:61
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_inherit_files
```
</details>
</li>
</ul>

## Differences
