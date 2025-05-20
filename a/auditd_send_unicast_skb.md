# Function: <code>auditd_send_unicast_skb</code>

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
In kernel/audit.c (ffffffff81136795)
Location: kernel/audit.c:625
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
In kernel/audit.c (ffffffff81143125)
Location: kernel/audit.c:625
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
In kernel/audit.c (ffffffff81151a8c)
Location: kernel/audit.c:668
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
In kernel/audit.c (ffffffff8115e741)
Location: kernel/audit.c:664
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
In kernel/audit.c (ffffffff8116ad5d)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffff81176c08)
Location: kernel/audit.c:651
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81186e90)
Location: kernel/audit.c:653
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81186e90-ffffffff81186fa1: auditd_send_unicast_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811841c0)
Location: kernel/audit.c:658
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811841c0-ffffffff81184311: auditd_send_unicast_skb.isra.0 (STB_LOCAL)
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
In kernel/audit.c (ffffffff81186253)
Location: kernel/audit.c:658
Inline: True
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
In kernel/audit.c (ffffffff811ae643)
Location: kernel/audit.c:680
Inline: True
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
In kernel/audit.c (ffffffff811e057a)
Location: kernel/audit.c:681
Inline: True
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
In kernel/audit.c (ffffffff8122632a)
Location: kernel/audit.c:679
Inline: True
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
In kernel/audit.c (ffffffff8123c90a)
Location: kernel/audit.c:679
Inline: True
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
In kernel/audit.c (ffffffff8125681a)
Location: kernel/audit.c:690
Inline: True
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
In kernel/audit.c (ffff8000101ebbc0)
Location: kernel/audit.c:651
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
In kernel/audit.c (c042b7c4)
Location: kernel/audit.c:651
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
In kernel/audit.c (c00000000025d1f0)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffe00016030c)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffff8116f228)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffff811623c8)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffff8116cff8)
Location: kernel/audit.c:651
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
In kernel/audit.c (ffffffff8117a7d3)
Location: kernel/audit.c:651
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
</ul>

## Differences
