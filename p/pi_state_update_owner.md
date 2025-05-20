# Function: <code>pi_state_update_owner</code>

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
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81157a40)
Location: kernel/futex.c:766
Inline: False
Direct callers:
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:wake_futex_pi
```
**Symbols:**

```
ffffffff81157a40-ffffffff81157af0: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81158e80)
Location: kernel/futex.c:765
Inline: False
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81158e80-ffffffff81158f30: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8117dd50)
Location: kernel/futex.c:823
Inline: True
Direct callers:
  - kernel/futex.c:futex_unlock_pi
  - kernel/futex.c:__fixup_pi_state_owner
  - kernel/futex.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff8117dd50-ffffffff8117de00: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811b4760)
Location: kernel/futex/pi.c:45
Inline: True
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff811b4760-ffffffff811b481f: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff811f5800)
Location: kernel/futex/pi.c:45
Inline: True
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff811f5800-ffffffff811f58bf: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff8120a000)
Location: kernel/futex/pi.c:45
Inline: True
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff8120a000-ffffffff8120a0bf: pi_state_update_owner (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pi_state_update_owner(struct futex_pi_state *pi_state, struct task_struct *new_owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex/pi.c (ffffffff81221520)
Location: kernel/futex/pi.c:46
Inline: True
Direct callers:
  - kernel/futex/pi.c:futex_unlock_pi
  - kernel/futex/pi.c:__fixup_pi_state_owner
  - kernel/futex/pi.c:__fixup_pi_state_owner
```
**Symbols:**

```
ffffffff81221520-ffffffff812215df: pi_state_update_owner (STB_LOCAL)
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
