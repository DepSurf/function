# Function: <code>disarm_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112da90)
Location: kernel/kprobes.c:985
Inline: False
Direct callers:
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:write_enabled_file_bool
```
**Symbols:**

```
ffffffff8112da90-ffffffff8112db84: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81135d00)
Location: kernel/kprobes.c:985
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81135d00-ffffffff81135df7: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8113fa80)
Location: kernel/kprobes.c:985
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8113fa80-ffffffff8113fb77: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140f10)
Location: kernel/kprobes.c:1028
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81140f10-ffffffff81140ffe: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ddb0)
Location: kernel/kprobes.c:1030
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8114ddb0-ffffffff8114de9e: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115c950)
Location: kernel/kprobes.c:1053
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8115c950-ffffffff8115ca7c: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81169660)
Location: kernel/kprobes.c:1068
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81169660-ffffffff81169786: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81176510)
Location: kernel/kprobes.c:1053
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81176510-ffffffff81176636: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182430)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81182430-ffffffff8118257b: disarm_kprobe (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff811970c8)
Location: kernel/kprobes.c:1114
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
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
In kernel/kprobes.c (ffffffff81194248)
Location: kernel/kprobes.c:1137
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_all_kprobes
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
In kernel/kprobes.c (ffffffff811952c4)
Location: kernel/kprobes.c:1138
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff811be1b4)
Location: kernel/kprobes.c:1148
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
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
In kernel/kprobes.c (ffffffff811f15a7)
Location: kernel/kprobes.c:1177
Inline: True
Inline callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1174
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81237340-ffffffff8123740d: disarm_kprobe (STB_LOCAL)
ffffffff8205c71a-ffffffff8205c72f: disarm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1174
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8124e400-ffffffff8124e4cd: disarm_kprobe (STB_LOCAL)
ffffffff820db06f-ffffffff820db084: disarm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1174
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81268330-ffffffff812683fd: disarm_kprobe (STB_LOCAL)
ffffffff821b6dc5-ffffffff821b6dda: disarm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f70b0)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffff8000101f70b0-ffff8000101f712c: disarm_kprobe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0437ad4)
Location: kernel/kprobes.c:1098
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
c0437ad4-c0437b98: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026e2c0)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
c00000000026e2c0-c00000000026e4cc: disarm_kprobe (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117aa50)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8117aa50-ffffffff8117ab9b: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116dbf0)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff8116dbf0-ffffffff8116dd3b: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81178820)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81178820-ffffffff8117896b: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int disarm_kprobe(struct kprobe *kp, bool reopt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811860f0)
Location: kernel/kprobes.c:1098
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811860f0-ffffffff8118623b: disarm_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
