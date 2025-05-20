# Function: <code>bpf_map_ptr_poisoned</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811be790)
Location: kernel/bpf/verifier.c:165
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811cced3)
Location: kernel/bpf/verifier.c:188
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811df6c1)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811ebe82)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120b01c)
Location: kernel/bpf/verifier.c:188
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff8120d1c2)
Location: kernel/bpf/verifier.c:189
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff8120ef5a)
Location: kernel/bpf/verifier.c:189
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffffffff812434db)
Location: kernel/bpf/verifier.c:189
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffffffff81288d42)
Location: kernel/bpf/verifier.c:193
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffffffff812dfd9a)
Location: kernel/bpf/verifier.c:194
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffffffff813025c0)
Location: kernel/bpf/verifier.c:202
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffffffff813226ed)
Location: kernel/bpf/verifier.c:210
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:set_map_elem_callback_state
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
In kernel/bpf/verifier.c (ffff80001026f7a4)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (c04a1c1c)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (c00000000031664c)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffe0001a9198)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811e44a2)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811d7262)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811e2272)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
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
In kernel/bpf/verifier.c (ffffffff811f0682)
Location: kernel/bpf/verifier.c:179
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
```
</details>
</li>
</ul>

## Differences
