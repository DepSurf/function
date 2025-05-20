# Function: <code>tomoyo_sys_getppid</code>

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
In security/tomoyo/audit.c (ffffffff81366caa)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff8136c6cf)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8139cd4a)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813a28ff)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff813b392a)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813b947f)
Location: security/tomoyo/common.h:1120
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff813ca2f1)
Location: security/tomoyo/common.h:1122
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813cfd48)
Location: security/tomoyo/common.h:1122
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff813f0791)
Location: security/tomoyo/common.h:1124
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813f692d)
Location: security/tomoyo/common.h:1124
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff814216a0)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff81427928)
Location: security/tomoyo/common.h:1121
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8143dd20)
Location: security/tomoyo/common.h:1124
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff814442b0)
Location: security/tomoyo/common.h:1124
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8146b8b3)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81471bda)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff81485693)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8148b97a)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff814db863)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff814e2d0a)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff814f8cd3)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815000c9)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff814ffa63)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81506e49)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8155aad7)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81563e1a)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff815f5895)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815ff2fe)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff816a6395)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816b019e)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff816ded75)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816e8651)
Location: security/tomoyo/common.h:1133
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8171b985)
Location: security/tomoyo/common.h:1131
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81725361)
Location: security/tomoyo/common.h:1131
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffff800010577b60)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffff80001057edc4)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (c072a9b0)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c0731708)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (c0000000006e1310)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c0000000006ebf30)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffe0003ca010)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffe0003cfebc)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8147dc73)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81483f5a)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff8146e693)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8147497a)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff81479d13)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8147fffa)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/audit.c (ffffffff814917c3)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81497b2d)
Location: security/tomoyo/common.h:1134
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
</details>
</li>
</ul>

## Differences
