# Function: <code>__fixup_pi_state_owner</code>

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
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157d20)
Location: kernel/futex.c:2333
Inline: False
```
**Symbols:**

```
ffffffff81157d20-ffffffff81157fd0: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81159000)
Location: kernel/futex.c:2332
Inline: False
```
**Symbols:**

```
ffffffff81159000-ffffffff811592b0: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117de00)
Location: kernel/futex.c:2580
Inline: False
```
**Symbols:**

```
ffffffff8117de00-ffffffff8117e0b0: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b4820)
Location: kernel/futex/pi.c:683
Inline: False
```
**Symbols:**

```
ffffffff811b4820-ffffffff811b4a9c: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f58d0)
Location: kernel/futex/pi.c:683
Inline: False
```
**Symbols:**

```
ffffffff811f58d0-ffffffff811f5b4c: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120a0d0)
Location: kernel/futex/pi.c:683
Inline: False
```
**Symbols:**

```
ffffffff8120a0d0-ffffffff8120a34c: __fixup_pi_state_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __fixup_pi_state_owner(u32 *uaddr, struct futex_q *q, struct task_struct *argowner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff812215f0)
Location: kernel/futex/pi.c:671
Inline: False
```
**Symbols:**

```
ffffffff812215f0-ffffffff8122186c: __fixup_pi_state_owner (STB_LOCAL)
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
