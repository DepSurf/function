# Function: <code>cgroup_threadgroup_change_end</code>

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
In kernel/fork.c (ffffffff8107ebfe)
Location: include/linux/cgroup-defs.h:519
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109089b)
Location: include/linux/cgroup-defs.h:519
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812135c8)
Location: include/linux/cgroup-defs.h:519
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
In kernel/fork.c (ffffffff81081635)
Location: include/linux/cgroup-defs.h:542
Inline: True
```
```
In kernel/signal.c (ffffffff8109393e)
Location: include/linux/cgroup-defs.h:542
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8123a12c)
Location: include/linux/cgroup-defs.h:542
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
In kernel/fork.c (ffffffff81085d0b)
Location: include/linux/cgroup-defs.h:546
Inline: True
```
```
In kernel/signal.c (ffffffff810988df)
Location: include/linux/cgroup-defs.h:546
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8124ce77)
Location: include/linux/cgroup-defs.h:546
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
In kernel/fork.c (ffffffff81082721)
Location: include/linux/cgroup-defs.h:565
Inline: True
```
```
In kernel/signal.c (ffffffff81095b7a)
Location: include/linux/cgroup-defs.h:565
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff81258e92)
Location: include/linux/cgroup-defs.h:565
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
In kernel/fork.c (ffffffff81089522)
Location: include/linux/cgroup-defs.h:685
Inline: True
```
```
In kernel/signal.c (ffffffff8109c9ca)
Location: include/linux/cgroup-defs.h:685
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff8127b028)
Location: include/linux/cgroup-defs.h:685
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff8108ad30)
Location: include/linux/cgroup-defs.h:697
Inline: True
```
```
In kernel/signal.c (ffffffff810a0dca)
Location: include/linux/cgroup-defs.h:697
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812a270c)
Location: include/linux/cgroup-defs.h:697
Inline: True
```
**Symbols:**

```
ffffffff8108ad30-ffffffff8108ad58: cgroup_threadgroup_change_end.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81092d30)
Location: include/linux/cgroup-defs.h:706
Inline: True
```
```
In kernel/signal.c (ffffffff810a920a)
Location: include/linux/cgroup-defs.h:706
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812b72fb)
Location: include/linux/cgroup-defs.h:706
Inline: True
```
**Symbols:**

```
ffffffff81092d30-ffffffff81092d58: cgroup_threadgroup_change_end.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81096d30)
Location: include/linux/cgroup-defs.h:749
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ad5d0)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812d4cf2)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81096d30-ffffffff81096d57: cgroup_threadgroup_change_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff8109d560)
Location: include/linux/cgroup-defs.h:749
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b3bf0)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812e6872)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff8109d560-ffffffff8109d587: cgroup_threadgroup_change_end.isra.0 (STB_LOCAL)
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
In kernel/signal.c (ffffffff810bc6a6)
Location: include/linux/cgroup-defs.h:742
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81177ec4)
Location: include/linux/cgroup-defs.h:742
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8131e111)
Location: include/linux/cgroup-defs.h:742
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810b7996)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81174be4)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff81329621)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810b8ef6)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811757a0)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8132f431)
Location: include/linux/cgroup-defs.h:727
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810cb486)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8119cd30)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff8137cc11)
Location: include/linux/cgroup-defs.h:731
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff810e4ae2)
Location: include/linux/cgroup-defs.h:732
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff811cd03a)
Location: include/linux/cgroup-defs.h:732
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff813fbf55)
Location: include/linux/cgroup-defs.h:732
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff81105132)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff812105fb)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff81485005)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff811113ba)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff8121ee1b)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff814b9f85)
Location: include/linux/cgroup-defs.h:760
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/signal.c (ffffffff8111ad4e)
Location: include/linux/cgroup-defs.h:796
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In kernel/cgroup/cgroup.c (ffffffff81236aab)
Location: include/linux/cgroup-defs.h:796
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_css_set_put_fork
  - kernel/cgroup/cgroup.c:cgroup_css_set_fork
```
```
In fs/exec.c (ffffffff814ec501)
Location: include/linux/cgroup-defs.h:796
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffff8000100f41bc)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff80001010fc08)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffff80001038eb2c)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/fork.c (c0352c9c)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c036798c)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (c05750a0)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/fork.c (c00000000013a608)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c000000000157220)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (c000000000485a94)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
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
In kernel/fork.c (ffffffe0000c0978)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000cff72)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffe00025e41e)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81096e80)
Location: include/linux/cgroup-defs.h:749
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810adf60)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812dee52)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81096e80-ffffffff81096ea7: cgroup_threadgroup_change_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81085900)
Location: include/linux/cgroup-defs.h:749
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109c8c0)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812cef71)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81085900-ffffffff81085927: cgroup_threadgroup_change_end.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/fork.c (ffffffff81096e30)
Location: include/linux/cgroup-defs.h:749
Inline: True
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810ad4c0)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812dcc62)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
**Symbols:**

```
ffffffff81096e30-ffffffff81096e57: cgroup_threadgroup_change_end.isra.0 (STB_LOCAL)
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
In kernel/fork.c (ffffffff810a115f)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b568d)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - kernel/signal.c:exit_signals
  - kernel/signal.c:exit_signals
```
```
In fs/exec.c (ffffffff812eda09)
Location: include/linux/cgroup-defs.h:749
Inline: True
Inline callers:
  - fs/exec.c:de_thread
  - fs/exec.c:de_thread
```
</details>
</li>
</ul>

## Differences
