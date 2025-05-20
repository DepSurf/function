# Function: <code>auditd_set</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81136a9c)
Location: kernel/audit.c:466
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81143437)
Location: kernel/audit.c:466
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81151f2a)
Location: kernel/audit.c:509
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8115ebe9)
Location: kernel/audit.c:505
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116b080)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81176f4b)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811898c7)
Location: kernel/audit.c:494
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int auditd_set(struct pid *pid, u32 portid, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81183a40)
Location: kernel/audit.c:499
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81183a40-ffffffff81183b76: auditd_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187c1c)
Location: kernel/audit.c:499
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811b007c)
Location: kernel/audit.c:499
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e2274)
Location: kernel/audit.c:500
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81228118)
Location: kernel/audit.c:498
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8123e725)
Location: kernel/audit.c:498
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int auditd_set(struct pid *pid, u32 portid, struct net *net, struct sk_buff *skb, bool *ack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/audit.c (0)
Location: kernel/audit.c:500
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81254880-ffffffff81254a3a: auditd_set (STB_LOCAL)
ffffffff821b6c02-ffffffff821b6c16: auditd_set.cold (STB_LOCAL)
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
In kernel/audit.c (ffff8000101ebec4)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (c042bb2c)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (c00000000025d794)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffe00016064c)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116f56b)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116270b)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116d33b)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8117ab31)
Location: kernel/audit.c:492
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
