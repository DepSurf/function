# Function: <code>register_trace_kprobe</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811693b4)
Location: kernel/trace/trace_kprobe.c:506
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff81176a3a)
Location: kernel/trace/trace_kprobe.c:510
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811824e7)
Location: kernel/trace/trace_kprobe.c:525
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff8118542a)
Location: kernel/trace/trace_kprobe.c:531
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff81193118)
Location: kernel/trace/trace_kprobe.c:531
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811a845b)
Location: kernel/trace/trace_kprobe.c:572
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811b5735)
Location: kernel/trace/trace_kprobe.c:492
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
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
In kernel/trace/trace_kprobe.c (ffffffff811c44f2)
Location: kernel/trace/trace_kprobe.c:455
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811cf930-ffffffff811cfd06: register_trace_kprobe (STB_LOCAL)
ffffffff811d1df0-ffffffff811d1e28: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:625
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811edb80-ffffffff811edd80: register_trace_kprobe (STB_LOCAL)
ffffffff811ee812-ffffffff811ee839: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:627
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811ebcf0-ffffffff811ebef0: register_trace_kprobe (STB_LOCAL)
ffffffff81be6434-ffffffff81be645b: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:627
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff811eb460-ffffffff811eb609: register_trace_kprobe (STB_LOCAL)
ffffffff81bd811c-ffffffff81bd8143: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:627
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff8121c2c0-ffffffff8121c499: register_trace_kprobe (STB_LOCAL)
ffffffff81cb72dd-ffffffff81cb7304: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:623
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff8125cd40-ffffffff8125cf54: register_trace_kprobe (STB_LOCAL)
ffffffff81e68687-ffffffff81e686ae: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812abcf0)
Location: kernel/trace/trace_kprobe.c:625
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812abcf0-ffffffff812abf22: register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ce4f0)
Location: kernel/trace/trace_kprobe.c:625
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812ce4f0-ffffffff812ce722: register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ebef0)
Location: kernel/trace/trace_kprobe.c:625
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812ebef0-ffffffff812ec122: register_trace_kprobe (STB_LOCAL)
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
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010250168)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffff800010250168-ffff80001025057c: register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0483bf8)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
c0483bf8-c0483f90: register_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ede50)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
c0000000002ede50-c0000000002ee674: register_trace_kprobe (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c7f50-ffffffff811c8326: register_trace_kprobe (STB_LOCAL)
ffffffff811ca410-ffffffff811ca448: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811bad30-ffffffff811bb106: register_trace_kprobe (STB_LOCAL)
ffffffff811bd1e0-ffffffff811bd218: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c5d20-ffffffff811c60f6: register_trace_kprobe (STB_LOCAL)
ffffffff811c81e0-ffffffff811c8218: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int register_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:626
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811d3f80-ffffffff811d4356: register_trace_kprobe (STB_LOCAL)
ffffffff811d6440-ffffffff811d6478: register_trace_kprobe.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
