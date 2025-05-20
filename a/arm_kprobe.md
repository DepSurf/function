# Function: <code>arm_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112d930)
Location: kernel/kprobes.c:968
Inline: False
Direct callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:write_enabled_file_bool
```
**Symbols:**

```
ffffffff8112d930-ffffffff8112da07: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81135b90)
Location: kernel/kprobes.c:968
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81135b90-ffffffff81135c67: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8113f910)
Location: kernel/kprobes.c:968
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff8113f910-ffffffff8113f9e7: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140db0)
Location: kernel/kprobes.c:1014
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81140db0-ffffffff81140e7c: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114dc50)
Location: kernel/kprobes.c:1016
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff8114dc50-ffffffff8114dd1c: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115c790)
Location: kernel/kprobes.c:1038
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff8115c790-ffffffff8115c8ae: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811694a0)
Location: kernel/kprobes.c:1053
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff811694a0-ffffffff811695be: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81176340)
Location: kernel/kprobes.c:1038
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81176340-ffffffff81176462: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182240)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81182240-ffffffff81182381: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81196210)
Location: kernel/kprobes.c:1099
Inline: False
Direct callers:
  - kernel/kprobes.c:arm_all_kprobes
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff81196210-ffffffff811962bd: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81192fa0)
Location: kernel/kprobes.c:1122
Inline: False
Direct callers:
  - kernel/kprobes.c:arm_all_kprobes
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff81192fa0-ffffffff8119304d: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193f20)
Location: kernel/kprobes.c:1123
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff81193f20-ffffffff81194064: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bcdd0)
Location: kernel/kprobes.c:1133
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff811bcdd0-ffffffff811bcf0b: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1163
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff811f02f0-ffffffff811f0445: arm_kprobe (STB_LOCAL)
ffffffff81e645c9-ffffffff81e645e6: arm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1160
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff81236e50-ffffffff81236fa5: arm_kprobe (STB_LOCAL)
ffffffff8205c6d3-ffffffff8205c6f0: arm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1160
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff8124df10-ffffffff8124e062: arm_kprobe (STB_LOCAL)
ffffffff820db030-ffffffff820db045: arm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1160
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_aggr_kprobe
```
**Symbols:**

```
ffffffff81267e40-ffffffff81267f92: arm_kprobe (STB_LOCAL)
ffffffff821b6d86-ffffffff821b6d9b: arm_kprobe.cold (STB_LOCAL)
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
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f6998)
Location: kernel/kprobes.c:1083
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffff8000101f6998-ffff8000101f6a14: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c04379a8)
Location: kernel/kprobes.c:1083
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
c04379a8-c0437a2c: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026df90)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
c00000000026df90-c00000000026e184: arm_kprobe (STB_LOCAL)
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
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117a860)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff8117a860-ffffffff8117a9a1: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116da00)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff8116da00-ffffffff8116db41: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81178630)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81178630-ffffffff81178771: arm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int arm_kprobe(struct kprobe *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81185f00)
Location: kernel/kprobes.c:1083
Inline: True
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:enable_kprobe
```
**Symbols:**

```
ffffffff81185f00-ffffffff81186041: arm_kprobe (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
