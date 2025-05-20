# Function: <code>rb_reset_cpu</code>

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
In kernel/trace/ring_buffer.c (ffffffff81146bfd)
Location: kernel/trace/ring_buffer.c:4175
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff8114f449)
Location: kernel/trace/ring_buffer.c:4170
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff811595dc)
Location: kernel/trace/ring_buffer.c:4139
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff8115c49d)
Location: kernel/trace/ring_buffer.c:4153
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff81169446)
Location: kernel/trace/ring_buffer.c:4145
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff811783c6)
Location: kernel/trace/ring_buffer.c:4307
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff81185854)
Location: kernel/trace/ring_buffer.c:4372
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff81192b94)
Location: kernel/trace/ring_buffer.c:4350
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff8119e814)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_reset_cpu(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b51e0)
Location: kernel/trace/ring_buffer.c:4442
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
**Symbols:**

```
ffffffff811b51e0-ffffffff811b536a: rb_reset_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rb_reset_cpu(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b2ab0)
Location: kernel/trace/ring_buffer.c:4988
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
```
**Symbols:**

```
ffffffff811b2ab0-ffffffff811b2c3a: rb_reset_cpu (STB_LOCAL)
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
In kernel/trace/ring_buffer.c (ffffffff811b5e33)
Location: kernel/trace/ring_buffer.c:5095
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
In kernel/trace/ring_buffer.c (ffffffff811e0003)
Location: kernel/trace/ring_buffer.c:5095
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
In kernel/trace/ring_buffer.c (ffffffff812171f1)
Location: kernel/trace/ring_buffer.c:5137
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
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
In kernel/trace/ring_buffer.c (ffffffff81260611)
Location: kernel/trace/ring_buffer.c:5243
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rb_reset_cpu(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81273ee0)
Location: kernel/trace/ring_buffer.c:5258
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
```
**Symbols:**

```
ffffffff81273ee0-ffffffff812740e6: rb_reset_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rb_reset_cpu(struct ring_buffer_per_cpu *cpu_buffer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8128f3c0)
Location: kernel/trace/ring_buffer.c:5175
Inline: False
Direct callers:
  - kernel/trace/ring_buffer.c:reset_disabled_cpu_buffer
```
**Symbols:**

```
ffffffff8128f3c0-ffffffff8128f5c6: rb_reset_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021a53c)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0456a38)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (c000000000299fcc)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffe0001770a6)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff81196e34)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff8118a114)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff81194c04)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
In kernel/trace/ring_buffer.c (ffffffff811a2814)
Location: kernel/trace/ring_buffer.c:4351
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_reset_cpu
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
