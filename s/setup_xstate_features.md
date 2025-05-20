# Function: <code>setup_xstate_features</code>

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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f6a075)
Location: arch/x86/kernel/fpu/xstate.c:201
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81f92165)
Location: arch/x86/kernel/fpu/xstate.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff81fcd415)
Location: arch/x86/kernel/fpu/xstate.c:257
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff820adad2)
Location: arch/x86/kernel/fpu/xstate.c:258
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff826b4069)
Location: arch/x86/kernel/fpu/xstate.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff826dd83f)
Location: arch/x86/kernel/fpu/xstate.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff82893c87)
Location: arch/x86/kernel/fpu/xstate.c:252
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828ab0ff)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828ae434)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setup_xstate_features();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82cd3355)
Location: arch/x86/kernel/fpu/xstate.c:249
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
```
**Symbols:**

```
ffffffff82cd3355-ffffffff82cd3450: setup_xstate_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setup_xstate_features();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff82fbf10f)
Location: arch/x86/kernel/fpu/xstate.c:253
Inline: False
Direct callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
```
**Symbols:**

```
ffffffff82fbf10f-ffffffff82fbf20a: setup_xstate_features (STB_LOCAL)
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
In arch/x86/kernel/fpu/xstate.c (ffffffff831c9704)
Location: arch/x86/kernel/fpu/xstate.c:253
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
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
In arch/x86/kernel/fpu/xstate.c (ffffffff832aa9d1)
Location: arch/x86/kernel/fpu/xstate.c:168
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:setup_init_fpu_buf
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/fpu/xstate.c (ffffffff8289c453)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff82894671)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828af416)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
In arch/x86/kernel/fpu/xstate.c (ffffffff828af444)
Location: arch/x86/kernel/fpu/xstate.c:246
Inline: True
Inline callers:
  - arch/x86/kernel/fpu/xstate.c:fpu__init_system_xstate
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
</ul>
