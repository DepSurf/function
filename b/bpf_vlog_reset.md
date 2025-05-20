# Function: <code>bpf_vlog_reset</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212e85)
Location: kernel/bpf/verifier.c:291
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
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
In kernel/bpf/verifier.c (ffffffff81213c03)
Location: kernel/bpf/verifier.c:295
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
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
In kernel/bpf/verifier.c (ffffffff812160cb)
Location: kernel/bpf/verifier.c:314
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
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
In kernel/bpf/verifier.c (ffffffff8124c7e0)
Location: kernel/bpf/verifier.c:315
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:pop_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_vlog_reset(struct bpf_verifier_log *log, u32 new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127b060)
Location: kernel/bpf/verifier.c:318
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:pop_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff8127b0e0-ffffffff8127b15f: bpf_vlog_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_vlog_reset(struct bpf_verifier_log *log, u32 new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1b6e)
Location: kernel/bpf/verifier.c:319
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:pop_stack
  - kernel/bpf/verifier.c:pop_stack
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff812d1bf0-ffffffff812d1c6a: bpf_vlog_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_vlog_reset(struct bpf_verifier_log *log, u64 new_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff813228c0)
Location: kernel/bpf/log.c:146
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:print_insn_state
```
**Symbols:**

```
ffffffff813228c0-ffffffff81322966: bpf_vlog_reset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_vlog_reset(struct bpf_verifier_log *log, u64 new_pos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff81345630)
Location: kernel/bpf/log.c:148
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/log.c:print_insn_state
```
**Symbols:**

```
ffffffff81345630-ffffffff813456d6: bpf_vlog_reset (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 new_pos</code> ➡️ <code>u64 new_pos</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
