# Function: <code>cgroup_task_frozen</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae937)
Location: include/linux/cgroup.h:920
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff8115abcc)
Location: include/linux/cgroup.h:920
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810b4f47)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff8116687c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810bde22)
Location: include/linux/cgroup.h:924
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81177a3f)
Location: include/linux/cgroup.h:924
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810b913d)
Location: include/linux/cgroup.h:923
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8117472f)
Location: include/linux/cgroup.h:923
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810ba651)
Location: include/linux/cgroup.h:923
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff811752e9)
Location: include/linux/cgroup.h:923
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810ccede)
Location: include/linux/cgroup.h:902
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8119c81b)
Location: include/linux/cgroup.h:902
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810e4efe)
Location: include/linux/cgroup.h:899
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff811ccaf0)
Location: include/linux/cgroup.h:899
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff8110556b)
Location: include/linux/cgroup.h:826
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81210080)
Location: include/linux/cgroup.h:826
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff811117f8)
Location: include/linux/cgroup.h:824
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81225a7b)
Location: include/linux/cgroup.h:824
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff8111b198)
Location: include/linux/cgroup.h:822
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff8123d70b)
Location: include/linux/cgroup.h:822
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffff8000101110d4)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffff8000101d8604)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (c03688f0)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (c041b25c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (c000000000158a30)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (c000000000245738)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffe0000d0ad2)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:recalc_sigpending_and_wake
```
```
In kernel/cgroup/cgroup.c (ffffffe0001515f8)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810af2b7)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff8115ee9c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff8109dc01)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff8115212c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810ae817)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff8115cc6c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
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
In kernel/signal.c (ffffffff810b6a6d)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:recalc_sigpending_tsk
```
```
In kernel/cgroup/cgroup.c (ffffffff81169d7c)
Location: include/linux/cgroup.h:922
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
```
</details>
</li>
</ul>

## Differences
