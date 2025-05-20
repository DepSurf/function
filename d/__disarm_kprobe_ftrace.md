# Function: <code>__disarm_kprobe_ftrace</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811824e4)
Location: kernel/kprobes.c:1049
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __disarm_kprobe_ftrace(struct kprobe *p, struct ftrace_ops *ops, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81195020)
Location: kernel/kprobes.c:1054
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81195020-ffffffff811950bd: __disarm_kprobe_ftrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __disarm_kprobe_ftrace(struct kprobe *p, struct ftrace_ops *ops, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81191e80)
Location: kernel/kprobes.c:1077
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81191e80-ffffffff81191f1d: __disarm_kprobe_ftrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __disarm_kprobe_ftrace(struct kprobe *p, struct ftrace_ops *ops, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192d50)
Location: kernel/kprobes.c:1078
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81192d50-ffffffff81192ded: __disarm_kprobe_ftrace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __disarm_kprobe_ftrace(struct kprobe *p, struct ftrace_ops *ops, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1088
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811bbe80-ffffffff811bbf29: __disarm_kprobe_ftrace (STB_LOCAL)
ffffffff81cb3731-ffffffff81cb374b: __disarm_kprobe_ftrace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __disarm_kprobe_ftrace(struct kprobe *p, struct ftrace_ops *ops, int *cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1113
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811ef4f0-ffffffff811ef5a5: __disarm_kprobe_ftrace (STB_LOCAL)
ffffffff81e64518-ffffffff81e64532: __disarm_kprobe_ftrace.cold (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff81235eb0)
Location: kernel/kprobes.c:1110
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe_ftrace
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
In kernel/kprobes.c (ffffffff8124ccd0)
Location: kernel/kprobes.c:1110
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe_ftrace
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
In kernel/kprobes.c (ffffffff81266bd0)
Location: kernel/kprobes.c:1110
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe_ftrace
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026e3e4)
Location: kernel/kprobes.c:1049
Inline: True
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/kprobes.c (ffffffff8117ab04)
Location: kernel/kprobes.c:1049
Inline: True
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
In kernel/kprobes.c (ffffffff8116dca4)
Location: kernel/kprobes.c:1049
Inline: True
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
In kernel/kprobes.c (ffffffff811788d4)
Location: kernel/kprobes.c:1049
Inline: True
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
In kernel/kprobes.c (ffffffff811861a4)
Location: kernel/kprobes.c:1049
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
