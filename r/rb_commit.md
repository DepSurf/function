# Function: <code>rb_commit</code>

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
In kernel/trace/ring_buffer.c (ffffffff81148bff)
Location: kernel/trace/ring_buffer.c:2537
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
  - kernel/trace/ring_buffer.c:ring_buffer_write
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
In kernel/trace/ring_buffer.c (ffffffff81152459)
Location: kernel/trace/ring_buffer.c:2531
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81158cf0)
Location: kernel/trace/ring_buffer.c:2500
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81158cf0-ffffffff81158f4d: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8115cd20)
Location: kernel/trace/ring_buffer.c:2502
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8115cd20-ffffffff8115cf3a: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81169cc0)
Location: kernel/trace/ring_buffer.c:2498
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81169cc0-ffffffff81169eda: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81178c20)
Location: kernel/trace/ring_buffer.c:2577
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81178c20-ffffffff81178e32: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811860e0)
Location: kernel/trace/ring_buffer.c:2625
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811860e0-ffffffff81186305: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81193470)
Location: kernel/trace/ring_buffer.c:2602
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81193470-ffffffff811936e8: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119f0a0)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8119f0a0-ffffffff8119f2c0: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b4fb0)
Location: kernel/trace/ring_buffer.c:2672
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811b4fb0-ffffffff811b51d3: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b27c0)
Location: kernel/trace/ring_buffer.c:2965
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811b27c0-ffffffff811b2923: rb_commit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b31a0)
Location: kernel/trace/ring_buffer.c:3048
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811b31a0-ffffffff811b3306: rb_commit.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811dfa4d)
Location: kernel/trace/ring_buffer.c:3048
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811dd080-ffffffff811dd1c2: rb_commit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81216d84)
Location: kernel/trace/ring_buffer.c:3091
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff812136f0-ffffffff8121384a: rb_commit.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8125cef0)
Location: kernel/trace/ring_buffer.c:3179
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8125cef0-ffffffff8125d04a: rb_commit.part.0 (STB_LOCAL)
ffffffff8125d060-ffffffff8125d099: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81274100)
Location: kernel/trace/ring_buffer.c:3183
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81274100-ffffffff81274260: rb_commit.part.0 (STB_LOCAL)
ffffffff81274270-ffffffff812742a9: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128e750)
Location: kernel/trace/ring_buffer.c:3003
Inline: True
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8128e750-ffffffff8128e8b0: rb_commit.part.0 (STB_LOCAL)
ffffffff8128e8c0-ffffffff8128e8f9: rb_commit (STB_LOCAL)
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
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021a7c8)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffff80001021a7c8-ffff80001021aaa8: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0457754)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
c0457754-c0457aac: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c00000000029b370)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
c00000000029b370-c00000000029b6a8: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe000177950)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffe000177950-ffffffe000177ad2: rb_commit (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811976c0)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811976c0-ffffffff811978e0: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118ab20)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff8118ab20-ffffffff8118ad40: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81195490)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff81195490-ffffffff811956b0: rb_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rb_commit(struct ring_buffer_per_cpu *cpu_buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a3320)
Location: kernel/trace/ring_buffer.c:2603
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_write
  - kernel/trace/ring_buffer.c:ring_buffer_unlock_commit
```
**Symbols:**

```
ffffffff811a3320-ffffffff811a3540: rb_commit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
