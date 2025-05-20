# Function: <code>__bpf_tramp_image_put_rcu_tasks</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812223f0)
Location: kernel/bpf/trampoline.c:200
Inline: False
```
**Symbols:**

```
ffffffff812223f0-ffffffff8122241b: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81226d80)
Location: kernel/bpf/trampoline.c:230
Inline: False
```
**Symbols:**

```
ffffffff81226d80-ffffffff81226dab: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8125ee80)
Location: kernel/bpf/trampoline.c:232
Inline: False
```
**Symbols:**

```
ffffffff8125ee80-ffffffff8125eeab: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff812a9420)
Location: kernel/bpf/trampoline.c:232
Inline: True
```
**Symbols:**

```
ffffffff812a9420-ffffffff812a945b: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff81308210)
Location: kernel/bpf/trampoline.c:314
Inline: True
```
**Symbols:**

```
ffffffff81308210-ffffffff8130824b: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff813370e0)
Location: kernel/bpf/trampoline.c:291
Inline: True
```
**Symbols:**

```
ffffffff813370e0-ffffffff8133711b: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_tramp_image_put_rcu_tasks(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/trampoline.c (ffffffff8135cf60)
Location: kernel/bpf/trampoline.c:291
Inline: True
```
**Symbols:**

```
ffffffff8135cf60-ffffffff8135cf9b: __bpf_tramp_image_put_rcu_tasks (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
