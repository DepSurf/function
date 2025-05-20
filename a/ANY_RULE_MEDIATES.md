# Function: <code>ANY_RULE_MEDIATES</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/task.c (ffffffff8161071e)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff81610cc3)
Location: security/apparmor/include/policy.h:299
Inline: True
Inline callers:
  - security/apparmor/ipc.c:profile_signal_perm
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
In security/apparmor/task.c (ffffffff816c316f)
Location: security/apparmor/include/policy.h:305
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff816c3720)
Location: security/apparmor/include/policy.h:305
Inline: True
Inline callers:
  - security/apparmor/ipc.c:profile_signal_perm
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
In security/apparmor/task.c (ffffffff816fbd0f)
Location: security/apparmor/include/policy.h:336
Inline: True
Inline callers:
  - security/apparmor/task.c:aa_may_ptrace
  - security/apparmor/task.c:aa_may_ptrace
```
```
In security/apparmor/ipc.c (ffffffff816fc303)
Location: security/apparmor/include/policy.h:336
Inline: True
Inline callers:
  - security/apparmor/ipc.c:profile_signal_perm
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
In security/apparmor/policy.c (ffffffff81743ff3)
Location: security/apparmor/include/policy.h:333
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
