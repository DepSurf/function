# Function: <code>audit_loginuid_set</code>

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
In kernel/auditfilter.c (0)
Location: include/linux/audit.h:444
Inline: True
```
```
In kernel/auditsc.c (0)
Location: include/linux/audit.h:444
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
In kernel/auditfilter.c (ffffffff8112d778)
Location: include/linux/audit.h:547
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8112f2e4)
Location: include/linux/audit.h:547
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
In kernel/auditfilter.c (ffffffff811374a8)
Location: include/linux/audit.h:547
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81138fa5)
Location: include/linux/audit.h:547
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
In kernel/auditfilter.c (ffffffff81138a08)
Location: include/linux/audit.h:577
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8113a5d0)
Location: include/linux/audit.h:577
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
In kernel/auditfilter.c (ffffffff811456f2)
Location: include/linux/audit.h:579
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811472a0)
Location: include/linux/audit.h:579
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
In kernel/auditfilter.c (ffffffff81154093)
Location: include/linux/audit.h:590
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81157a44)
Location: include/linux/audit.h:590
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/auditfilter.c (ffffffff81160f68)
Location: include/linux/audit.h:589
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81164a42)
Location: include/linux/audit.h:589
Inline: True
Inline callers:
  - kernel/auditsc.c:audit_set_loginuid
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
In kernel/audit.c (ffffffff8116b4b2)
Location: include/linux/audit.h:659
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8116d622)
Location: include/linux/audit.h:659
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81170242)
Location: include/linux/audit.h:659
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
In kernel/audit.c (ffffffff81177392)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff811794c2)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117c0c2)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffff8118a0fb)
Location: include/linux/audit.h:688
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118c53c)
Location: include/linux/audit.h:688
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118e789)
Location: include/linux/audit.h:688
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
In kernel/audit.c (ffffffff8118740b)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118975a)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118b95c)
Location: include/linux/audit.h:697
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
In kernel/audit.c (ffffffff81188344)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8118a5b1)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118c80d)
Location: include/linux/audit.h:697
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
In kernel/audit.c (ffffffff811b0864)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff811b30ac)
Location: include/linux/audit.h:697
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811b5455)
Location: include/linux/audit.h:697
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
In kernel/audit.c (ffffffff811e2a41)
Location: include/linux/audit.h:738
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff811e54de)
Location: include/linux/audit.h:738
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811e7afe)
Location: include/linux/audit.h:738
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
In kernel/audit.c (ffffffff81228921)
Location: include/linux/audit.h:731
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8122b55e)
Location: include/linux/audit.h:731
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8122dc5e)
Location: include/linux/audit.h:731
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
In kernel/audit.c (ffffffff8123ef21)
Location: include/linux/audit.h:730
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff81241b96)
Location: include/linux/audit.h:730
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81243f73)
Location: include/linux/audit.h:730
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
In kernel/audit.c (ffffffff81258d92)
Location: include/linux/audit.h:729
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8125b9ae)
Location: include/linux/audit.h:729
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8125dec4)
Location: include/linux/audit.h:729
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
In kernel/audit.c (ffff8000101ec33c)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffff8000101ee7fc)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffff8000101f03f4)
Location: include/linux/audit.h:652
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
In kernel/audit.c (0)
Location: include/linux/audit.h:652
Inline: True
```
```
In kernel/auditfilter.c (c042e754)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c04315d0)
Location: include/linux/audit.h:652
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
In kernel/audit.c (c00000000025dd0c)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (c000000000261480)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (c00000000026370c)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffe000160a68)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffe000162828)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffe000163ffc)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffff8116f9b2)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff81171ae2)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811746e2)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffff81162b52)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff81164c82)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff81167882)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffff8116d782)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8116f8b2)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811724b2)
Location: include/linux/audit.h:652
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
In kernel/audit.c (ffffffff8117af72)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/audit.c:audit_set_loginuid
```
```
In kernel/auditfilter.c (ffffffff8117d0b7)
Location: include/linux/audit.h:652
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8117fdb2)
Location: include/linux/audit.h:652
Inline: True
```
</details>
</li>
</ul>

## Differences
