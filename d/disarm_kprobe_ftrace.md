# Function: <code>disarm_kprobe_ftrace</code>

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
In kernel/kprobes.c (ffffffff8112db13)
Location: kernel/kprobes.c:948
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff81135d86)
Location: kernel/kprobes.c:948
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8113fb06)
Location: kernel/kprobes.c:948
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140f98)
Location: kernel/kprobes.c:994
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff8114de38)
Location: kernel/kprobes.c:996
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff8115c9e7)
Location: kernel/kprobes.c:1013
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff811696f1)
Location: kernel/kprobes.c:1028
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff811765a1)
Location: kernel/kprobes.c:1013
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff811824c5)
Location: kernel/kprobes.c:1068
Inline: True
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
In kernel/kprobes.c (ffffffff811970fe)
Location: kernel/kprobes.c:1073
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
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
In kernel/kprobes.c (ffffffff8119427e)
Location: kernel/kprobes.c:1096
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
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
In kernel/kprobes.c (ffffffff811952fa)
Location: kernel/kprobes.c:1097
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
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
In kernel/kprobes.c (ffffffff811be1ea)
Location: kernel/kprobes.c:1107
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
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
In kernel/kprobes.c (ffffffff811f167a)
Location: kernel/kprobes.c:1134
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:__disable_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe_ftrace(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1131
Inline: False
Direct callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:disarm_kprobe
```
**Symbols:**

```
ffffffff81235e80-ffffffff81235f60: disarm_kprobe_ftrace (STB_LOCAL)
ffffffff8205c621-ffffffff8205c63c: disarm_kprobe_ftrace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe_ftrace(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1131
Inline: False
Direct callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:disarm_kprobe
```
**Symbols:**

```
ffffffff8124cca0-ffffffff8124cd80: disarm_kprobe_ftrace (STB_LOCAL)
ffffffff820daf7e-ffffffff820daf99: disarm_kprobe_ftrace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe_ftrace(struct kprobe *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1131
Inline: False
Direct callers:
  - kernel/kprobes.c:kill_kprobe
  - kernel/kprobes.c:disarm_kprobe
```
**Symbols:**

```
ffffffff81266ba0-ffffffff81266c80: disarm_kprobe_ftrace (STB_LOCAL)
ffffffff821b6cd4-ffffffff821b6cef: disarm_kprobe_ftrace.cold (STB_LOCAL)
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
In kernel/kprobes.c (c00000000026e3c0)
Location: kernel/kprobes.c:1068
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
In kernel/kprobes.c (ffffffff8117aae5)
Location: kernel/kprobes.c:1068
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
In kernel/kprobes.c (ffffffff8116dc85)
Location: kernel/kprobes.c:1068
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
In kernel/kprobes.c (ffffffff811788b5)
Location: kernel/kprobes.c:1068
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
In kernel/kprobes.c (ffffffff81186185)
Location: kernel/kprobes.c:1068
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
