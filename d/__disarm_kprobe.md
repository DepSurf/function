# Function: <code>__disarm_kprobe</code>

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
In kernel/kprobes.c (ffffffff8112dab4)
Location: kernel/kprobes.c:868
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
In kernel/kprobes.c (ffffffff81135d24)
Location: kernel/kprobes.c:868
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
In kernel/kprobes.c (ffffffff8113faa4)
Location: kernel/kprobes.c:868
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
In kernel/kprobes.c (ffffffff81140f39)
Location: kernel/kprobes.c:914
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
In kernel/kprobes.c (ffffffff8114ddd9)
Location: kernel/kprobes.c:916
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
In kernel/kprobes.c (ffffffff8115c97f)
Location: kernel/kprobes.c:914
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
In kernel/kprobes.c (ffffffff8116968f)
Location: kernel/kprobes.c:924
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
In kernel/kprobes.c (ffffffff8117653f)
Location: kernel/kprobes.c:909
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
In kernel/kprobes.c (ffffffff81182461)
Location: kernel/kprobes.c:930
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __disarm_kprobe(struct kprobe *p, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811965e0)
Location: kernel/kprobes.c:935
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811965e0-ffffffff81196644: __disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __disarm_kprobe(struct kprobe *p, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193370)
Location: kernel/kprobes.c:958
Inline: False
Direct callers:
  - kernel/kprobes.c:disarm_all_kprobes
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81193370-ffffffff811933d4: __disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __disarm_kprobe(struct kprobe *p, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194320)
Location: kernel/kprobes.c:959
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff81194320-ffffffff8119438a: __disarm_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __disarm_kprobe(struct kprobe *p, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:969
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811bd1a0-ffffffff811bd224: __disarm_kprobe (STB_LOCAL)
ffffffff81cb37f6-ffffffff81cb380b: __disarm_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __disarm_kprobe(struct kprobe *p, bool reopt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:1001
Inline: False
Direct callers:
  - kernel/kprobes.c:write_enabled_file_bool
  - kernel/kprobes.c:__disable_kprobe
```
**Symbols:**

```
ffffffff811f0450-ffffffff811f04ec: __disarm_kprobe (STB_LOCAL)
ffffffff81e645e6-ffffffff81e645fb: __disarm_kprobe.cold (STB_LOCAL)
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
In kernel/kprobes.c (ffffffff8123736f)
Location: kernel/kprobes.c:998
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff8124e42f)
Location: kernel/kprobes.c:998
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (ffffffff8126835f)
Location: kernel/kprobes.c:998
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c0437b0c)
Location: kernel/kprobes.c:930
Inline: True
Inline callers:
  - kernel/kprobes.c:disarm_kprobe
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
In kernel/kprobes.c (c00000000026e320)
Location: kernel/kprobes.c:930
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
In kernel/kprobes.c (ffffffff8117aa81)
Location: kernel/kprobes.c:930
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
In kernel/kprobes.c (ffffffff8116dc21)
Location: kernel/kprobes.c:930
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
In kernel/kprobes.c (ffffffff81178851)
Location: kernel/kprobes.c:930
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
In kernel/kprobes.c (ffffffff81186121)
Location: kernel/kprobes.c:930
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
