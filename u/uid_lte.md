# Function: <code>uid_lte</code>

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
In kernel/auditfilter.c (0)
Location: include/linux/uidgid.h:100
Inline: True
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
In kernel/auditfilter.c (ffffffff8112d574)
Location: include/linux/uidgid.h:100
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
In kernel/auditfilter.c (ffffffff811372a4)
Location: include/linux/uidgid.h:100
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:100
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
In kernel/auditfilter.c (ffffffff81138804)
Location: include/linux/uidgid.h:100
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:100
Inline: True
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
In kernel/auditfilter.c (ffffffff81145501)
Location: include/linux/uidgid.h:101
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff81153ea1)
Location: include/linux/uidgid.h:101
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff81160c39)
Location: include/linux/uidgid.h:101
Inline: True
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8116d2db)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8117917b)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8118c1bb)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff811893db)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff8118a248)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff811b2d08)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff811e50fa)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff8122b13a)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff8124171a)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
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
In kernel/auditfilter.c (ffffffff8125b54a)
Location: include/linux/uidgid.h:93
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:93
Inline: True
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
In kernel/auditfilter.c (ffff8000101ee3c4)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (c042e454)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (c000000000260f90)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffe000162556)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8117179b)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8116493b)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8116f56b)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
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
In kernel/auditfilter.c (ffffffff8117cd5b)
Location: include/linux/uidgid.h:101
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_uid_comparator
```
```
In net/core/fib_rules.c (0)
Location: include/linux/uidgid.h:101
Inline: True
```
</details>
</li>
</ul>

## Differences
