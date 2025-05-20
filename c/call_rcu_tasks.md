# Function: <code>call_rcu_tasks</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9790)
Location: kernel/rcu/update.c:537
Inline: True
```
**Symbols:**

```
ffffffff810e9790-ffffffff810e98a0: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0640)
Location: kernel/rcu/update.c:540
Inline: True
```
**Symbols:**

```
ffffffff810f0640-ffffffff810f0750: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0620)
Location: kernel/rcu/update.c:599
Inline: True
```
**Symbols:**

```
ffffffff810f0620-ffffffff810f0730: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810fa2f0)
Location: kernel/rcu/update.c:602
Inline: True
```
**Symbols:**

```
ffffffff810fa2f0-ffffffff810fa370: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811027f0)
Location: kernel/rcu/update.c:554
Inline: True
```
**Symbols:**

```
ffffffff811027f0-ffffffff8110286d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110e200)
Location: kernel/rcu/update.c:550
Inline: True
```
**Symbols:**

```
ffffffff8110e200-ffffffff8110e27d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81117900)
Location: kernel/rcu/update.c:495
Inline: True
```
**Symbols:**

```
ffffffff81117900-ffffffff8111797d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81123ce0)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffff81123ce0-ffffffff81123d5d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81130c80)
Location: kernel/rcu/tasks.h:505
Inline: False
```
**Symbols:**

```
ffffffff81130c80-ffffffff81130d00: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811738b0)
Location: kernel/rcu/tasks.h:893
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
```
**Symbols:**

```
ffffffff811738b0-ffffffff811738d1: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811aacf0)
Location: kernel/rcu/tasks.h:944
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
```
**Symbols:**

```
ffffffff811aacf0-ffffffff811aad11: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bcc20)
Location: kernel/rcu/tasks.h:981
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
```
**Symbols:**

```
ffffffff811bcc20-ffffffff811bcc41: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cbae0)
Location: kernel/rcu/tasks.h:1074
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_put
  - kernel/bpf/trampoline.c:__bpf_tramp_image_release
```
**Symbols:**

```
ffffffff811cbae0-ffffffff811cbb01: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff800010188a58)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffff800010188a58-ffff800010188b4c: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c03d787c)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
c03d787c-c03d7900: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c0000000001e32c0)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
c0000000001e32c0-c0000000001e339c: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe00011e340)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffe00011e340-ffffffe00011e3cc: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8111c2c0)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffff8111c2c0-ffffffff8111c33d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110d3a0)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffff8110d3a0-ffffffff8110d41d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8111a1b0)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffff8111a1b0-ffffffff8111a22d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void call_rcu_tasks(struct callback_head *rhp, rcu_callback_t func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81125900)
Location: kernel/rcu/update.c:522
Inline: True
```
**Symbols:**

```
ffffffff81125900-ffffffff8112597d: call_rcu_tasks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
