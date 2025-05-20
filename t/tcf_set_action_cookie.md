# Function: <code>tcf_set_action_cookie</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81902eea)
Location: net/sched/act_api.c:64
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff819640ec)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff8199abba)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81a73e53)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffffffff81a7cb74)
Location: net/sched/act_api.c:57
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81a65882)
Location: net/sched/act_api.c:57
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81b1ea14)
Location: net/sched/act_api.c:57
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81ca64ad)
Location: net/sched/act_api.c:59
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81e6298d)
Location: net/sched/act_api.c:60
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81ebea1d)
Location: net/sched/act_api.c:60
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff81f81bc6)
Location: net/sched/act_api.c:60
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tcf_set_action_cookie(struct tc_cookie **old_cookie, struct tc_cookie *new_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (ffff800010c46700)
Location: net/sched/act_api.c:41
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
ffff800010c46700-ffff800010c4675c: tcf_set_action_cookie (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcf_set_action_cookie(struct tc_cookie **old_cookie, struct tc_cookie *new_cookie);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sched/act_api.c (c0d58148)
Location: net/sched/act_api.c:41
Inline: False
Direct callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
**Symbols:**

```
c0d58148-c0d58194: tcf_set_action_cookie (STB_LOCAL)
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
In net/sched/act_api.c (c000000000d44f08)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffe0007b5914)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff8193aa2a)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff818f452a)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff8198bbba)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
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
In net/sched/act_api.c (ffffffff819ae42a)
Location: net/sched/act_api.c:41
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
  - net/sched/act_api.c:tcf_action_cleanup
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
