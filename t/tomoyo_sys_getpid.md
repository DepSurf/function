# Function: <code>tomoyo_sys_getpid</code>

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
In security/tomoyo/audit.c (ffffffff81366cc7)
Location: security/tomoyo/common.h:1137
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff8136c6dd)
Location: security/tomoyo/common.h:1137
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
In security/tomoyo/audit.c (ffffffff8139cd67)
Location: security/tomoyo/common.h:1137
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813a290d)
Location: security/tomoyo/common.h:1137
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
In security/tomoyo/audit.c (ffffffff813b3947)
Location: security/tomoyo/common.h:1137
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813b948d)
Location: security/tomoyo/common.h:1137
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
In security/tomoyo/audit.c (ffffffff813ca307)
Location: security/tomoyo/common.h:1139
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813cfd5b)
Location: security/tomoyo/common.h:1139
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
In security/tomoyo/audit.c (ffffffff813f07a7)
Location: security/tomoyo/common.h:1141
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff813f6924)
Location: security/tomoyo/common.h:1141
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
In security/tomoyo/audit.c (ffffffff814216b2)
Location: security/tomoyo/common.h:1138
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff81427967)
Location: security/tomoyo/common.h:1138
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
In security/tomoyo/audit.c (ffffffff8143dd32)
Location: security/tomoyo/common.h:1141
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/tomoyo/condition.c (ffffffff81443faf)
Location: security/tomoyo/common.h:1141
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
In security/tomoyo/audit.c (ffffffff8146b8cd)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8147205f)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff814856ad)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8148bdff)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff814db87d)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff814e2fd6)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff814f8cf2)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815003e1)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff814ffa82)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8150702c)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff8155aaf3)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81564072)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff815f58b5)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff815ff266)
Location: security/tomoyo/common.h:1151
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
In security/tomoyo/audit.c (ffffffff816a63b5)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816b0106)
Location: security/tomoyo/common.h:1151
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
In security/tomoyo/audit.c (ffffffff816ded95)
Location: security/tomoyo/common.h:1151
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff816e89a0)
Location: security/tomoyo/common.h:1151
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
In security/tomoyo/audit.c (ffffffff8171b9a6)
Location: security/tomoyo/common.h:1149
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff817256b0)
Location: security/tomoyo/common.h:1149
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
In security/tomoyo/audit.c (ffff800010577b58)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffff80001057ed98)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (c072a994)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c0731724)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (c0000000006e1304)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (c0000000006ebf18)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffe0003ca000)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffe0003cfed6)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff8147dc8d)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff814843df)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff8146e6ad)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81474dff)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff81479d2d)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff8148047f)
Location: security/tomoyo/common.h:1152
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
In security/tomoyo/audit.c (ffffffff814917e7)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/tomoyo/condition.c (ffffffff81497fea)
Location: security/tomoyo/common.h:1152
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
</details>
</li>
</ul>

## Differences
